# lkt

- Welcome, here you will find all my pwn related writeups and resources.

## Writeups

<details>
    <summary><strong>Hack The Box Writeups</strong></summary>

- [magic scrolls](https://github.com/Iokete/writeups/tree/main/pwn/hackthebox/htb.magic.scrolls.heap)
  	> OOB write to achieve arb read/free into tcache poisoning via fake chunk

- [sound of silence](https://github.com/Iokete/writeups/tree/main/pwn/hackthebox/htb.sound.of.silence)
	> rop chain, register reuse

</details>

<details>
    <summary><strong>URJC CTF Introductory Course Writeups</strong></summary>

- [gestorcuentas](https://github.com/Iokete/writeups/tree/main/pwn/urjc.ctf.course/tls.dtor.overwrite.gestorcuentas)
	> arbitrary write TLS Storage dtor_list overwrite to achieve RCE

- [kebab amigo II](https://github.com/Iokete/writeups/tree/main/pwn/urjc.ctf.course/kebab.amigo.ii.rop)
	> incorrect `scanf` formatting, buffer overflow, ret2libc

</details>

<details>
    <summary><strong>Exploitation techniques</strong></summary>

- [house of force](https://github.com/Iokete/writeups/tree/main/pwn/techniques/house.of.force)<br>
	
 	> top chunk size corruption to achieve arbitrary write, rce via `__malloc_hook` overwrite


</details>

## Useful resources 

<details open>
	<summary><strong>Stack</strong></summary>
	
- [Stack Data Structure](https://www.programiz.com/dsa/stack)
- [PWN 101 YouTube Playlist from CryptoCat](https://www.youtube.com/playlist?list=PLHUKi1UlEgOIc07Rfk2Jgb5fZbxDPec94)
- [PWN 101 TryHackMe Room](https://tryhackme.com/room/pwn101)
- [https://www.youtube.com/@RazviOverflow](https://www.youtube.com/@RazviOverflow)
- [RET2CSU BlackHat Papers](https://i.blackhat.com/briefings/asia/2018/asia-18-Marco-return-to-csu-a-new-method-to-bypass-the-64-bit-Linux-ASLR-wp.pdf)
- [ROP Emporium](https://ropemporium.com/)
	- [CryptoCat Solve Playlist](https://www.youtube.com/watch?v=oBZy0bGNezo&list=PLHUKi1UlEgOKAVRdiMlpX6hgayiY6dTwu)
- [This page](https://github.com/nushosilayer8/pwn) explains the following techniques:
	- BROP (Blind ROP)
	- SROP (Sigreturn Oriented Programming)
	- Ret2csu
	- Ret2dlresolve
- [ret2dl_resolve x64: Exploiting Dynamic Linking Procedure In x64 ELF Binaries](https://syst3mfailure.io/ret2dl_resolve/)
- [ROP return to dl-resolve (in Chinese)](https://rk700.github.io/2015/08/09/return-to-dl-resolve/#64%E4%BD%8D%E7%8E%AF%E5%A2%83%E4%B8%8Breturn-to-dl-resolve)
- [Boosting your ROP skills with SROP and ret2dlresolve - Giulia Martino - HackTricks Track 2023](https://www.youtube.com/watch?v=ADULSwnQs-s&t=858s)
- [Temple Of Pwn 12 - Ret2DlResolve](https://www.youtube.com/watch?v=6qMabyX0yPw)
	
</details>

<details open>
<summary><strong>General</strong></summary>
	
- [Nightmare](https://guyinatuxedo.github.io/)
	- Hoppers’ remix [https://github.com/hoppersroppers/nightmare](https://github.com/hoppersroppers/nightmare)
- [Nightmare Challenges](https://github.com/guyinatuxedo/nightmare/tree/master/modules)
- [GDB Cheatsheet](https://darkdust.net/files/GDB%20Cheat%20Sheet.pdf)
- [GDB Primer](https://people.cs.pitt.edu/~mosse/gdb-note.html)
- [Installer for all GDB pwn related plugins](https://github.com/apogiatzis/gdb-peda-pwndbg-gef)
- [pwn.college](https://pwn.college/)
- [Temple Of Pwn - Youtube Playlist](https://www.youtube.com/watch?v=TqGMVRV2l9s&list=PLiCcguURxSpbD9M0ha-Mvs-vLYt-VKlWt)
- [https://ir0nstone.gitbook.io/](https://ir0nstone.gitbook.io/)
- [https://www.hoppersroppers.org/roadmap/training/pwning.html](https://www.hoppersroppers.org/roadmap/training/pwning.html)
	- This blog has a lot of info + at the end some links for ARM and Windows
- [https://www.lazenca.net/display/TEC/02.TechNote](https://www.lazenca.net/display/TEC/02.TechNote) <- goated
- [php heap exploitation](https://web.archive.org/web/20240714044301/https://deepunk.icu/php-pwn/)
- [https://nickgregory.me/post/2019/04/06/pivoting-around-memory/](https://nickgregory.me/post/2019/04/06/pivoting-around-memory/)
	
</details>
		
<details open>
	<summary><strong>Fuzzing</strong></summary>

- [Fuzzing.in](https://fuzzing.in/)
- [Fuzzing 101](https://github.com/antonio-morales/Fuzzing101)
	
</details>

<details open>
<summary><strong>Kernel</strong></summary>
	
- [So You Wanna Pwn The Kernel?](https://sam4k.com/so-you-wanna-pwn-the-kernel/#ego)
- [Learning Linux Kernel Exploitation - Part 1 - Midas Blog](https://lkmidas.github.io/posts/20210123-linux-kernel-pwn-part-1/#analyzing-the-kernel-module)
- [Linux Kernel Pwn Basics](https://mem2019.github.io/jekyll/update/2019/01/11/Linux-Kernel-Pwn-Basics.html)
- [https://github.com/xairy/linux-kernel-exploitation](https://github.com/xairy/linux-kernel-exploitation) - **Big** collection of links
- [Youtube playlist of different system exploitation ctf solving](https://www.youtube.com/playlist?list=PLMOpZvQB55bcRA5-KjvW7dVyGUarcqZuL)
- [https://lwn.net/Kernel/LDD3/](https://lwn.net/Kernel/LDD3/)
- [https://github.com/smallkirby/kernelpwn](https://github.com/smallkirby/kernelpwn)
- [https://r1ru.github.io/posts/6/](https://r1ru.github.io/posts/6/)
- [More kernel ROP](https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/linux-kernel-rop-ropping-your-way-to-part-1)
- [kernel useful structures](https://ptr-yudai.hatenablog.com/entry/2020/03/16/165628)
  
</details>

<details>
	
<summary><strong>Heap</strong></summary>

- HeapLAB Udemy course by Max Camper ([ROP Emporium](https://ropemporium.com/) creator)
	- [Part 1](https://www.udemy.com/course/linux-heap-exploitation-part-3)
	- [Part 2](https://www.udemy.com/course/linux-heap-exploitation-part-2)
	- [Part 3](https://www.udemy.com/course/linux-heap-exploitation-part-3)
- [House of Orange - Pwning My Life](https://4ngelboy.blogspot.com/2016/10/hitcon-ctf-qual-2016-house-of-orange.html?m=1)
- [Seed Labs CTF Repository](https://github.com/cole-wustl/seed-labs-ctf)

</details>

<details open>
<summary><strong>FSOP</strong></summary>
	
- [Roderick Chan - house of apple 1](https://roderickchan.github.io/zh-cn/house-of-apple-%E4%B8%80%E7%A7%8D%E6%96%B0%E7%9A%84glibc%E4%B8%ADio%E6%94%BB%E5%87%BB%E6%96%B9%E6%B3%95-1/)
- [Roderick Chan - house of apple 2](https://roderickchan.github.io/zh-cn/house-of-apple-%E4%B8%80%E7%A7%8D%E6%96%B0%E7%9A%84glibc%E4%B8%ADio%E6%94%BB%E5%87%BB%E6%96%B9%E6%B3%95-2/)
- [Roderick Chan - house of apple 3](https://roderickchan.github.io/zh-cn/house-of-apple-%E4%B8%80%E7%A7%8D%E6%96%B0%E7%9A%84glibc%E4%B8%ADio%E6%94%BB%E5%87%BB%E6%96%B9%E6%B3%95-3/)
- [Kyle bot - angry-FSOP - using angr to explore FSOP path](https://blog.kylebot.net/2022/10/22/angry-FSROP/)
- [Nifitic - Deep dive into FSOP](https://niftic.ca/posts/fsop/)
- 
</details>

<details open>
<summary><strong>Shellcoding</strong></summary>
	
- [x64.syscall.sh](https://x64.syscall.sh/): Your cheat sheet for syscalls. A glance here, and you're always ahead.
- [Syscalls Manpage](https://man7.org/linux/man-pages/man2/syscalls.2.html): Understand not just the calls, but their deeper implications.
- [Felix Cloutier](https://www.felixcloutier.com/x86/): Dive into the heartbeats of instructions, ensuring you're always in step.
- [x86asm Reference](http://ref.x86asm.net/coder64.html): amd64 opcode listing.

</details>

<details open>
	

<summary><strong>Windows</strong></summary>

- [Windows and Linux pwn](https://ctf-wiki.mahaloz.re/pwn/readme/)
- [pwncollege Module](https://pwn.college/windows-warzone/)
- [Leaking Kernel32 address via shellcode](https://blog.xenoscr.net/2019/12/08/Locating-Kernel32-Base-Address.html)
- [https://fuzzysecurity.com/tutorials.html](https://fuzzysecurity.com/tutorials.html)
</details>

<details open>
	
<summary><strong>ARM</strong></summary>

- [https://academy.8ksec.io/course/arm-exploitation-challenges](https://academy.8ksec.io/course/arm-exploitation-challenges)
- [https://pwn.college/arm-architecture/](https://pwn.college/arm-architecture/)
- [https://pwn.college/xnu/](https://pwn.college/xnu/)
  
</details>
