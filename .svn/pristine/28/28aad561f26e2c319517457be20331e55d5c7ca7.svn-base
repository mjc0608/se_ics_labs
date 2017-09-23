
bomb:     file format elf32-i386


Disassembly of section .init:

08048734 <_init>:
 8048734:	53                   	push   %ebx
 8048735:	83 ec 08             	sub    $0x8,%esp
 8048738:	e8 83 02 00 00       	call   80489c0 <__x86.get_pc_thunk.bx>
 804873d:	81 c3 bb 29 00 00    	add    $0x29bb,%ebx
 8048743:	8b 83 fc ff ff ff    	mov    -0x4(%ebx),%eax
 8048749:	85 c0                	test   %eax,%eax
 804874b:	74 05                	je     8048752 <_init+0x1e>
 804874d:	e8 2e 01 00 00       	call   8048880 <__gmon_start__@plt>
 8048752:	83 c4 08             	add    $0x8,%esp
 8048755:	5b                   	pop    %ebx
 8048756:	c3                   	ret    

Disassembly of section .plt:

08048760 <cuserid@plt-0x10>:
 8048760:	ff 35 fc b0 04 08    	pushl  0x804b0fc
 8048766:	ff 25 00 b1 04 08    	jmp    *0x804b100
 804876c:	00 00                	add    %al,(%eax)
	...

08048770 <cuserid@plt>:
 8048770:	ff 25 04 b1 04 08    	jmp    *0x804b104
 8048776:	68 00 00 00 00       	push   $0x0
 804877b:	e9 e0 ff ff ff       	jmp    8048760 <_init+0x2c>

08048780 <printf@plt>:
 8048780:	ff 25 08 b1 04 08    	jmp    *0x804b108
 8048786:	68 08 00 00 00       	push   $0x8
 804878b:	e9 d0 ff ff ff       	jmp    8048760 <_init+0x2c>

08048790 <fflush@plt>:
 8048790:	ff 25 0c b1 04 08    	jmp    *0x804b10c
 8048796:	68 10 00 00 00       	push   $0x10
 804879b:	e9 c0 ff ff ff       	jmp    8048760 <_init+0x2c>

080487a0 <dup@plt>:
 80487a0:	ff 25 10 b1 04 08    	jmp    *0x804b110
 80487a6:	68 18 00 00 00       	push   $0x18
 80487ab:	e9 b0 ff ff ff       	jmp    8048760 <_init+0x2c>

080487b0 <inet_pton@plt>:
 80487b0:	ff 25 14 b1 04 08    	jmp    *0x804b114
 80487b6:	68 20 00 00 00       	push   $0x20
 80487bb:	e9 a0 ff ff ff       	jmp    8048760 <_init+0x2c>

080487c0 <fgets@plt>:
 80487c0:	ff 25 18 b1 04 08    	jmp    *0x804b118
 80487c6:	68 28 00 00 00       	push   $0x28
 80487cb:	e9 90 ff ff ff       	jmp    8048760 <_init+0x2c>

080487d0 <fclose@plt>:
 80487d0:	ff 25 1c b1 04 08    	jmp    *0x804b11c
 80487d6:	68 30 00 00 00       	push   $0x30
 80487db:	e9 80 ff ff ff       	jmp    8048760 <_init+0x2c>

080487e0 <signal@plt>:
 80487e0:	ff 25 20 b1 04 08    	jmp    *0x804b120
 80487e6:	68 38 00 00 00       	push   $0x38
 80487eb:	e9 70 ff ff ff       	jmp    8048760 <_init+0x2c>

080487f0 <sleep@plt>:
 80487f0:	ff 25 24 b1 04 08    	jmp    *0x804b124
 80487f6:	68 40 00 00 00       	push   $0x40
 80487fb:	e9 60 ff ff ff       	jmp    8048760 <_init+0x2c>

08048800 <rewind@plt>:
 8048800:	ff 25 28 b1 04 08    	jmp    *0x804b128
 8048806:	68 48 00 00 00       	push   $0x48
 804880b:	e9 50 ff ff ff       	jmp    8048760 <_init+0x2c>

08048810 <fwrite@plt>:
 8048810:	ff 25 2c b1 04 08    	jmp    *0x804b12c
 8048816:	68 50 00 00 00       	push   $0x50
 804881b:	e9 40 ff ff ff       	jmp    8048760 <_init+0x2c>

08048820 <bcopy@plt>:
 8048820:	ff 25 30 b1 04 08    	jmp    *0x804b130
 8048826:	68 58 00 00 00       	push   $0x58
 804882b:	e9 30 ff ff ff       	jmp    8048760 <_init+0x2c>

08048830 <strcat@plt>:
 8048830:	ff 25 34 b1 04 08    	jmp    *0x804b134
 8048836:	68 60 00 00 00       	push   $0x60
 804883b:	e9 20 ff ff ff       	jmp    8048760 <_init+0x2c>

08048840 <strcpy@plt>:
 8048840:	ff 25 38 b1 04 08    	jmp    *0x804b138
 8048846:	68 68 00 00 00       	push   $0x68
 804884b:	e9 10 ff ff ff       	jmp    8048760 <_init+0x2c>

08048850 <getenv@plt>:
 8048850:	ff 25 3c b1 04 08    	jmp    *0x804b13c
 8048856:	68 70 00 00 00       	push   $0x70
 804885b:	e9 00 ff ff ff       	jmp    8048760 <_init+0x2c>

08048860 <puts@plt>:
 8048860:	ff 25 40 b1 04 08    	jmp    *0x804b140
 8048866:	68 78 00 00 00       	push   $0x78
 804886b:	e9 f0 fe ff ff       	jmp    8048760 <_init+0x2c>

08048870 <system@plt>:
 8048870:	ff 25 44 b1 04 08    	jmp    *0x804b144
 8048876:	68 80 00 00 00       	push   $0x80
 804887b:	e9 e0 fe ff ff       	jmp    8048760 <_init+0x2c>

08048880 <__gmon_start__@plt>:
 8048880:	ff 25 48 b1 04 08    	jmp    *0x804b148
 8048886:	68 88 00 00 00       	push   $0x88
 804888b:	e9 d0 fe ff ff       	jmp    8048760 <_init+0x2c>

08048890 <exit@plt>:
 8048890:	ff 25 4c b1 04 08    	jmp    *0x804b14c
 8048896:	68 90 00 00 00       	push   $0x90
 804889b:	e9 c0 fe ff ff       	jmp    8048760 <_init+0x2c>

080488a0 <__libc_start_main@plt>:
 80488a0:	ff 25 50 b1 04 08    	jmp    *0x804b150
 80488a6:	68 98 00 00 00       	push   $0x98
 80488ab:	e9 b0 fe ff ff       	jmp    8048760 <_init+0x2c>

080488b0 <fprintf@plt>:
 80488b0:	ff 25 54 b1 04 08    	jmp    *0x804b154
 80488b6:	68 a0 00 00 00       	push   $0xa0
 80488bb:	e9 a0 fe ff ff       	jmp    8048760 <_init+0x2c>

080488c0 <write@plt>:
 80488c0:	ff 25 58 b1 04 08    	jmp    *0x804b158
 80488c6:	68 a8 00 00 00       	push   $0xa8
 80488cb:	e9 90 fe ff ff       	jmp    8048760 <_init+0x2c>

080488d0 <__isoc99_sscanf@plt>:
 80488d0:	ff 25 5c b1 04 08    	jmp    *0x804b15c
 80488d6:	68 b0 00 00 00       	push   $0xb0
 80488db:	e9 80 fe ff ff       	jmp    8048760 <_init+0x2c>

080488e0 <fopen@plt>:
 80488e0:	ff 25 60 b1 04 08    	jmp    *0x804b160
 80488e6:	68 b8 00 00 00       	push   $0xb8
 80488eb:	e9 70 fe ff ff       	jmp    8048760 <_init+0x2c>

080488f0 <__errno_location@plt>:
 80488f0:	ff 25 64 b1 04 08    	jmp    *0x804b164
 80488f6:	68 c0 00 00 00       	push   $0xc0
 80488fb:	e9 60 fe ff ff       	jmp    8048760 <_init+0x2c>

08048900 <fputc@plt>:
 8048900:	ff 25 68 b1 04 08    	jmp    *0x804b168
 8048906:	68 c8 00 00 00       	push   $0xc8
 804890b:	e9 50 fe ff ff       	jmp    8048760 <_init+0x2c>

08048910 <sprintf@plt>:
 8048910:	ff 25 6c b1 04 08    	jmp    *0x804b16c
 8048916:	68 d0 00 00 00       	push   $0xd0
 804891b:	e9 40 fe ff ff       	jmp    8048760 <_init+0x2c>

08048920 <tmpfile@plt>:
 8048920:	ff 25 70 b1 04 08    	jmp    *0x804b170
 8048926:	68 d8 00 00 00       	push   $0xd8
 804892b:	e9 30 fe ff ff       	jmp    8048760 <_init+0x2c>

08048930 <socket@plt>:
 8048930:	ff 25 74 b1 04 08    	jmp    *0x804b174
 8048936:	68 e0 00 00 00       	push   $0xe0
 804893b:	e9 20 fe ff ff       	jmp    8048760 <_init+0x2c>

08048940 <gethostbyname@plt>:
 8048940:	ff 25 78 b1 04 08    	jmp    *0x804b178
 8048946:	68 e8 00 00 00       	push   $0xe8
 804894b:	e9 10 fe ff ff       	jmp    8048760 <_init+0x2c>

08048950 <strtol@plt>:
 8048950:	ff 25 7c b1 04 08    	jmp    *0x804b17c
 8048956:	68 f0 00 00 00       	push   $0xf0
 804895b:	e9 00 fe ff ff       	jmp    8048760 <_init+0x2c>

08048960 <connect@plt>:
 8048960:	ff 25 80 b1 04 08    	jmp    *0x804b180
 8048966:	68 f8 00 00 00       	push   $0xf8
 804896b:	e9 f0 fd ff ff       	jmp    8048760 <_init+0x2c>

08048970 <close@plt>:
 8048970:	ff 25 84 b1 04 08    	jmp    *0x804b184
 8048976:	68 00 01 00 00       	push   $0x100
 804897b:	e9 e0 fd ff ff       	jmp    8048760 <_init+0x2c>

08048980 <__ctype_b_loc@plt>:
 8048980:	ff 25 88 b1 04 08    	jmp    *0x804b188
 8048986:	68 08 01 00 00       	push   $0x108
 804898b:	e9 d0 fd ff ff       	jmp    8048760 <_init+0x2c>

Disassembly of section .text:

08048990 <_start>:
 8048990:	31 ed                	xor    %ebp,%ebp
 8048992:	5e                   	pop    %esi
 8048993:	89 e1                	mov    %esp,%ecx
 8048995:	83 e4 f0             	and    $0xfffffff0,%esp
 8048998:	50                   	push   %eax
 8048999:	54                   	push   %esp
 804899a:	52                   	push   %edx
 804899b:	68 60 99 04 08       	push   $0x8049960
 80489a0:	68 f0 98 04 08       	push   $0x80498f0
 80489a5:	51                   	push   %ecx
 80489a6:	56                   	push   %esi
 80489a7:	68 8b 8a 04 08       	push   $0x8048a8b
 80489ac:	e8 ef fe ff ff       	call   80488a0 <__libc_start_main@plt>
 80489b1:	f4                   	hlt    
 80489b2:	66 90                	xchg   %ax,%ax
 80489b4:	66 90                	xchg   %ax,%ax
 80489b6:	66 90                	xchg   %ax,%ax
 80489b8:	66 90                	xchg   %ax,%ax
 80489ba:	66 90                	xchg   %ax,%ax
 80489bc:	66 90                	xchg   %ax,%ax
 80489be:	66 90                	xchg   %ax,%ax

080489c0 <__x86.get_pc_thunk.bx>:
 80489c0:	8b 1c 24             	mov    (%esp),%ebx
 80489c3:	c3                   	ret    
 80489c4:	66 90                	xchg   %ax,%ax
 80489c6:	66 90                	xchg   %ax,%ax
 80489c8:	66 90                	xchg   %ax,%ax
 80489ca:	66 90                	xchg   %ax,%ax
 80489cc:	66 90                	xchg   %ax,%ax
 80489ce:	66 90                	xchg   %ax,%ax

080489d0 <deregister_tm_clones>:
 80489d0:	b8 07 b7 04 08       	mov    $0x804b707,%eax
 80489d5:	2d 04 b7 04 08       	sub    $0x804b704,%eax
 80489da:	83 f8 06             	cmp    $0x6,%eax
 80489dd:	76 1a                	jbe    80489f9 <deregister_tm_clones+0x29>
 80489df:	b8 00 00 00 00       	mov    $0x0,%eax
 80489e4:	85 c0                	test   %eax,%eax
 80489e6:	74 11                	je     80489f9 <deregister_tm_clones+0x29>
 80489e8:	55                   	push   %ebp
 80489e9:	89 e5                	mov    %esp,%ebp
 80489eb:	83 ec 14             	sub    $0x14,%esp
 80489ee:	68 04 b7 04 08       	push   $0x804b704
 80489f3:	ff d0                	call   *%eax
 80489f5:	83 c4 10             	add    $0x10,%esp
 80489f8:	c9                   	leave  
 80489f9:	f3 c3                	repz ret 
 80489fb:	90                   	nop
 80489fc:	8d 74 26 00          	lea    0x0(%esi,%eiz,1),%esi

08048a00 <register_tm_clones>:
 8048a00:	b8 04 b7 04 08       	mov    $0x804b704,%eax
 8048a05:	2d 04 b7 04 08       	sub    $0x804b704,%eax
 8048a0a:	c1 f8 02             	sar    $0x2,%eax
 8048a0d:	89 c2                	mov    %eax,%edx
 8048a0f:	c1 ea 1f             	shr    $0x1f,%edx
 8048a12:	01 d0                	add    %edx,%eax
 8048a14:	d1 f8                	sar    %eax
 8048a16:	74 1b                	je     8048a33 <register_tm_clones+0x33>
 8048a18:	ba 00 00 00 00       	mov    $0x0,%edx
 8048a1d:	85 d2                	test   %edx,%edx
 8048a1f:	74 12                	je     8048a33 <register_tm_clones+0x33>
 8048a21:	55                   	push   %ebp
 8048a22:	89 e5                	mov    %esp,%ebp
 8048a24:	83 ec 10             	sub    $0x10,%esp
 8048a27:	50                   	push   %eax
 8048a28:	68 04 b7 04 08       	push   $0x804b704
 8048a2d:	ff d2                	call   *%edx
 8048a2f:	83 c4 10             	add    $0x10,%esp
 8048a32:	c9                   	leave  
 8048a33:	f3 c3                	repz ret 
 8048a35:	8d 74 26 00          	lea    0x0(%esi,%eiz,1),%esi
 8048a39:	8d bc 27 00 00 00 00 	lea    0x0(%edi,%eiz,1),%edi

08048a40 <__do_global_dtors_aux>:
 8048a40:	80 3d 64 b7 04 08 00 	cmpb   $0x0,0x804b764
 8048a47:	75 13                	jne    8048a5c <__do_global_dtors_aux+0x1c>
 8048a49:	55                   	push   %ebp
 8048a4a:	89 e5                	mov    %esp,%ebp
 8048a4c:	83 ec 08             	sub    $0x8,%esp
 8048a4f:	e8 7c ff ff ff       	call   80489d0 <deregister_tm_clones>
 8048a54:	c6 05 64 b7 04 08 01 	movb   $0x1,0x804b764
 8048a5b:	c9                   	leave  
 8048a5c:	f3 c3                	repz ret 
 8048a5e:	66 90                	xchg   %ax,%ax

08048a60 <frame_dummy>:
 8048a60:	b8 08 b0 04 08       	mov    $0x804b008,%eax
 8048a65:	8b 10                	mov    (%eax),%edx
 8048a67:	85 d2                	test   %edx,%edx
 8048a69:	75 05                	jne    8048a70 <frame_dummy+0x10>
 8048a6b:	eb 93                	jmp    8048a00 <register_tm_clones>
 8048a6d:	8d 76 00             	lea    0x0(%esi),%esi
 8048a70:	ba 00 00 00 00       	mov    $0x0,%edx
 8048a75:	85 d2                	test   %edx,%edx
 8048a77:	74 f2                	je     8048a6b <frame_dummy+0xb>
 8048a79:	55                   	push   %ebp
 8048a7a:	89 e5                	mov    %esp,%ebp
 8048a7c:	83 ec 14             	sub    $0x14,%esp
 8048a7f:	50                   	push   %eax
 8048a80:	ff d2                	call   *%edx
 8048a82:	83 c4 10             	add    $0x10,%esp
 8048a85:	c9                   	leave  
 8048a86:	e9 75 ff ff ff       	jmp    8048a00 <register_tm_clones>

08048a8b <main>:
 8048a8b:	8d 4c 24 04          	lea    0x4(%esp),%ecx
 8048a8f:	83 e4 f0             	and    $0xfffffff0,%esp
 8048a92:	ff 71 fc             	pushl  -0x4(%ecx)
 8048a95:	55                   	push   %ebp
 8048a96:	89 e5                	mov    %esp,%ebp
 8048a98:	53                   	push   %ebx
 8048a99:	51                   	push   %ecx
 8048a9a:	8b 01                	mov    (%ecx),%eax
 8048a9c:	8b 59 04             	mov    0x4(%ecx),%ebx
 8048a9f:	83 f8 01             	cmp    $0x1,%eax
 8048aa2:	75 0c                	jne    8048ab0 <main+0x25>
 8048aa4:	a1 40 b7 04 08       	mov    0x804b740,%eax
 8048aa9:	a3 6c b7 04 08       	mov    %eax,0x804b76c
 8048aae:	eb 5a                	jmp    8048b0a <main+0x7f>
 8048ab0:	83 f8 02             	cmp    $0x2,%eax
 8048ab3:	75 3a                	jne    8048aef <main+0x64>
 8048ab5:	83 ec 08             	sub    $0x8,%esp
 8048ab8:	68 cf 9d 04 08       	push   $0x8049dcf
 8048abd:	ff 73 04             	pushl  0x4(%ebx)
 8048ac0:	e8 1b fe ff ff       	call   80488e0 <fopen@plt>
 8048ac5:	a3 6c b7 04 08       	mov    %eax,0x804b76c
 8048aca:	83 c4 10             	add    $0x10,%esp
 8048acd:	85 c0                	test   %eax,%eax
 8048acf:	75 39                	jne    8048b0a <main+0x7f>
 8048ad1:	83 ec 04             	sub    $0x4,%esp
 8048ad4:	ff 73 04             	pushl  0x4(%ebx)
 8048ad7:	ff 33                	pushl  (%ebx)
 8048ad9:	68 88 99 04 08       	push   $0x8049988
 8048ade:	e8 9d fc ff ff       	call   8048780 <printf@plt>
 8048ae3:	c7 04 24 08 00 00 00 	movl   $0x8,(%esp)
 8048aea:	e8 a1 fd ff ff       	call   8048890 <exit@plt>
 8048aef:	83 ec 08             	sub    $0x8,%esp
 8048af2:	ff 33                	pushl  (%ebx)
 8048af4:	68 a5 99 04 08       	push   $0x80499a5
 8048af9:	e8 82 fc ff ff       	call   8048780 <printf@plt>
 8048afe:	c7 04 24 08 00 00 00 	movl   $0x8,(%esp)
 8048b05:	e8 86 fd ff ff       	call   8048890 <exit@plt>
 8048b0a:	e8 d0 05 00 00       	call   80490df <initialize_bomb>
 8048b0f:	83 ec 0c             	sub    $0xc,%esp
 8048b12:	68 0c 9a 04 08       	push   $0x8049a0c
 8048b17:	e8 44 fd ff ff       	call   8048860 <puts@plt>
 8048b1c:	c7 04 24 48 9a 04 08 	movl   $0x8049a48,(%esp)
 8048b23:	e8 38 fd ff ff       	call   8048860 <puts@plt>
 8048b28:	e8 65 0c 00 00       	call   8049792 <read_line>
 8048b2d:	89 04 24             	mov    %eax,(%esp)
 8048b30:	e8 ad 00 00 00       	call   8048be2 <phase_1>
 8048b35:	e8 1f 0d 00 00       	call   8049859 <phase_defused>
 8048b3a:	c7 04 24 74 9a 04 08 	movl   $0x8049a74,(%esp)
 8048b41:	e8 1a fd ff ff       	call   8048860 <puts@plt>
 8048b46:	e8 47 0c 00 00       	call   8049792 <read_line>
 8048b4b:	89 04 24             	mov    %eax,(%esp)
 8048b4e:	e8 b0 00 00 00       	call   8048c03 <phase_2>
 8048b53:	e8 01 0d 00 00       	call   8049859 <phase_defused>
 8048b58:	c7 04 24 bf 99 04 08 	movl   $0x80499bf,(%esp)
 8048b5f:	e8 fc fc ff ff       	call   8048860 <puts@plt>
 8048b64:	e8 29 0c 00 00       	call   8049792 <read_line>
 8048b69:	89 04 24             	mov    %eax,(%esp)
 8048b6c:	e8 df 00 00 00       	call   8048c50 <phase_3>
 8048b71:	e8 e3 0c 00 00       	call   8049859 <phase_defused>
 8048b76:	c7 04 24 dd 99 04 08 	movl   $0x80499dd,(%esp)
 8048b7d:	e8 de fc ff ff       	call   8048860 <puts@plt>
 8048b82:	e8 0b 0c 00 00       	call   8049792 <read_line>
 8048b87:	89 04 24             	mov    %eax,(%esp)
 8048b8a:	e8 7a 01 00 00       	call   8048d09 <phase_4>
 8048b8f:	e8 c5 0c 00 00       	call   8049859 <phase_defused>
 8048b94:	c7 04 24 a0 9a 04 08 	movl   $0x8049aa0,(%esp)
 8048b9b:	e8 c0 fc ff ff       	call   8048860 <puts@plt>
 8048ba0:	e8 ed 0b 00 00       	call   8049792 <read_line>
 8048ba5:	89 04 24             	mov    %eax,(%esp)
 8048ba8:	e8 a5 01 00 00       	call   8048d52 <phase_5>
 8048bad:	e8 a7 0c 00 00       	call   8049859 <phase_defused>
 8048bb2:	c7 04 24 ec 99 04 08 	movl   $0x80499ec,(%esp)
 8048bb9:	e8 a2 fc ff ff       	call   8048860 <puts@plt>
 8048bbe:	e8 cf 0b 00 00       	call   8049792 <read_line>
 8048bc3:	89 04 24             	mov    %eax,(%esp)
 8048bc6:	e8 cf 01 00 00       	call   8048d9a <phase_6>
 8048bcb:	e8 89 0c 00 00       	call   8049859 <phase_defused>
 8048bd0:	83 c4 10             	add    $0x10,%esp
 8048bd3:	b8 00 00 00 00       	mov    $0x0,%eax
 8048bd8:	8d 65 f8             	lea    -0x8(%ebp),%esp
 8048bdb:	59                   	pop    %ecx
 8048bdc:	5b                   	pop    %ebx
 8048bdd:	5d                   	pop    %ebp
 8048bde:	8d 61 fc             	lea    -0x4(%ecx),%esp
 8048be1:	c3                   	ret    

08048be2 <phase_1>:
 8048be2:	83 ec 14             	sub    $0x14,%esp
 8048be5:	68 c4 9a 04 08       	push   $0x8049ac4
 8048bea:	ff 74 24 1c          	pushl  0x1c(%esp)
 8048bee:	e8 ab 03 00 00       	call   8048f9e <strings_not_equal>
 8048bf3:	83 c4 10             	add    $0x10,%esp
 8048bf6:	85 c0                	test   %eax,%eax
 8048bf8:	74 05                	je     8048bff <phase_1+0x1d>
 8048bfa:	e8 1b 0b 00 00       	call   804971a <explode_bomb>
 8048bff:	83 c4 0c             	add    $0xc,%esp
 8048c02:	c3                   	ret    

08048c03 <phase_2>:
 8048c03:	53                   	push   %ebx
 8048c04:	83 ec 30             	sub    $0x30,%esp
 8048c07:	8d 44 24 10          	lea    0x10(%esp),%eax
 8048c0b:	50                   	push   %eax
 8048c0c:	ff 74 24 3c          	pushl  0x3c(%esp)
 8048c10:	e8 42 0b 00 00       	call   8049757 <read_six_numbers>
 8048c15:	83 c4 10             	add    $0x10,%esp
 8048c18:	83 7c 24 08 01       	cmpl   $0x1,0x8(%esp)
 8048c1d:	74 25                	je     8048c44 <phase_2+0x41>
 8048c1f:	e8 f6 0a 00 00       	call   804971a <explode_bomb>
 8048c24:	eb 1e                	jmp    8048c44 <phase_2+0x41>
 8048c26:	89 d8                	mov    %ebx,%eax
 8048c28:	83 c3 01             	add    $0x1,%ebx
 8048c2b:	89 da                	mov    %ebx,%edx
 8048c2d:	0f af 54 84 04       	imul   0x4(%esp,%eax,4),%edx
 8048c32:	39 54 84 08          	cmp    %edx,0x8(%esp,%eax,4)
 8048c36:	74 05                	je     8048c3d <phase_2+0x3a>
 8048c38:	e8 dd 0a 00 00       	call   804971a <explode_bomb>
 8048c3d:	83 fb 06             	cmp    $0x6,%ebx
 8048c40:	75 e4                	jne    8048c26 <phase_2+0x23>
 8048c42:	eb 07                	jmp    8048c4b <phase_2+0x48>
 8048c44:	bb 01 00 00 00       	mov    $0x1,%ebx
 8048c49:	eb db                	jmp    8048c26 <phase_2+0x23>
 8048c4b:	83 c4 28             	add    $0x28,%esp
 8048c4e:	5b                   	pop    %ebx
 8048c4f:	c3                   	ret    

08048c50 <phase_3>:
 8048c50:	83 ec 1c             	sub    $0x1c,%esp
 8048c53:	8d 44 24 08          	lea    0x8(%esp),%eax
 8048c57:	50                   	push   %eax
 8048c58:	8d 44 24 10          	lea    0x10(%esp),%eax
 8048c5c:	50                   	push   %eax
 8048c5d:	68 d8 9e 04 08       	push   $0x8049ed8
 8048c62:	ff 74 24 2c          	pushl  0x2c(%esp)
 8048c66:	e8 65 fc ff ff       	call   80488d0 <__isoc99_sscanf@plt>
 8048c6b:	83 c4 10             	add    $0x10,%esp
 8048c6e:	83 f8 01             	cmp    $0x1,%eax
 8048c71:	7f 05                	jg     8048c78 <phase_3+0x28>
 8048c73:	e8 a2 0a 00 00       	call   804971a <explode_bomb>
 8048c78:	83 7c 24 0c 07       	cmpl   $0x7,0xc(%esp)
 8048c7d:	77 3c                	ja     8048cbb <phase_3+0x6b>
 8048c7f:	8b 44 24 0c          	mov    0xc(%esp),%eax
 8048c83:	ff 24 85 40 9b 04 08 	jmp    *0x8049b40(,%eax,4)
 8048c8a:	b8 18 01 00 00       	mov    $0x118,%eax
 8048c8f:	eb 3b                	jmp    8048ccc <phase_3+0x7c>
 8048c91:	b8 82 03 00 00       	mov    $0x382,%eax
 8048c96:	eb 34                	jmp    8048ccc <phase_3+0x7c>
 8048c98:	b8 d0 03 00 00       	mov    $0x3d0,%eax
 8048c9d:	eb 2d                	jmp    8048ccc <phase_3+0x7c>
 8048c9f:	b8 33 00 00 00       	mov    $0x33,%eax
 8048ca4:	eb 26                	jmp    8048ccc <phase_3+0x7c>
 8048ca6:	b8 5b 02 00 00       	mov    $0x25b,%eax
 8048cab:	eb 1f                	jmp    8048ccc <phase_3+0x7c>
 8048cad:	b8 c3 00 00 00       	mov    $0xc3,%eax
 8048cb2:	eb 18                	jmp    8048ccc <phase_3+0x7c>
 8048cb4:	b8 94 01 00 00       	mov    $0x194,%eax
 8048cb9:	eb 11                	jmp    8048ccc <phase_3+0x7c>
 8048cbb:	e8 5a 0a 00 00       	call   804971a <explode_bomb>
 8048cc0:	b8 00 00 00 00       	mov    $0x0,%eax
 8048cc5:	eb 05                	jmp    8048ccc <phase_3+0x7c>
 8048cc7:	b8 06 02 00 00       	mov    $0x206,%eax
 8048ccc:	3b 44 24 08          	cmp    0x8(%esp),%eax
 8048cd0:	74 05                	je     8048cd7 <phase_3+0x87>
 8048cd2:	e8 43 0a 00 00       	call   804971a <explode_bomb>
 8048cd7:	83 c4 1c             	add    $0x1c,%esp
 8048cda:	c3                   	ret    

08048cdb <func4>:
 8048cdb:	83 ec 0c             	sub    $0xc,%esp
 8048cde:	8b 54 24 10          	mov    0x10(%esp),%edx
 8048ce2:	b8 01 00 00 00       	mov    $0x1,%eax
 8048ce7:	85 d2                	test   %edx,%edx
 8048ce9:	7e 1a                	jle    8048d05 <func4+0x2a>
 8048ceb:	83 ec 0c             	sub    $0xc,%esp
 8048cee:	83 ea 01             	sub    $0x1,%edx
 8048cf1:	52                   	push   %edx
 8048cf2:	e8 e4 ff ff ff       	call   8048cdb <func4>
 8048cf7:	83 c4 10             	add    $0x10,%esp
 8048cfa:	8d 14 c5 00 00 00 00 	lea    0x0(,%eax,8),%edx
 8048d01:	29 c2                	sub    %eax,%edx
 8048d03:	89 d0                	mov    %edx,%eax
 8048d05:	83 c4 0c             	add    $0xc,%esp
 8048d08:	c3                   	ret    

08048d09 <phase_4>:
 8048d09:	83 ec 20             	sub    $0x20,%esp
 8048d0c:	8d 44 24 10          	lea    0x10(%esp),%eax
 8048d10:	50                   	push   %eax
 8048d11:	68 db 9e 04 08       	push   $0x8049edb
 8048d16:	ff 74 24 2c          	pushl  0x2c(%esp)
 8048d1a:	e8 b1 fb ff ff       	call   80488d0 <__isoc99_sscanf@plt>
 8048d1f:	83 c4 10             	add    $0x10,%esp
 8048d22:	83 f8 01             	cmp    $0x1,%eax
 8048d25:	75 07                	jne    8048d2e <phase_4+0x25>
 8048d27:	83 7c 24 0c 00       	cmpl   $0x0,0xc(%esp)
 8048d2c:	7f 05                	jg     8048d33 <phase_4+0x2a>
 8048d2e:	e8 e7 09 00 00       	call   804971a <explode_bomb>
 8048d33:	83 ec 0c             	sub    $0xc,%esp
 8048d36:	ff 74 24 18          	pushl  0x18(%esp)
 8048d3a:	e8 9c ff ff ff       	call   8048cdb <func4>
 8048d3f:	83 c4 10             	add    $0x10,%esp
 8048d42:	3d f7 90 0c 00       	cmp    $0xc90f7,%eax
 8048d47:	74 05                	je     8048d4e <phase_4+0x45>
 8048d49:	e8 cc 09 00 00       	call   804971a <explode_bomb>
 8048d4e:	83 c4 1c             	add    $0x1c,%esp
 8048d51:	c3                   	ret    

08048d52 <phase_5>:
 8048d52:	53                   	push   %ebx
 8048d53:	83 ec 14             	sub    $0x14,%esp
 8048d56:	8b 5c 24 1c          	mov    0x1c(%esp),%ebx
 8048d5a:	53                   	push   %ebx
 8048d5b:	e8 1f 02 00 00       	call   8048f7f <string_length>
 8048d60:	83 c4 10             	add    $0x10,%esp
 8048d63:	83 f8 06             	cmp    $0x6,%eax
 8048d66:	74 05                	je     8048d6d <phase_5+0x1b>
 8048d68:	e8 ad 09 00 00       	call   804971a <explode_bomb>
 8048d6d:	89 d8                	mov    %ebx,%eax
 8048d6f:	83 c3 06             	add    $0x6,%ebx
 8048d72:	b9 00 00 00 00       	mov    $0x0,%ecx
 8048d77:	0f b6 10             	movzbl (%eax),%edx
 8048d7a:	83 e2 0f             	and    $0xf,%edx
 8048d7d:	03 0c 95 80 9b 04 08 	add    0x8049b80(,%edx,4),%ecx
 8048d84:	83 c0 01             	add    $0x1,%eax
 8048d87:	39 d8                	cmp    %ebx,%eax
 8048d89:	75 ec                	jne    8048d77 <phase_5+0x25>
 8048d8b:	83 f9 41             	cmp    $0x41,%ecx
 8048d8e:	74 05                	je     8048d95 <phase_5+0x43>
 8048d90:	e8 85 09 00 00       	call   804971a <explode_bomb>
 8048d95:	83 c4 08             	add    $0x8,%esp
 8048d98:	5b                   	pop    %ebx
 8048d99:	c3                   	ret    

08048d9a <phase_6>:
 8048d9a:	56                   	push   %esi
 8048d9b:	53                   	push   %ebx
 8048d9c:	83 ec 3c             	sub    $0x3c,%esp
 8048d9f:	8d 44 24 20          	lea    0x20(%esp),%eax
 8048da3:	50                   	push   %eax
 8048da4:	ff 74 24 4c          	pushl  0x4c(%esp)
 8048da8:	e8 aa 09 00 00       	call   8049757 <read_six_numbers>
 8048dad:	83 c4 10             	add    $0x10,%esp
 8048db0:	be 00 00 00 00       	mov    $0x0,%esi
 8048db5:	8b 44 b4 18          	mov    0x18(%esp,%esi,4),%eax
 8048db9:	83 e8 01             	sub    $0x1,%eax
 8048dbc:	83 f8 05             	cmp    $0x5,%eax
 8048dbf:	76 05                	jbe    8048dc6 <phase_6+0x2c>
 8048dc1:	e8 54 09 00 00       	call   804971a <explode_bomb>
 8048dc6:	83 c6 01             	add    $0x1,%esi
 8048dc9:	83 fe 06             	cmp    $0x6,%esi
 8048dcc:	74 32                	je     8048e00 <phase_6+0x66>
 8048dce:	89 f3                	mov    %esi,%ebx
 8048dd0:	8b 44 9c 18          	mov    0x18(%esp,%ebx,4),%eax
 8048dd4:	39 44 b4 14          	cmp    %eax,0x14(%esp,%esi,4)
 8048dd8:	75 05                	jne    8048ddf <phase_6+0x45>
 8048dda:	e8 3b 09 00 00       	call   804971a <explode_bomb>
 8048ddf:	83 c3 01             	add    $0x1,%ebx
 8048de2:	83 fb 05             	cmp    $0x5,%ebx
 8048de5:	7e e9                	jle    8048dd0 <phase_6+0x36>
 8048de7:	eb cc                	jmp    8048db5 <phase_6+0x1b>
 8048de9:	8b 52 08             	mov    0x8(%edx),%edx
 8048dec:	83 c0 01             	add    $0x1,%eax
 8048def:	39 c8                	cmp    %ecx,%eax
 8048df1:	75 f6                	jne    8048de9 <phase_6+0x4f>
 8048df3:	89 14 b4             	mov    %edx,(%esp,%esi,4)
 8048df6:	83 c3 01             	add    $0x1,%ebx
 8048df9:	83 fb 06             	cmp    $0x6,%ebx
 8048dfc:	75 07                	jne    8048e05 <phase_6+0x6b>
 8048dfe:	eb 1c                	jmp    8048e1c <phase_6+0x82>
 8048e00:	bb 00 00 00 00       	mov    $0x0,%ebx
 8048e05:	89 de                	mov    %ebx,%esi
 8048e07:	8b 4c 9c 18          	mov    0x18(%esp,%ebx,4),%ecx
 8048e0b:	b8 01 00 00 00       	mov    $0x1,%eax
 8048e10:	ba b4 b2 04 08       	mov    $0x804b2b4,%edx
 8048e15:	83 f9 01             	cmp    $0x1,%ecx
 8048e18:	7f cf                	jg     8048de9 <phase_6+0x4f>
 8048e1a:	eb d7                	jmp    8048df3 <phase_6+0x59>
 8048e1c:	8b 1c 24             	mov    (%esp),%ebx
 8048e1f:	89 e0                	mov    %esp,%eax
 8048e21:	8d 74 24 14          	lea    0x14(%esp),%esi
 8048e25:	89 d9                	mov    %ebx,%ecx
 8048e27:	8b 50 04             	mov    0x4(%eax),%edx
 8048e2a:	89 51 08             	mov    %edx,0x8(%ecx)
 8048e2d:	83 c0 04             	add    $0x4,%eax
 8048e30:	89 d1                	mov    %edx,%ecx
 8048e32:	39 f0                	cmp    %esi,%eax
 8048e34:	75 f1                	jne    8048e27 <phase_6+0x8d>
 8048e36:	c7 42 08 00 00 00 00 	movl   $0x0,0x8(%edx)
 8048e3d:	be 05 00 00 00       	mov    $0x5,%esi
 8048e42:	8b 43 08             	mov    0x8(%ebx),%eax
 8048e45:	8b 00                	mov    (%eax),%eax
 8048e47:	39 03                	cmp    %eax,(%ebx)
 8048e49:	7d 05                	jge    8048e50 <phase_6+0xb6>
 8048e4b:	e8 ca 08 00 00       	call   804971a <explode_bomb>
 8048e50:	8b 5b 08             	mov    0x8(%ebx),%ebx
 8048e53:	83 ee 01             	sub    $0x1,%esi
 8048e56:	75 ea                	jne    8048e42 <phase_6+0xa8>
 8048e58:	83 c4 34             	add    $0x34,%esp
 8048e5b:	5b                   	pop    %ebx
 8048e5c:	5e                   	pop    %esi
 8048e5d:	c3                   	ret    

08048e5e <fun7>:
 8048e5e:	53                   	push   %ebx
 8048e5f:	83 ec 08             	sub    $0x8,%esp
 8048e62:	8b 54 24 10          	mov    0x10(%esp),%edx
 8048e66:	8b 4c 24 14          	mov    0x14(%esp),%ecx
 8048e6a:	85 d2                	test   %edx,%edx
 8048e6c:	74 37                	je     8048ea5 <fun7+0x47>
 8048e6e:	8b 1a                	mov    (%edx),%ebx
 8048e70:	39 cb                	cmp    %ecx,%ebx
 8048e72:	7e 13                	jle    8048e87 <fun7+0x29>
 8048e74:	83 ec 08             	sub    $0x8,%esp
 8048e77:	51                   	push   %ecx
 8048e78:	ff 72 04             	pushl  0x4(%edx)
 8048e7b:	e8 de ff ff ff       	call   8048e5e <fun7>
 8048e80:	83 c4 10             	add    $0x10,%esp
 8048e83:	01 c0                	add    %eax,%eax
 8048e85:	eb 23                	jmp    8048eaa <fun7+0x4c>
 8048e87:	b8 00 00 00 00       	mov    $0x0,%eax
 8048e8c:	39 cb                	cmp    %ecx,%ebx
 8048e8e:	74 1a                	je     8048eaa <fun7+0x4c>
 8048e90:	83 ec 08             	sub    $0x8,%esp
 8048e93:	51                   	push   %ecx
 8048e94:	ff 72 08             	pushl  0x8(%edx)
 8048e97:	e8 c2 ff ff ff       	call   8048e5e <fun7>
 8048e9c:	83 c4 10             	add    $0x10,%esp
 8048e9f:	8d 44 00 01          	lea    0x1(%eax,%eax,1),%eax
 8048ea3:	eb 05                	jmp    8048eaa <fun7+0x4c>
 8048ea5:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
 8048eaa:	83 c4 08             	add    $0x8,%esp
 8048ead:	5b                   	pop    %ebx
 8048eae:	c3                   	ret    

08048eaf <secret_phase>:
 8048eaf:	53                   	push   %ebx
 8048eb0:	83 ec 08             	sub    $0x8,%esp
 8048eb3:	e8 da 08 00 00       	call   8049792 <read_line>
 8048eb8:	83 ec 04             	sub    $0x4,%esp
 8048ebb:	6a 0a                	push   $0xa
 8048ebd:	6a 00                	push   $0x0
 8048ebf:	50                   	push   %eax
 8048ec0:	e8 8b fa ff ff       	call   8048950 <strtol@plt>
 8048ec5:	89 c3                	mov    %eax,%ebx
 8048ec7:	8d 40 ff             	lea    -0x1(%eax),%eax
 8048eca:	83 c4 10             	add    $0x10,%esp
 8048ecd:	3d e8 03 00 00       	cmp    $0x3e8,%eax
 8048ed2:	76 05                	jbe    8048ed9 <secret_phase+0x2a>
 8048ed4:	e8 41 08 00 00       	call   804971a <explode_bomb>
 8048ed9:	83 ec 08             	sub    $0x8,%esp
 8048edc:	53                   	push   %ebx
 8048edd:	68 00 b2 04 08       	push   $0x804b200
 8048ee2:	e8 77 ff ff ff       	call   8048e5e <fun7>
 8048ee7:	83 c4 10             	add    $0x10,%esp
 8048eea:	83 f8 06             	cmp    $0x6,%eax
 8048eed:	74 05                	je     8048ef4 <secret_phase+0x45>
 8048eef:	e8 26 08 00 00       	call   804971a <explode_bomb>
 8048ef4:	83 ec 0c             	sub    $0xc,%esp
 8048ef7:	68 f0 9a 04 08       	push   $0x8049af0
 8048efc:	e8 5f f9 ff ff       	call   8048860 <puts@plt>
 8048f01:	e8 53 09 00 00       	call   8049859 <phase_defused>
 8048f06:	83 c4 18             	add    $0x18,%esp
 8048f09:	5b                   	pop    %ebx
 8048f0a:	c3                   	ret    

08048f0b <sig_handler>:
 8048f0b:	83 ec 18             	sub    $0x18,%esp
 8048f0e:	68 c0 9b 04 08       	push   $0x8049bc0
 8048f13:	e8 48 f9 ff ff       	call   8048860 <puts@plt>
 8048f18:	c7 04 24 03 00 00 00 	movl   $0x3,(%esp)
 8048f1f:	e8 cc f8 ff ff       	call   80487f0 <sleep@plt>
 8048f24:	c7 04 24 ec 9c 04 08 	movl   $0x8049cec,(%esp)
 8048f2b:	e8 50 f8 ff ff       	call   8048780 <printf@plt>
 8048f30:	83 c4 04             	add    $0x4,%esp
 8048f33:	ff 35 60 b7 04 08    	pushl  0x804b760
 8048f39:	e8 52 f8 ff ff       	call   8048790 <fflush@plt>
 8048f3e:	c7 04 24 01 00 00 00 	movl   $0x1,(%esp)
 8048f45:	e8 a6 f8 ff ff       	call   80487f0 <sleep@plt>
 8048f4a:	c7 04 24 f4 9c 04 08 	movl   $0x8049cf4,(%esp)
 8048f51:	e8 0a f9 ff ff       	call   8048860 <puts@plt>
 8048f56:	c7 04 24 10 00 00 00 	movl   $0x10,(%esp)
 8048f5d:	e8 2e f9 ff ff       	call   8048890 <exit@plt>

08048f62 <invalid_phase>:
 8048f62:	83 ec 14             	sub    $0x14,%esp
 8048f65:	ff 74 24 18          	pushl  0x18(%esp)
 8048f69:	68 fc 9c 04 08       	push   $0x8049cfc
 8048f6e:	e8 0d f8 ff ff       	call   8048780 <printf@plt>
 8048f73:	c7 04 24 08 00 00 00 	movl   $0x8,(%esp)
 8048f7a:	e8 11 f9 ff ff       	call   8048890 <exit@plt>

08048f7f <string_length>:
 8048f7f:	8b 54 24 04          	mov    0x4(%esp),%edx
 8048f83:	80 3a 00             	cmpb   $0x0,(%edx)
 8048f86:	74 10                	je     8048f98 <string_length+0x19>
 8048f88:	b8 00 00 00 00       	mov    $0x0,%eax
 8048f8d:	83 c0 01             	add    $0x1,%eax
 8048f90:	80 3c 02 00          	cmpb   $0x0,(%edx,%eax,1)
 8048f94:	75 f7                	jne    8048f8d <string_length+0xe>
 8048f96:	f3 c3                	repz ret 
 8048f98:	b8 00 00 00 00       	mov    $0x0,%eax
 8048f9d:	c3                   	ret    

08048f9e <strings_not_equal>:
 8048f9e:	57                   	push   %edi
 8048f9f:	56                   	push   %esi
 8048fa0:	53                   	push   %ebx
 8048fa1:	8b 5c 24 10          	mov    0x10(%esp),%ebx
 8048fa5:	8b 74 24 14          	mov    0x14(%esp),%esi
 8048fa9:	53                   	push   %ebx
 8048faa:	e8 d0 ff ff ff       	call   8048f7f <string_length>
 8048faf:	89 c7                	mov    %eax,%edi
 8048fb1:	89 34 24             	mov    %esi,(%esp)
 8048fb4:	e8 c6 ff ff ff       	call   8048f7f <string_length>
 8048fb9:	83 c4 04             	add    $0x4,%esp
 8048fbc:	ba 01 00 00 00       	mov    $0x1,%edx
 8048fc1:	39 c7                	cmp    %eax,%edi
 8048fc3:	75 38                	jne    8048ffd <strings_not_equal+0x5f>
 8048fc5:	0f b6 03             	movzbl (%ebx),%eax
 8048fc8:	84 c0                	test   %al,%al
 8048fca:	74 1e                	je     8048fea <strings_not_equal+0x4c>
 8048fcc:	3a 06                	cmp    (%esi),%al
 8048fce:	74 06                	je     8048fd6 <strings_not_equal+0x38>
 8048fd0:	eb 1f                	jmp    8048ff1 <strings_not_equal+0x53>
 8048fd2:	3a 06                	cmp    (%esi),%al
 8048fd4:	75 22                	jne    8048ff8 <strings_not_equal+0x5a>
 8048fd6:	83 c3 01             	add    $0x1,%ebx
 8048fd9:	83 c6 01             	add    $0x1,%esi
 8048fdc:	0f b6 03             	movzbl (%ebx),%eax
 8048fdf:	84 c0                	test   %al,%al
 8048fe1:	75 ef                	jne    8048fd2 <strings_not_equal+0x34>
 8048fe3:	ba 00 00 00 00       	mov    $0x0,%edx
 8048fe8:	eb 13                	jmp    8048ffd <strings_not_equal+0x5f>
 8048fea:	ba 00 00 00 00       	mov    $0x0,%edx
 8048fef:	eb 0c                	jmp    8048ffd <strings_not_equal+0x5f>
 8048ff1:	ba 01 00 00 00       	mov    $0x1,%edx
 8048ff6:	eb 05                	jmp    8048ffd <strings_not_equal+0x5f>
 8048ff8:	ba 01 00 00 00       	mov    $0x1,%edx
 8048ffd:	89 d0                	mov    %edx,%eax
 8048fff:	5b                   	pop    %ebx
 8049000:	5e                   	pop    %esi
 8049001:	5f                   	pop    %edi
 8049002:	c3                   	ret    

08049003 <open_clientfd>:
 8049003:	56                   	push   %esi
 8049004:	53                   	push   %ebx
 8049005:	83 ec 18             	sub    $0x18,%esp
 8049008:	6a 00                	push   $0x0
 804900a:	6a 01                	push   $0x1
 804900c:	6a 02                	push   $0x2
 804900e:	e8 1d f9 ff ff       	call   8048930 <socket@plt>
 8049013:	89 c3                	mov    %eax,%ebx
 8049015:	83 c4 10             	add    $0x10,%esp
 8049018:	85 c0                	test   %eax,%eax
 804901a:	79 19                	jns    8049035 <open_clientfd+0x32>
 804901c:	83 ec 0c             	sub    $0xc,%esp
 804901f:	68 0d 9d 04 08       	push   $0x8049d0d
 8049024:	e8 37 f8 ff ff       	call   8048860 <puts@plt>
 8049029:	c7 04 24 08 00 00 00 	movl   $0x8,(%esp)
 8049030:	e8 5b f8 ff ff       	call   8048890 <exit@plt>
 8049035:	83 ec 0c             	sub    $0xc,%esp
 8049038:	ff 74 24 2c          	pushl  0x2c(%esp)
 804903c:	e8 ff f8 ff ff       	call   8048940 <gethostbyname@plt>
 8049041:	83 c4 10             	add    $0x10,%esp
 8049044:	85 c0                	test   %eax,%eax
 8049046:	75 19                	jne    8049061 <open_clientfd+0x5e>
 8049048:	83 ec 0c             	sub    $0xc,%esp
 804904b:	68 1b 9d 04 08       	push   $0x8049d1b
 8049050:	e8 0b f8 ff ff       	call   8048860 <puts@plt>
 8049055:	c7 04 24 08 00 00 00 	movl   $0x8,(%esp)
 804905c:	e8 2f f8 ff ff       	call   8048890 <exit@plt>
 8049061:	89 e6                	mov    %esp,%esi
 8049063:	c7 04 24 00 00 00 00 	movl   $0x0,(%esp)
 804906a:	c7 44 24 04 00 00 00 	movl   $0x0,0x4(%esp)
 8049071:	00 
 8049072:	c7 44 24 08 00 00 00 	movl   $0x0,0x8(%esp)
 8049079:	00 
 804907a:	c7 44 24 0c 00 00 00 	movl   $0x0,0xc(%esp)
 8049081:	00 
 8049082:	66 c7 04 24 02 00    	movw   $0x2,(%esp)
 8049088:	83 ec 04             	sub    $0x4,%esp
 804908b:	ff 70 0c             	pushl  0xc(%eax)
 804908e:	8d 54 24 0c          	lea    0xc(%esp),%edx
 8049092:	52                   	push   %edx
 8049093:	8b 40 10             	mov    0x10(%eax),%eax
 8049096:	ff 30                	pushl  (%eax)
 8049098:	e8 83 f7 ff ff       	call   8048820 <bcopy@plt>
 804909d:	0f b7 44 24 34       	movzwl 0x34(%esp),%eax
 80490a2:	66 c1 c8 08          	ror    $0x8,%ax
 80490a6:	66 89 44 24 12       	mov    %ax,0x12(%esp)
 80490ab:	83 c4 0c             	add    $0xc,%esp
 80490ae:	6a 10                	push   $0x10
 80490b0:	56                   	push   %esi
 80490b1:	53                   	push   %ebx
 80490b2:	e8 a9 f8 ff ff       	call   8048960 <connect@plt>
 80490b7:	83 c4 10             	add    $0x10,%esp
 80490ba:	85 c0                	test   %eax,%eax
 80490bc:	79 19                	jns    80490d7 <open_clientfd+0xd4>
 80490be:	83 ec 0c             	sub    $0xc,%esp
 80490c1:	68 29 9d 04 08       	push   $0x8049d29
 80490c6:	e8 95 f7 ff ff       	call   8048860 <puts@plt>
 80490cb:	c7 04 24 08 00 00 00 	movl   $0x8,(%esp)
 80490d2:	e8 b9 f7 ff ff       	call   8048890 <exit@plt>
 80490d7:	89 d8                	mov    %ebx,%eax
 80490d9:	83 c4 14             	add    $0x14,%esp
 80490dc:	5b                   	pop    %ebx
 80490dd:	5e                   	pop    %esi
 80490de:	c3                   	ret    

080490df <initialize_bomb>:
 80490df:	83 ec 14             	sub    $0x14,%esp
 80490e2:	68 0b 8f 04 08       	push   $0x8048f0b
 80490e7:	6a 02                	push   $0x2
 80490e9:	e8 f2 f6 ff ff       	call   80487e0 <signal@plt>
 80490ee:	83 c4 08             	add    $0x8,%esp
 80490f1:	6a 50                	push   $0x50
 80490f3:	68 37 9d 04 08       	push   $0x8049d37
 80490f8:	e8 06 ff ff ff       	call   8049003 <open_clientfd>
 80490fd:	89 04 24             	mov    %eax,(%esp)
 8049100:	e8 6b f8 ff ff       	call   8048970 <close@plt>
 8049105:	83 c4 1c             	add    $0x1c,%esp
 8049108:	c3                   	ret    

08049109 <blank_line>:
 8049109:	56                   	push   %esi
 804910a:	53                   	push   %ebx
 804910b:	83 ec 04             	sub    $0x4,%esp
 804910e:	8b 74 24 10          	mov    0x10(%esp),%esi
 8049112:	eb 14                	jmp    8049128 <blank_line+0x1f>
 8049114:	e8 67 f8 ff ff       	call   8048980 <__ctype_b_loc@plt>
 8049119:	83 c6 01             	add    $0x1,%esi
 804911c:	0f be db             	movsbl %bl,%ebx
 804911f:	8b 00                	mov    (%eax),%eax
 8049121:	f6 44 58 01 20       	testb  $0x20,0x1(%eax,%ebx,2)
 8049126:	74 0e                	je     8049136 <blank_line+0x2d>
 8049128:	0f b6 1e             	movzbl (%esi),%ebx
 804912b:	84 db                	test   %bl,%bl
 804912d:	75 e5                	jne    8049114 <blank_line+0xb>
 804912f:	b8 01 00 00 00       	mov    $0x1,%eax
 8049134:	eb 05                	jmp    804913b <blank_line+0x32>
 8049136:	b8 00 00 00 00       	mov    $0x0,%eax
 804913b:	83 c4 04             	add    $0x4,%esp
 804913e:	5b                   	pop    %ebx
 804913f:	5e                   	pop    %esi
 8049140:	c3                   	ret    

08049141 <skip>:
 8049141:	53                   	push   %ebx
 8049142:	83 ec 08             	sub    $0x8,%esp
 8049145:	83 ec 04             	sub    $0x4,%esp
 8049148:	ff 35 6c b7 04 08    	pushl  0x804b76c
 804914e:	6a 50                	push   $0x50
 8049150:	a1 68 b7 04 08       	mov    0x804b768,%eax
 8049155:	8d 04 80             	lea    (%eax,%eax,4),%eax
 8049158:	c1 e0 04             	shl    $0x4,%eax
 804915b:	05 80 b7 04 08       	add    $0x804b780,%eax
 8049160:	50                   	push   %eax
 8049161:	e8 5a f6 ff ff       	call   80487c0 <fgets@plt>
 8049166:	89 c3                	mov    %eax,%ebx
 8049168:	83 c4 10             	add    $0x10,%esp
 804916b:	85 c0                	test   %eax,%eax
 804916d:	74 10                	je     804917f <skip+0x3e>
 804916f:	83 ec 0c             	sub    $0xc,%esp
 8049172:	50                   	push   %eax
 8049173:	e8 91 ff ff ff       	call   8049109 <blank_line>
 8049178:	83 c4 10             	add    $0x10,%esp
 804917b:	85 c0                	test   %eax,%eax
 804917d:	75 c6                	jne    8049145 <skip+0x4>
 804917f:	89 d8                	mov    %ebx,%eax
 8049181:	83 c4 08             	add    $0x8,%esp
 8049184:	5b                   	pop    %ebx
 8049185:	c3                   	ret    

08049186 <writen>:
 8049186:	55                   	push   %ebp
 8049187:	57                   	push   %edi
 8049188:	56                   	push   %esi
 8049189:	53                   	push   %ebx
 804918a:	83 ec 0c             	sub    $0xc,%esp
 804918d:	8b 7c 24 20          	mov    0x20(%esp),%edi
 8049191:	8b 74 24 24          	mov    0x24(%esp),%esi
 8049195:	8b 6c 24 28          	mov    0x28(%esp),%ebp
 8049199:	85 ed                	test   %ebp,%ebp
 804919b:	74 29                	je     80491c6 <writen+0x40>
 804919d:	89 eb                	mov    %ebp,%ebx
 804919f:	83 ec 04             	sub    $0x4,%esp
 80491a2:	53                   	push   %ebx
 80491a3:	56                   	push   %esi
 80491a4:	57                   	push   %edi
 80491a5:	e8 16 f7 ff ff       	call   80488c0 <write@plt>
 80491aa:	83 c4 10             	add    $0x10,%esp
 80491ad:	85 c0                	test   %eax,%eax
 80491af:	7f 0f                	jg     80491c0 <writen+0x3a>
 80491b1:	e8 3a f7 ff ff       	call   80488f0 <__errno_location@plt>
 80491b6:	83 38 04             	cmpl   $0x4,(%eax)
 80491b9:	75 0f                	jne    80491ca <writen+0x44>
 80491bb:	b8 00 00 00 00       	mov    $0x0,%eax
 80491c0:	01 c6                	add    %eax,%esi
 80491c2:	29 c3                	sub    %eax,%ebx
 80491c4:	75 d9                	jne    804919f <writen+0x19>
 80491c6:	89 e8                	mov    %ebp,%eax
 80491c8:	eb 05                	jmp    80491cf <writen+0x49>
 80491ca:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
 80491cf:	83 c4 0c             	add    $0xc,%esp
 80491d2:	5b                   	pop    %ebx
 80491d3:	5e                   	pop    %esi
 80491d4:	5f                   	pop    %edi
 80491d5:	5d                   	pop    %ebp
 80491d6:	c3                   	ret    

080491d7 <send_msg>:
 80491d7:	55                   	push   %ebp
 80491d8:	57                   	push   %edi
 80491d9:	56                   	push   %esi
 80491da:	53                   	push   %ebx
 80491db:	81 ec 80 24 00 00    	sub    $0x2480,%esp
 80491e1:	6a 00                	push   $0x0
 80491e3:	6a 01                	push   $0x1
 80491e5:	6a 02                	push   $0x2
 80491e7:	e8 44 f7 ff ff       	call   8048930 <socket@plt>
 80491ec:	89 44 24 1c          	mov    %eax,0x1c(%esp)
 80491f0:	83 c4 10             	add    $0x10,%esp
 80491f3:	85 c0                	test   %eax,%eax
 80491f5:	79 30                	jns    8049227 <send_msg+0x50>
 80491f7:	83 ec 04             	sub    $0x4,%esp
 80491fa:	68 57 9d 04 08       	push   $0x8049d57
 80491ff:	68 a1 99 04 08       	push   $0x80499a1
 8049204:	ff 35 60 b7 04 08    	pushl  0x804b760
 804920a:	e8 a1 f6 ff ff       	call   80488b0 <fprintf@plt>
 804920f:	83 c4 04             	add    $0x4,%esp
 8049212:	ff 74 24 18          	pushl  0x18(%esp)
 8049216:	e8 55 f7 ff ff       	call   8048970 <close@plt>
 804921b:	c7 04 24 01 00 00 00 	movl   $0x1,(%esp)
 8049222:	e8 69 f6 ff ff       	call   8048890 <exit@plt>
 8049227:	c7 84 24 64 24 00 00 	movl   $0x0,0x2464(%esp)
 804922e:	00 00 00 00 
 8049232:	c7 84 24 68 24 00 00 	movl   $0x0,0x2468(%esp)
 8049239:	00 00 00 00 
 804923d:	c7 84 24 6c 24 00 00 	movl   $0x0,0x246c(%esp)
 8049244:	00 00 00 00 
 8049248:	66 c7 84 24 60 24 00 	movw   $0x2,0x2460(%esp)
 804924f:	00 02 00 
 8049252:	66 c7 84 24 62 24 00 	movw   $0x7ac8,0x2462(%esp)
 8049259:	00 c8 7a 
 804925c:	83 ec 04             	sub    $0x4,%esp
 804925f:	8d 84 24 68 24 00 00 	lea    0x2468(%esp),%eax
 8049266:	50                   	push   %eax
 8049267:	68 37 9d 04 08       	push   $0x8049d37
 804926c:	6a 02                	push   $0x2
 804926e:	e8 3d f5 ff ff       	call   80487b0 <inet_pton@plt>
 8049273:	83 c4 10             	add    $0x10,%esp
 8049276:	85 c0                	test   %eax,%eax
 8049278:	79 3b                	jns    80492b5 <send_msg+0xde>
 804927a:	83 ec 04             	sub    $0x4,%esp
 804927d:	68 cb 9d 04 08       	push   $0x8049dcb
 8049282:	68 a1 99 04 08       	push   $0x80499a1
 8049287:	ff 35 60 b7 04 08    	pushl  0x804b760
 804928d:	e8 1e f6 ff ff       	call   80488b0 <fprintf@plt>
 8049292:	83 c4 10             	add    $0x10,%esp
 8049295:	83 7c 24 0c 00       	cmpl   $0x0,0xc(%esp)
 804929a:	74 0f                	je     80492ab <send_msg+0xd4>
 804929c:	83 ec 0c             	sub    $0xc,%esp
 804929f:	ff 74 24 18          	pushl  0x18(%esp)
 80492a3:	e8 c8 f6 ff ff       	call   8048970 <close@plt>
 80492a8:	83 c4 10             	add    $0x10,%esp
 80492ab:	83 ec 0c             	sub    $0xc,%esp
 80492ae:	6a 01                	push   $0x1
 80492b0:	e8 db f5 ff ff       	call   8048890 <exit@plt>
 80492b5:	83 ec 04             	sub    $0x4,%esp
 80492b8:	6a 10                	push   $0x10
 80492ba:	8d 84 24 68 24 00 00 	lea    0x2468(%esp),%eax
 80492c1:	50                   	push   %eax
 80492c2:	ff 74 24 18          	pushl  0x18(%esp)
 80492c6:	e8 95 f6 ff ff       	call   8048960 <connect@plt>
 80492cb:	83 c4 10             	add    $0x10,%esp
 80492ce:	85 c0                	test   %eax,%eax
 80492d0:	79 3b                	jns    804930d <send_msg+0x136>
 80492d2:	83 ec 04             	sub    $0x4,%esp
 80492d5:	68 64 9d 04 08       	push   $0x8049d64
 80492da:	68 a1 99 04 08       	push   $0x80499a1
 80492df:	ff 35 60 b7 04 08    	pushl  0x804b760
 80492e5:	e8 c6 f5 ff ff       	call   80488b0 <fprintf@plt>
 80492ea:	83 c4 10             	add    $0x10,%esp
 80492ed:	83 7c 24 0c 00       	cmpl   $0x0,0xc(%esp)
 80492f2:	74 0f                	je     8049303 <send_msg+0x12c>
 80492f4:	83 ec 0c             	sub    $0xc,%esp
 80492f7:	ff 74 24 18          	pushl  0x18(%esp)
 80492fb:	e8 70 f6 ff ff       	call   8048970 <close@plt>
 8049300:	83 c4 10             	add    $0x10,%esp
 8049303:	83 ec 0c             	sub    $0xc,%esp
 8049306:	6a 01                	push   $0x1
 8049308:	e8 83 f5 ff ff       	call   8048890 <exit@plt>
 804930d:	8d 74 24 60          	lea    0x60(%esp),%esi
 8049311:	c7 44 24 60 53 75 62 	movl   $0x6a627553,0x60(%esp)
 8049318:	6a 
 8049319:	c7 44 24 64 65 63 74 	movl   $0x3a746365,0x64(%esp)
 8049320:	3a 
 8049321:	c7 44 24 68 20 42 6f 	movl   $0x6d6f4220,0x68(%esp)
 8049328:	6d 
 8049329:	c7 44 24 6c 62 20 6e 	movl   $0x6f6e2062,0x6c(%esp)
 8049330:	6f 
 8049331:	c7 44 24 70 74 69 66 	movl   $0x69666974,0x70(%esp)
 8049338:	69 
 8049339:	c7 44 24 74 63 61 74 	movl   $0x69746163,0x74(%esp)
 8049340:	69 
 8049341:	c7 44 24 78 6f 6e 0a 	movl   $0xa6e6f,0x78(%esp)
 8049348:	00 
 8049349:	83 ec 08             	sub    $0x8,%esp
 804934c:	56                   	push   %esi
 804934d:	8d 9c 24 6c 04 00 00 	lea    0x46c(%esp),%ebx
 8049354:	53                   	push   %ebx
 8049355:	e8 d6 f4 ff ff       	call   8048830 <strcat@plt>
 804935a:	66 c7 44 24 70 0a 00 	movw   $0xa,0x70(%esp)
 8049361:	83 c4 08             	add    $0x8,%esp
 8049364:	56                   	push   %esi
 8049365:	53                   	push   %ebx
 8049366:	e8 c5 f4 ff ff       	call   8048830 <strcat@plt>
 804936b:	c7 04 24 00 00 00 00 	movl   $0x0,(%esp)
 8049372:	e8 f9 f3 ff ff       	call   8048770 <cuserid@plt>
 8049377:	83 c4 10             	add    $0x10,%esp
 804937a:	85 c0                	test   %eax,%eax
 804937c:	75 16                	jne    8049394 <send_msg+0x1bd>
 804937e:	c7 44 24 10 6e 6f 62 	movl   $0x6f626f6e,0x10(%esp)
 8049385:	6f 
 8049386:	66 c7 44 24 14 64 79 	movw   $0x7964,0x14(%esp)
 804938d:	c6 44 24 16 00       	movb   $0x0,0x16(%esp)
 8049392:	eb 11                	jmp    80493a5 <send_msg+0x1ce>
 8049394:	83 ec 08             	sub    $0x8,%esp
 8049397:	50                   	push   %eax
 8049398:	8d 44 24 1c          	lea    0x1c(%esp),%eax
 804939c:	50                   	push   %eax
 804939d:	e8 9e f4 ff ff       	call   8048840 <strcpy@plt>
 80493a2:	83 c4 10             	add    $0x10,%esp
 80493a5:	8b 15 68 b7 04 08    	mov    0x804b768,%edx
 80493ab:	b8 46 9d 04 08       	mov    $0x8049d46,%eax
 80493b0:	83 bc 24 90 24 00 00 	cmpl   $0x0,0x2490(%esp)
 80493b7:	00 
 80493b8:	75 05                	jne    80493bf <send_msg+0x1e8>
 80493ba:	b8 4e 9d 04 08       	mov    $0x8049d4e,%eax
 80493bf:	83 ec 04             	sub    $0x4,%esp
 80493c2:	52                   	push   %edx
 80493c3:	50                   	push   %eax
 80493c4:	8d 44 24 1c          	lea    0x1c(%esp),%eax
 80493c8:	50                   	push   %eax
 80493c9:	ff 35 00 b7 04 08    	pushl  0x804b700
 80493cf:	68 00 b3 04 08       	push   $0x804b300
 80493d4:	68 72 9d 04 08       	push   $0x8049d72
 80493d9:	8d 5c 24 7c          	lea    0x7c(%esp),%ebx
 80493dd:	53                   	push   %ebx
 80493de:	e8 2d f5 ff ff       	call   8048910 <sprintf@plt>
 80493e3:	83 c4 18             	add    $0x18,%esp
 80493e6:	53                   	push   %ebx
 80493e7:	8d 84 24 6c 04 00 00 	lea    0x46c(%esp),%eax
 80493ee:	50                   	push   %eax
 80493ef:	e8 3c f4 ff ff       	call   8048830 <strcat@plt>
 80493f4:	83 c4 10             	add    $0x10,%esp
 80493f7:	83 3d 68 b7 04 08 00 	cmpl   $0x0,0x804b768
 80493fe:	7e 50                	jle    8049450 <send_msg+0x279>
 8049400:	be 80 b7 04 08       	mov    $0x804b780,%esi
 8049405:	bb 00 00 00 00       	mov    $0x0,%ebx
 804940a:	8d 6c 24 10          	lea    0x10(%esp),%ebp
 804940e:	8d 7c 24 60          	lea    0x60(%esp),%edi
 8049412:	83 c3 01             	add    $0x1,%ebx
 8049415:	83 ec 04             	sub    $0x4,%esp
 8049418:	56                   	push   %esi
 8049419:	53                   	push   %ebx
 804941a:	55                   	push   %ebp
 804941b:	ff 35 00 b7 04 08    	pushl  0x804b700
 8049421:	68 00 b3 04 08       	push   $0x804b300
 8049426:	68 8e 9d 04 08       	push   $0x8049d8e
 804942b:	57                   	push   %edi
 804942c:	e8 df f4 ff ff       	call   8048910 <sprintf@plt>
 8049431:	83 c4 18             	add    $0x18,%esp
 8049434:	57                   	push   %edi
 8049435:	8d 84 24 6c 04 00 00 	lea    0x46c(%esp),%eax
 804943c:	50                   	push   %eax
 804943d:	e8 ee f3 ff ff       	call   8048830 <strcat@plt>
 8049442:	83 c6 50             	add    $0x50,%esi
 8049445:	83 c4 10             	add    $0x10,%esp
 8049448:	39 1d 68 b7 04 08    	cmp    %ebx,0x804b768
 804944e:	7f c2                	jg     8049412 <send_msg+0x23b>
 8049450:	8d 9c 24 60 04 00 00 	lea    0x460(%esp),%ebx
 8049457:	be ff ff ff ff       	mov    $0xffffffff,%esi
 804945c:	89 df                	mov    %ebx,%edi
 804945e:	bd 00 00 00 00       	mov    $0x0,%ebp
 8049463:	89 f1                	mov    %esi,%ecx
 8049465:	89 e8                	mov    %ebp,%eax
 8049467:	f2 ae                	repnz scas %es:(%edi),%al
 8049469:	f7 d1                	not    %ecx
 804946b:	83 e9 01             	sub    $0x1,%ecx
 804946e:	83 ec 04             	sub    $0x4,%esp
 8049471:	51                   	push   %ecx
 8049472:	53                   	push   %ebx
 8049473:	ff 74 24 18          	pushl  0x18(%esp)
 8049477:	e8 0a fd ff ff       	call   8049186 <writen>
 804947c:	89 c2                	mov    %eax,%edx
 804947e:	89 df                	mov    %ebx,%edi
 8049480:	89 f1                	mov    %esi,%ecx
 8049482:	89 e8                	mov    %ebp,%eax
 8049484:	f2 ae                	repnz scas %es:(%edi),%al
 8049486:	f7 d1                	not    %ecx
 8049488:	83 e9 01             	sub    $0x1,%ecx
 804948b:	83 c4 10             	add    $0x10,%esp
 804948e:	39 ca                	cmp    %ecx,%edx
 8049490:	73 3b                	jae    80494cd <send_msg+0x2f6>
 8049492:	83 ec 04             	sub    $0x4,%esp
 8049495:	68 aa 9d 04 08       	push   $0x8049daa
 804949a:	68 a1 99 04 08       	push   $0x80499a1
 804949f:	ff 35 60 b7 04 08    	pushl  0x804b760
 80494a5:	e8 06 f4 ff ff       	call   80488b0 <fprintf@plt>
 80494aa:	83 c4 10             	add    $0x10,%esp
 80494ad:	83 7c 24 0c 00       	cmpl   $0x0,0xc(%esp)
 80494b2:	74 0f                	je     80494c3 <send_msg+0x2ec>
 80494b4:	83 ec 0c             	sub    $0xc,%esp
 80494b7:	ff 74 24 18          	pushl  0x18(%esp)
 80494bb:	e8 b0 f4 ff ff       	call   8048970 <close@plt>
 80494c0:	83 c4 10             	add    $0x10,%esp
 80494c3:	83 ec 0c             	sub    $0xc,%esp
 80494c6:	6a 01                	push   $0x1
 80494c8:	e8 c3 f3 ff ff       	call   8048890 <exit@plt>
 80494cd:	83 ec 0c             	sub    $0xc,%esp
 80494d0:	ff 74 24 18          	pushl  0x18(%esp)
 80494d4:	e8 97 f4 ff ff       	call   8048970 <close@plt>
 80494d9:	81 c4 8c 24 00 00    	add    $0x248c,%esp
 80494df:	5b                   	pop    %ebx
 80494e0:	5e                   	pop    %esi
 80494e1:	5f                   	pop    %edi
 80494e2:	5d                   	pop    %ebp
 80494e3:	c3                   	ret    

080494e4 <send_msg_2>:
 80494e4:	55                   	push   %ebp
 80494e5:	57                   	push   %edi
 80494e6:	56                   	push   %esi
 80494e7:	53                   	push   %ebx
 80494e8:	83 ec 78             	sub    $0x78,%esp
 80494eb:	6a 00                	push   $0x0
 80494ed:	e8 ae f2 ff ff       	call   80487a0 <dup@plt>
 80494f2:	89 44 24 1c          	mov    %eax,0x1c(%esp)
 80494f6:	83 c4 10             	add    $0x10,%esp
 80494f9:	83 f8 ff             	cmp    $0xffffffff,%eax
 80494fc:	75 19                	jne    8049517 <send_msg_2+0x33>
 80494fe:	83 ec 0c             	sub    $0xc,%esp
 8049501:	68 bd 9d 04 08       	push   $0x8049dbd
 8049506:	e8 55 f3 ff ff       	call   8048860 <puts@plt>
 804950b:	c7 04 24 08 00 00 00 	movl   $0x8,(%esp)
 8049512:	e8 79 f3 ff ff       	call   8048890 <exit@plt>
 8049517:	83 ec 0c             	sub    $0xc,%esp
 804951a:	6a 00                	push   $0x0
 804951c:	e8 4f f4 ff ff       	call   8048970 <close@plt>
 8049521:	83 c4 10             	add    $0x10,%esp
 8049524:	83 f8 ff             	cmp    $0xffffffff,%eax
 8049527:	75 19                	jne    8049542 <send_msg_2+0x5e>
 8049529:	83 ec 0c             	sub    $0xc,%esp
 804952c:	68 d1 9d 04 08       	push   $0x8049dd1
 8049531:	e8 2a f3 ff ff       	call   8048860 <puts@plt>
 8049536:	c7 04 24 08 00 00 00 	movl   $0x8,(%esp)
 804953d:	e8 4e f3 ff ff       	call   8048890 <exit@plt>
 8049542:	e8 d9 f3 ff ff       	call   8048920 <tmpfile@plt>
 8049547:	89 c7                	mov    %eax,%edi
 8049549:	85 c0                	test   %eax,%eax
 804954b:	75 19                	jne    8049566 <send_msg_2+0x82>
 804954d:	83 ec 0c             	sub    $0xc,%esp
 8049550:	68 e4 9d 04 08       	push   $0x8049de4
 8049555:	e8 06 f3 ff ff       	call   8048860 <puts@plt>
 804955a:	c7 04 24 08 00 00 00 	movl   $0x8,(%esp)
 8049561:	e8 2a f3 ff ff       	call   8048890 <exit@plt>
 8049566:	50                   	push   %eax
 8049567:	6a 1b                	push   $0x1b
 8049569:	6a 01                	push   $0x1
 804956b:	68 f9 9d 04 08       	push   $0x8049df9
 8049570:	e8 9b f2 ff ff       	call   8048810 <fwrite@plt>
 8049575:	83 c4 08             	add    $0x8,%esp
 8049578:	57                   	push   %edi
 8049579:	6a 0a                	push   $0xa
 804957b:	e8 80 f3 ff ff       	call   8048900 <fputc@plt>
 8049580:	c7 04 24 00 00 00 00 	movl   $0x0,(%esp)
 8049587:	e8 e4 f1 ff ff       	call   8048770 <cuserid@plt>
 804958c:	83 c4 10             	add    $0x10,%esp
 804958f:	85 c0                	test   %eax,%eax
 8049591:	75 16                	jne    80495a9 <send_msg_2+0xc5>
 8049593:	c7 44 24 10 6e 6f 62 	movl   $0x6f626f6e,0x10(%esp)
 804959a:	6f 
 804959b:	66 c7 44 24 14 64 79 	movw   $0x7964,0x14(%esp)
 80495a2:	c6 44 24 16 00       	movb   $0x0,0x16(%esp)
 80495a7:	eb 11                	jmp    80495ba <send_msg_2+0xd6>
 80495a9:	83 ec 08             	sub    $0x8,%esp
 80495ac:	50                   	push   %eax
 80495ad:	8d 44 24 1c          	lea    0x1c(%esp),%eax
 80495b1:	50                   	push   %eax
 80495b2:	e8 89 f2 ff ff       	call   8048840 <strcpy@plt>
 80495b7:	83 c4 10             	add    $0x10,%esp
 80495ba:	8b 15 68 b7 04 08    	mov    0x804b768,%edx
 80495c0:	b8 46 9d 04 08       	mov    $0x8049d46,%eax
 80495c5:	83 bc 24 80 00 00 00 	cmpl   $0x0,0x80(%esp)
 80495cc:	00 
 80495cd:	75 05                	jne    80495d4 <send_msg_2+0xf0>
 80495cf:	b8 4e 9d 04 08       	mov    $0x8049d4e,%eax
 80495d4:	83 ec 04             	sub    $0x4,%esp
 80495d7:	52                   	push   %edx
 80495d8:	50                   	push   %eax
 80495d9:	8d 44 24 1c          	lea    0x1c(%esp),%eax
 80495dd:	50                   	push   %eax
 80495de:	ff 35 00 b7 04 08    	pushl  0x804b700
 80495e4:	68 00 b3 04 08       	push   $0x804b300
 80495e9:	68 72 9d 04 08       	push   $0x8049d72
 80495ee:	57                   	push   %edi
 80495ef:	e8 bc f2 ff ff       	call   80488b0 <fprintf@plt>
 80495f4:	83 c4 20             	add    $0x20,%esp
 80495f7:	83 3d 68 b7 04 08 00 	cmpl   $0x0,0x804b768
 80495fe:	7e 3b                	jle    804963b <send_msg_2+0x157>
 8049600:	be 80 b7 04 08       	mov    $0x804b780,%esi
 8049605:	bb 00 00 00 00       	mov    $0x0,%ebx
 804960a:	8d 6c 24 10          	lea    0x10(%esp),%ebp
 804960e:	83 c3 01             	add    $0x1,%ebx
 8049611:	83 ec 04             	sub    $0x4,%esp
 8049614:	56                   	push   %esi
 8049615:	53                   	push   %ebx
 8049616:	55                   	push   %ebp
 8049617:	ff 35 00 b7 04 08    	pushl  0x804b700
 804961d:	68 00 b3 04 08       	push   $0x804b300
 8049622:	68 8e 9d 04 08       	push   $0x8049d8e
 8049627:	57                   	push   %edi
 8049628:	e8 83 f2 ff ff       	call   80488b0 <fprintf@plt>
 804962d:	83 c6 50             	add    $0x50,%esi
 8049630:	83 c4 20             	add    $0x20,%esp
 8049633:	39 1d 68 b7 04 08    	cmp    %ebx,0x804b768
 8049639:	7f d3                	jg     804960e <send_msg_2+0x12a>
 804963b:	83 ec 0c             	sub    $0xc,%esp
 804963e:	57                   	push   %edi
 804963f:	e8 bc f1 ff ff       	call   8048800 <rewind@plt>
 8049644:	c7 04 24 15 9e 04 08 	movl   $0x8049e15,(%esp)
 804964b:	68 1f 9e 04 08       	push   $0x8049e1f
 8049650:	68 27 9e 04 08       	push   $0x8049e27
 8049655:	68 3e 9e 04 08       	push   $0x8049e3e
 804965a:	68 c0 bd 04 08       	push   $0x804bdc0
 804965f:	e8 ac f2 ff ff       	call   8048910 <sprintf@plt>
 8049664:	83 c4 14             	add    $0x14,%esp
 8049667:	68 c0 bd 04 08       	push   $0x804bdc0
 804966c:	e8 ff f1 ff ff       	call   8048870 <system@plt>
 8049671:	83 c4 10             	add    $0x10,%esp
 8049674:	85 c0                	test   %eax,%eax
 8049676:	74 19                	je     8049691 <send_msg_2+0x1ad>
 8049678:	83 ec 0c             	sub    $0xc,%esp
 804967b:	68 47 9e 04 08       	push   $0x8049e47
 8049680:	e8 db f1 ff ff       	call   8048860 <puts@plt>
 8049685:	c7 04 24 08 00 00 00 	movl   $0x8,(%esp)
 804968c:	e8 ff f1 ff ff       	call   8048890 <exit@plt>
 8049691:	83 ec 0c             	sub    $0xc,%esp
 8049694:	57                   	push   %edi
 8049695:	e8 36 f1 ff ff       	call   80487d0 <fclose@plt>
 804969a:	83 c4 10             	add    $0x10,%esp
 804969d:	85 c0                	test   %eax,%eax
 804969f:	74 19                	je     80496ba <send_msg_2+0x1d6>
 80496a1:	83 ec 0c             	sub    $0xc,%esp
 80496a4:	68 61 9e 04 08       	push   $0x8049e61
 80496a9:	e8 b2 f1 ff ff       	call   8048860 <puts@plt>
 80496ae:	c7 04 24 08 00 00 00 	movl   $0x8,(%esp)
 80496b5:	e8 d6 f1 ff ff       	call   8048890 <exit@plt>
 80496ba:	83 ec 0c             	sub    $0xc,%esp
 80496bd:	ff 74 24 18          	pushl  0x18(%esp)
 80496c1:	e8 da f0 ff ff       	call   80487a0 <dup@plt>
 80496c6:	83 c4 10             	add    $0x10,%esp
 80496c9:	85 c0                	test   %eax,%eax
 80496cb:	74 19                	je     80496e6 <send_msg_2+0x202>
 80496cd:	83 ec 0c             	sub    $0xc,%esp
 80496d0:	68 7a 9e 04 08       	push   $0x8049e7a
 80496d5:	e8 86 f1 ff ff       	call   8048860 <puts@plt>
 80496da:	c7 04 24 08 00 00 00 	movl   $0x8,(%esp)
 80496e1:	e8 aa f1 ff ff       	call   8048890 <exit@plt>
 80496e6:	83 ec 0c             	sub    $0xc,%esp
 80496e9:	ff 74 24 18          	pushl  0x18(%esp)
 80496ed:	e8 7e f2 ff ff       	call   8048970 <close@plt>
 80496f2:	83 c4 10             	add    $0x10,%esp
 80496f5:	85 c0                	test   %eax,%eax
 80496f7:	74 19                	je     8049712 <send_msg_2+0x22e>
 80496f9:	83 ec 0c             	sub    $0xc,%esp
 80496fc:	68 95 9e 04 08       	push   $0x8049e95
 8049701:	e8 5a f1 ff ff       	call   8048860 <puts@plt>
 8049706:	c7 04 24 08 00 00 00 	movl   $0x8,(%esp)
 804970d:	e8 7e f1 ff ff       	call   8048890 <exit@plt>
 8049712:	83 c4 6c             	add    $0x6c,%esp
 8049715:	5b                   	pop    %ebx
 8049716:	5e                   	pop    %esi
 8049717:	5f                   	pop    %edi
 8049718:	5d                   	pop    %ebp
 8049719:	c3                   	ret    

0804971a <explode_bomb>:
 804971a:	83 ec 18             	sub    $0x18,%esp
 804971d:	68 ac 9e 04 08       	push   $0x8049eac
 8049722:	e8 39 f1 ff ff       	call   8048860 <puts@plt>
 8049727:	c7 04 24 b5 9e 04 08 	movl   $0x8049eb5,(%esp)
 804972e:	e8 2d f1 ff ff       	call   8048860 <puts@plt>
 8049733:	c7 04 24 00 00 00 00 	movl   $0x0,(%esp)
 804973a:	e8 98 fa ff ff       	call   80491d7 <send_msg>
 804973f:	c7 04 24 f8 9b 04 08 	movl   $0x8049bf8,(%esp)
 8049746:	e8 15 f1 ff ff       	call   8048860 <puts@plt>
 804974b:	c7 04 24 08 00 00 00 	movl   $0x8,(%esp)
 8049752:	e8 39 f1 ff ff       	call   8048890 <exit@plt>

08049757 <read_six_numbers>:
 8049757:	83 ec 0c             	sub    $0xc,%esp
 804975a:	8b 44 24 14          	mov    0x14(%esp),%eax
 804975e:	8d 50 14             	lea    0x14(%eax),%edx
 8049761:	52                   	push   %edx
 8049762:	8d 50 10             	lea    0x10(%eax),%edx
 8049765:	52                   	push   %edx
 8049766:	8d 50 0c             	lea    0xc(%eax),%edx
 8049769:	52                   	push   %edx
 804976a:	8d 50 08             	lea    0x8(%eax),%edx
 804976d:	52                   	push   %edx
 804976e:	8d 50 04             	lea    0x4(%eax),%edx
 8049771:	52                   	push   %edx
 8049772:	50                   	push   %eax
 8049773:	68 cc 9e 04 08       	push   $0x8049ecc
 8049778:	ff 74 24 2c          	pushl  0x2c(%esp)
 804977c:	e8 4f f1 ff ff       	call   80488d0 <__isoc99_sscanf@plt>
 8049781:	83 c4 20             	add    $0x20,%esp
 8049784:	83 f8 05             	cmp    $0x5,%eax
 8049787:	7f 05                	jg     804978e <read_six_numbers+0x37>
 8049789:	e8 8c ff ff ff       	call   804971a <explode_bomb>
 804978e:	83 c4 0c             	add    $0xc,%esp
 8049791:	c3                   	ret    

08049792 <read_line>:
 8049792:	57                   	push   %edi
 8049793:	56                   	push   %esi
 8049794:	53                   	push   %ebx
 8049795:	e8 a7 f9 ff ff       	call   8049141 <skip>
 804979a:	85 c0                	test   %eax,%eax
 804979c:	75 62                	jne    8049800 <read_line+0x6e>
 804979e:	a1 40 b7 04 08       	mov    0x804b740,%eax
 80497a3:	39 05 6c b7 04 08    	cmp    %eax,0x804b76c
 80497a9:	75 12                	jne    80497bd <read_line+0x2b>
 80497ab:	83 ec 0c             	sub    $0xc,%esp
 80497ae:	68 de 9e 04 08       	push   $0x8049ede
 80497b3:	e8 a8 f0 ff ff       	call   8048860 <puts@plt>
 80497b8:	e8 5d ff ff ff       	call   804971a <explode_bomb>
 80497bd:	83 ec 0c             	sub    $0xc,%esp
 80497c0:	68 fc 9e 04 08       	push   $0x8049efc
 80497c5:	e8 86 f0 ff ff       	call   8048850 <getenv@plt>
 80497ca:	83 c4 10             	add    $0x10,%esp
 80497cd:	85 c0                	test   %eax,%eax
 80497cf:	74 0a                	je     80497db <read_line+0x49>
 80497d1:	83 ec 0c             	sub    $0xc,%esp
 80497d4:	6a 00                	push   $0x0
 80497d6:	e8 b5 f0 ff ff       	call   8048890 <exit@plt>
 80497db:	a1 40 b7 04 08       	mov    0x804b740,%eax
 80497e0:	a3 6c b7 04 08       	mov    %eax,0x804b76c
 80497e5:	e8 57 f9 ff ff       	call   8049141 <skip>
 80497ea:	85 c0                	test   %eax,%eax
 80497ec:	75 12                	jne    8049800 <read_line+0x6e>
 80497ee:	83 ec 0c             	sub    $0xc,%esp
 80497f1:	68 de 9e 04 08       	push   $0x8049ede
 80497f6:	e8 65 f0 ff ff       	call   8048860 <puts@plt>
 80497fb:	e8 1a ff ff ff       	call   804971a <explode_bomb>
 8049800:	8b 1d 68 b7 04 08    	mov    0x804b768,%ebx
 8049806:	8d 34 9b             	lea    (%ebx,%ebx,4),%esi
 8049809:	c1 e6 04             	shl    $0x4,%esi
 804980c:	81 c6 80 b7 04 08    	add    $0x804b780,%esi
 8049812:	89 f7                	mov    %esi,%edi
 8049814:	b8 00 00 00 00       	mov    $0x0,%eax
 8049819:	b9 ff ff ff ff       	mov    $0xffffffff,%ecx
 804981e:	f2 ae                	repnz scas %es:(%edi),%al
 8049820:	f7 d1                	not    %ecx
 8049822:	83 e9 01             	sub    $0x1,%ecx
 8049825:	83 f9 4f             	cmp    $0x4f,%ecx
 8049828:	75 12                	jne    804983c <read_line+0xaa>
 804982a:	83 ec 0c             	sub    $0xc,%esp
 804982d:	68 07 9f 04 08       	push   $0x8049f07
 8049832:	e8 29 f0 ff ff       	call   8048860 <puts@plt>
 8049837:	e8 de fe ff ff       	call   804971a <explode_bomb>
 804983c:	8d 04 9b             	lea    (%ebx,%ebx,4),%eax
 804983f:	c1 e0 04             	shl    $0x4,%eax
 8049842:	c6 84 01 7f b7 04 08 	movb   $0x0,0x804b77f(%ecx,%eax,1)
 8049849:	00 
 804984a:	83 c3 01             	add    $0x1,%ebx
 804984d:	89 1d 68 b7 04 08    	mov    %ebx,0x804b768
 8049853:	89 f0                	mov    %esi,%eax
 8049855:	5b                   	pop    %ebx
 8049856:	5e                   	pop    %esi
 8049857:	5f                   	pop    %edi
 8049858:	c3                   	ret    

08049859 <phase_defused>:
 8049859:	83 ec 78             	sub    $0x78,%esp
 804985c:	6a 01                	push   $0x1
 804985e:	e8 74 f9 ff ff       	call   80491d7 <send_msg>
 8049863:	83 c4 10             	add    $0x10,%esp
 8049866:	83 3d 68 b7 04 08 06 	cmpl   $0x6,0x804b768
 804986d:	75 77                	jne    80498e6 <phase_defused+0x8d>
 804986f:	8d 44 24 10          	lea    0x10(%esp),%eax
 8049873:	50                   	push   %eax
 8049874:	8d 44 24 10          	lea    0x10(%esp),%eax
 8049878:	50                   	push   %eax
 8049879:	68 22 9f 04 08       	push   $0x8049f22
 804987e:	68 70 b8 04 08       	push   $0x804b870
 8049883:	e8 48 f0 ff ff       	call   80488d0 <__isoc99_sscanf@plt>
 8049888:	83 c4 10             	add    $0x10,%esp
 804988b:	83 f8 02             	cmp    $0x2,%eax
 804988e:	75 3a                	jne    80498ca <phase_defused+0x71>
 8049890:	83 ec 08             	sub    $0x8,%esp
 8049893:	68 28 9f 04 08       	push   $0x8049f28
 8049898:	8d 44 24 1c          	lea    0x1c(%esp),%eax
 804989c:	50                   	push   %eax
 804989d:	e8 fc f6 ff ff       	call   8048f9e <strings_not_equal>
 80498a2:	83 c4 10             	add    $0x10,%esp
 80498a5:	85 c0                	test   %eax,%eax
 80498a7:	75 21                	jne    80498ca <phase_defused+0x71>
 80498a9:	83 ec 0c             	sub    $0xc,%esp
 80498ac:	68 1c 9c 04 08       	push   $0x8049c1c
 80498b1:	e8 aa ef ff ff       	call   8048860 <puts@plt>
 80498b6:	c7 04 24 44 9c 04 08 	movl   $0x8049c44,(%esp)
 80498bd:	e8 9e ef ff ff       	call   8048860 <puts@plt>
 80498c2:	e8 e8 f5 ff ff       	call   8048eaf <secret_phase>
 80498c7:	83 c4 10             	add    $0x10,%esp
 80498ca:	83 ec 0c             	sub    $0xc,%esp
 80498cd:	68 7c 9c 04 08       	push   $0x8049c7c
 80498d2:	e8 89 ef ff ff       	call   8048860 <puts@plt>
 80498d7:	c7 04 24 a8 9c 04 08 	movl   $0x8049ca8,(%esp)
 80498de:	e8 7d ef ff ff       	call   8048860 <puts@plt>
 80498e3:	83 c4 10             	add    $0x10,%esp
 80498e6:	83 c4 6c             	add    $0x6c,%esp
 80498e9:	c3                   	ret    
 80498ea:	66 90                	xchg   %ax,%ax
 80498ec:	66 90                	xchg   %ax,%ax
 80498ee:	66 90                	xchg   %ax,%ax

080498f0 <__libc_csu_init>:
 80498f0:	55                   	push   %ebp
 80498f1:	57                   	push   %edi
 80498f2:	31 ff                	xor    %edi,%edi
 80498f4:	56                   	push   %esi
 80498f5:	53                   	push   %ebx
 80498f6:	e8 c5 f0 ff ff       	call   80489c0 <__x86.get_pc_thunk.bx>
 80498fb:	81 c3 fd 17 00 00    	add    $0x17fd,%ebx
 8049901:	83 ec 1c             	sub    $0x1c,%esp
 8049904:	8b 6c 24 30          	mov    0x30(%esp),%ebp
 8049908:	8d b3 0c ff ff ff    	lea    -0xf4(%ebx),%esi
 804990e:	e8 21 ee ff ff       	call   8048734 <_init>
 8049913:	8d 83 08 ff ff ff    	lea    -0xf8(%ebx),%eax
 8049919:	29 c6                	sub    %eax,%esi
 804991b:	c1 fe 02             	sar    $0x2,%esi
 804991e:	85 f6                	test   %esi,%esi
 8049920:	74 27                	je     8049949 <__libc_csu_init+0x59>
 8049922:	8d b6 00 00 00 00    	lea    0x0(%esi),%esi
 8049928:	8b 44 24 38          	mov    0x38(%esp),%eax
 804992c:	89 2c 24             	mov    %ebp,(%esp)
 804992f:	89 44 24 08          	mov    %eax,0x8(%esp)
 8049933:	8b 44 24 34          	mov    0x34(%esp),%eax
 8049937:	89 44 24 04          	mov    %eax,0x4(%esp)
 804993b:	ff 94 bb 08 ff ff ff 	call   *-0xf8(%ebx,%edi,4)
 8049942:	83 c7 01             	add    $0x1,%edi
 8049945:	39 f7                	cmp    %esi,%edi
 8049947:	75 df                	jne    8049928 <__libc_csu_init+0x38>
 8049949:	83 c4 1c             	add    $0x1c,%esp
 804994c:	5b                   	pop    %ebx
 804994d:	5e                   	pop    %esi
 804994e:	5f                   	pop    %edi
 804994f:	5d                   	pop    %ebp
 8049950:	c3                   	ret    
 8049951:	eb 0d                	jmp    8049960 <__libc_csu_fini>
 8049953:	90                   	nop
 8049954:	90                   	nop
 8049955:	90                   	nop
 8049956:	90                   	nop
 8049957:	90                   	nop
 8049958:	90                   	nop
 8049959:	90                   	nop
 804995a:	90                   	nop
 804995b:	90                   	nop
 804995c:	90                   	nop
 804995d:	90                   	nop
 804995e:	90                   	nop
 804995f:	90                   	nop

08049960 <__libc_csu_fini>:
 8049960:	f3 c3                	repz ret 

Disassembly of section .fini:

08049964 <_fini>:
 8049964:	53                   	push   %ebx
 8049965:	83 ec 08             	sub    $0x8,%esp
 8049968:	e8 53 f0 ff ff       	call   80489c0 <__x86.get_pc_thunk.bx>
 804996d:	81 c3 8b 17 00 00    	add    $0x178b,%ebx
 8049973:	83 c4 08             	add    $0x8,%esp
 8049976:	5b                   	pop    %ebx
 8049977:	c3                   	ret    
