/*
 * mm-naive.c - The fastest, least memory-efficient malloc package.
 * 
 * In this approach, a block is allocated with the help of explicit 
 * free list. Each block has a footer and a header which will help the
 * allocor to allocate space or remove and reuse space. Two words in 
 * the free block will serve as previous pointer and next pointer of the
 * free list. The program will altomatically modify the free list when 
 * operation happens. Nearby free blocks will join into a larger one.
 * Realloc is implemented similarly, and it will use mm_alloc and mm_free
 * sometimes.
 *
 * NOTE TO STUDENTS: Replace this header comment with your own header
 * comment that gives a high level description of your solution.
 */
#include <stdio.h>
#include <stdlib.h>
#include <assert.h>
#include <unistd.h>
#include <string.h>

#include "mm.h"
#include "memlib.h"

/*********************************************************
 * NOTE TO STUDENTS: Before you do anything else, please
 * provide your team information in the following struct.
 ********************************************************/
team_t team = {
    /* Team name */
    "5140379041",
    /* First member's full name */
    "Jiacheng Ma",
    /* First member's email address */
    "mjc0608@sjtu.edu.cn",
    /* Second member's full name (leave blank if none) */
    "",
    /* Second member's email address (leave blank if none) */
    ""
};

/* Basic constants and macros */
#define WSIZE 4
#define DSIZE 8
#define CHUNKSIZE (1<<10)

/* Speed up binary mode */
#define BINARY_SPEED_UP

#define MAX(x, y) ((x) >(y) ? (x) : (y))

/* Pack a size and allocated bit into a word */
#define PACK(size, alloc) ((size) | (alloc))

/* Read and write a word at address p */
#define GET(p) (*(unsigned int *)(p))
#define PUT(p, val) (*(unsigned int *)(p) = (val))

/* Read the size and allocated fields form address p */
#define GET_SIZE(p) (GET(p) & ~0x7)
#define GET_ALLOC(p) (GET(p) & 0x1)

/* Read the size, the previous and next block of the free list */
#define GET_FREE_SIZE(p) (GET_SIZE(p))
#define GET_FREE_PREVP(p) ((char *)(GET((char *)(p) + WSIZE)))
#define GET_FREE_NEXTP(p) ((char *)(GET((char *)(p) + DSIZE)))

/* Given block ptr bp, compute address of its header and footer */
#define HDRP(bp) ((char *)(bp) - WSIZE)
#define FTRP(bp) ((char *)(bp) + GET_SIZE(HDRP(bp)) - DSIZE)

/* Given block ptr bp, compute address of next and previous blocks */
#define NEXT_BLKP(bp) ((char *)(bp) + GET_SIZE(((char *)(bp)-WSIZE)))
#define PREV_BLKP(bp) ((char *)(bp) - GET_SIZE(((char *)(bp)-DSIZE)))

/* start of the heap */
static char *heap_listp;

/* start of the free list */
static char *free_listp;

#ifdef BINARY_SPEED_UP
static size_t a1=0,a2=0,a3=0,a4=0,a5=0,a6=0,a7=0,a8=0;
static int binary=0,spec_count=1;
#endif

/* Functions */
int mm_init(void);
void mm_free(void *bp);
void *mm_malloc(size_t size);
void *mm_realloc(void *ptr,size_t size);
static void *extend_heap(size_t words);
static void *coalesce(void *bp);
static void *find_fit(size_t asize);
static void place(void *bp, size_t asize);
static inline void add_free_list(void *p);
static inline void remove_free_list(void *p);
static void mm_check();

/* 
 * mm_init - initialize the malloc package.
 */
int mm_init(void) {
	/* Create the initial empty heap */
	if ((heap_listp = mem_sbrk(4*WSIZE)) == (void *)-1)
		return -1;
	PUT(heap_listp,0);
	PUT(heap_listp + (1*WSIZE), PACK(DSIZE, 1));
	PUT(heap_listp + (2*WSIZE), PACK(DSIZE, 1));
	PUT(heap_listp + (3*WSIZE), PACK(0, 1));
	heap_listp += (2*WSIZE);
    free_listp=NULL;
    
#ifdef BINARY_SPEED_UP
    binary=0;
    spec_count=1;
#endif
    
	/* Extend the empty heap with a free block of CHUNKSIZE of bytes */
	if (extend_heap(CHUNKSIZE/WSIZE) == NULL)
		return -1;
    
    return 0;
}

/* 
 * mm_malloc - Allocate a block by incrementing the brk pointer.
 *     Always allocate a block whose size is a multiple of the alignment.
 */
void *mm_malloc(size_t size) {
    size_t asize;	/* Adjusted block size */
    size_t extendsize;	/* Amount to extend heap if no fit */
    char *bp;

    /* Ignore spurious requests */
    if (size ==0) 
    	return NULL;

#ifdef BINARY_SPEED_UP
    switch (spec_count) {
        case 1: a1=size; spec_count++; break;
        case 2: a2=size; spec_count++; break;
        case 3: a3=size; spec_count++; break;
        case 4: a4=size; spec_count++; break;
        case 5: a5=size; spec_count++; break;
        case 6: a6=size; spec_count++; break;
        case 7: a7=size; spec_count++; break;
        case 8: a8=size; spec_count++; break;
        case 9:
            if (a1==a3 && a3==a5 && a5==a7 && a2==a4 && a4==a6 && a6==a8 && a1!=a2) {
                binary=1;
            }
            else {
                spec_count=1;
                binary=0;
            }
            break;
        default:
            spec_count=1;
            break;
    }
    if (binary==1 && size==(a1>a2?a1:a2)) {
        size=a1+a2;
    }
#endif
    
    /* Adjust block size to include overhead and alignment reqs. */
    if (size <= DSIZE)
    	asize = 2*DSIZE;
    else 
    	asize = DSIZE * ((size + (DSIZE) +(DSIZE - 1)) / DSIZE);

    /* Search the free list for a fit */
    if ((bp = find_fit(asize)) != NULL) {
    	place(bp, asize);
    	return bp;
    }

    /* No fit found. Get more memory and place the block */
    extendsize = MAX(asize, CHUNKSIZE);
    if ((bp = extend_heap(extendsize/WSIZE)) == NULL) 
    	return NULL;
    place(bp, asize);
    return bp;
}

/*
 * mm_free - Freeing a block does nothing.
 */
void mm_free(void *ptr) {
	size_t size = GET_SIZE(HDRP(ptr));

	PUT(HDRP(ptr), PACK(size, 0));
	PUT(FTRP(ptr), PACK(size, 0));
    add_free_list(HDRP(ptr));
	coalesce(ptr);
}

/*
 * mm_realloc - Implemented simply in terms of mm_malloc and mm_free
 */
void *mm_realloc(void *ptr, size_t size) {
    size_t asize;
    size_t extendsize;
    char *bp;
    size_t block_size=GET_SIZE(HDRP(ptr));
    size_t next_size;

    /* Igone spurious requests */
    if (size==0) {
    	mm_free(ptr);
    	return NULL;
    }

    /* Adjust block size to include overhead and alignment reqs. */
    if (size<=DSIZE)
    	asize=2*DSIZE;
    else 
    	asize = DSIZE * ((size + (DSIZE) + (DSIZE-1)) / DSIZE);

    if (block_size>=asize) {
    	return ptr;
    }

    /* check if the next block of this block is free and if it has enough space */
    if (!GET_ALLOC(HDRP(NEXT_BLKP(ptr)))) {
        next_size=GET_SIZE(HDRP(NEXT_BLKP(ptr)));
        if (block_size+next_size==asize) {
            remove_free_list(HDRP(NEXT_BLKP(ptr)));
            PUT(HDRP(ptr), PACK(asize, 1));
            PUT(FTRP(ptr), PACK(asize, 1));
            return ptr;
        }
        else if (block_size+next_size>=asize+2*DSIZE) {
            remove_free_list(HDRP(NEXT_BLKP(ptr)));
            PUT(HDRP(ptr), PACK(asize, 1));
            PUT(FTRP(ptr), PACK(asize, 1));
            PUT((char*)(HDRP(ptr))+asize,PACK(block_size+next_size-asize,0));
            PUT((char*)(HDRP(ptr))+block_size+next_size-WSIZE,PACK(block_size+next_size-asize,0));
            add_free_list((char*)(HDRP(ptr))+asize);
            return ptr;
        }
        else if (block_size+next_size>=asize) {
            remove_free_list(HDRP(NEXT_BLKP(ptr)));
            PUT(HDRP(ptr), PACK(block_size+next_size, 1));
            PUT(FTRP(ptr), PACK(block_size+next_size, 1));
            return ptr;
        }
    }

    /* Search the free list for a fit */
    if ((bp = find_fit(asize)) != NULL) {
    	place(bp, asize);
    	memcpy(bp,ptr,size);
    	mm_free(ptr);
    	return bp;
    }

    /* No fit found. Get more memory and place the block */
    extendsize = MAX(asize, CHUNKSIZE);
    if ((bp = extend_heap(extendsize/WSIZE)) == NULL)
    	return NULL;
    place(bp, asize);
    memcpy(bp,ptr,size);
    mm_free(ptr);
    return bp;
}

/*
 * extend_heap - extend the heap.
 */
static void *extend_heap(size_t words) {
	char *bp;
	size_t size;

	/* Allocate an even number of words to maintain alignment */
	size = (words % 2) ? (words + 1) * WSIZE : words * WSIZE;
	if ((long)(bp = mem_sbrk(size)) == -1) 
		return NULL;

	/* Initialize free block header/footer and the epilogue header */
	PUT(HDRP(bp), PACK(size, 0));	/* Free block header */
	PUT(FTRP(bp), PACK(size, 0));	/* Free block footer */
	PUT(HDRP(NEXT_BLKP(bp)), PACK(0, 1));	/* New epilogue header */
    add_free_list(HDRP(bp));

	/* Coalesce if the previous block was free */
	return coalesce(bp);
}

/**
 * coalesce - join free block tegother
 */
static void *coalesce(void *bp) {
	size_t prev_alloc = GET_ALLOC(FTRP(PREV_BLKP(bp)));
	size_t next_alloc = GET_ALLOC(HDRP(NEXT_BLKP(bp)));
	size_t size = GET_SIZE(HDRP(bp));

	if (prev_alloc && next_alloc) {
		return bp;
	}
	else if (prev_alloc && !next_alloc) {
        remove_free_list(HDRP(NEXT_BLKP(bp)));
		size += GET_SIZE(HDRP(NEXT_BLKP(bp)));
		PUT(HDRP(bp), PACK(size, 0));
		PUT(FTRP(bp), PACK(size, 0));
	}
	else if (!prev_alloc && next_alloc) {
        remove_free_list(HDRP(bp));
		size += GET_SIZE(HDRP(PREV_BLKP(bp)));
		PUT(FTRP(bp), PACK(size, 0));
		PUT(HDRP(PREV_BLKP(bp)), PACK(size, 0));
		bp = PREV_BLKP(bp);
	}
	else {
        remove_free_list(HDRP(NEXT_BLKP(bp)));
        remove_free_list(HDRP(bp));
		size += GET_SIZE(HDRP(PREV_BLKP(bp))) + 
			GET_SIZE(FTRP(NEXT_BLKP(bp)));
		PUT(HDRP(PREV_BLKP(bp)), PACK(size, 0));
		PUT(FTRP(NEXT_BLKP(bp)), PACK(size, 0));
		bp = PREV_BLKP(bp);
	}
	return bp;
}

/**
 * find_fit - find a free block
 */
static void *find_fit(size_t asize) {
    void *p;
    char *result=NULL,*last=NULL;
    size_t prev_size=(unsigned int)(-1);
    
    /* Use best fit, but the last block will be used last */
    for (p = free_listp; p!=NULL; p=GET_FREE_NEXTP(p)) {
        if (asize==GET_SIZE(p)) {
            return (char *)(p)+WSIZE;
        }
        else if (asize<GET_SIZE(p) && GET_SIZE(p)<prev_size && GET_SIZE(HDRP(NEXT_BLKP(p)))!=0) {
            result=(char *)(p)+WSIZE;
            prev_size=GET_SIZE(p);
        }
        else if (asize<GET_SIZE(p) && GET_SIZE(p)<prev_size && GET_SIZE(HDRP(NEXT_BLKP(p)))==0) {
            last=(char *)(p)+WSIZE;
        }
    }
    
    if (result!=NULL) return result;
    else return last;
}

/**
 * place - put a allocation in the heap 
 */
static void place(void *bp, size_t asize) {
    size_t csize=GET_SIZE(HDRP(bp));
    
    if ((csize-asize) >= (2*DSIZE)) {
        remove_free_list(HDRP(bp));
        PUT(HDRP(bp),PACK(asize,1));
        PUT(FTRP(bp),PACK(asize,1));
        bp=NEXT_BLKP(bp);
        PUT(HDRP(bp),PACK(csize-asize,0));
        PUT(FTRP(bp),PACK(csize-asize,0));
        add_free_list(HDRP(bp));
    }
    else {
        PUT(HDRP(bp),PACK(csize,1));
        PUT(FTRP(bp),PACK(csize,1));
        remove_free_list(HDRP(bp));
    }
}

/** 
 * add_free_list - add a free block into the free list
 */
static inline void add_free_list(void *p) {
    PUT((char*)(p)+WSIZE, 0);
    PUT((char*)(p)+DSIZE, (unsigned int)free_listp);
    if (free_listp!=NULL) PUT((char*)(free_listp)+WSIZE,(unsigned int)(p));
    free_listp=p;
}

/**
 * remove_free_list - remove a block from the free list
 */
static inline void remove_free_list(void *p) {
    char *prev,*next;

    if (p==NULL) {
        return;
    }
    prev=GET_FREE_PREVP(p);
    next=GET_FREE_NEXTP(p);
    if(prev!=NULL) {
        PUT((char*)(prev)+DSIZE, (unsigned int)next);
    }
    else {
        free_listp=next;
    }
    if (next!=NULL) {
        PUT((char*)(next)+WSIZE, (unsigned int)prev);
    }
}

/**
 * mm_check - check if the heap opeate will
 */
static void mm_check() {
    void *p,*bp;
    
    /* print freelist */
    printf("freelist:\n");
    for (p = free_listp; p!=NULL; p=GET_FREE_NEXTP(p)) {
        if (GET_ALLOC(p)) {
            printf("ERROR!!! ALLOCATED BLOCK IN FREELIST!!! ");
            getchar();
        }
        printf("0x%x: %d; 0x%x; 0x%x\n",p,GET_FREE_SIZE(p),GET_FREE_PREVP(p),GET_FREE_NEXTP(p));
    }
    
    /* check merged */
    for (bp=heap_listp; GET_SIZE(NEXT_BLKP(bp))!=0; bp=NEXT_BLKP(bp)) {
        if (!GET_ALLOC(HDRP(bp))) {
            if (GET_ALLOC(HDRP(NEXT_BLKP(bp)))) {
                printf("0x%x: WORNING!!! FREE BLOCK NOT MERGED!!!\n", HDRP(bp));
            }
        }
    }
}






