# linux-kernel-pwn

Here i accumulate notes, whitepapers, other's lists of stuff, anything useful for myself that i come across while trying to learn linux kernel exploitation, and my own attempts of solving related CTF challs. So it's sort of constant WIP.


## Challs in `exploits`

- [2017 CISCN - babydriver](https://github.com/pr0cf5/kernel-exploit-practice/tree/master/babydriver)
- [2018 0CTF Finals - Baby Kernel](https://github.com/ctf-wiki/ctf-challenges/tree/master/pwn/kernel/0CTF2018-baby)


## Probably useful stuff

### MEMORY MANAGEMENT & ALLOCATORS

#### Videos

- [GWU OS: Memory Allocation - Slab and Buddy Allocators](https://www.youtube.com/watch?v=DRAHRJEAEso)
- [SLUB Internals for Exploit Developers](https://www.youtube.com/watch?v=2hYzxsWeNcE), Andrey Konovalov
- [The Linux Maple Tree](https://www.youtube.com/watch?v=XwukyRAL7WQ), Matthew Wilcox

#### Articles

- Linternals series by sam4k
  1. [Linternals: Introducing Memory Allocators & The Page Allocator](https://sam4k.com/linternals-memory-allocators-part-1/) - Buddy (page) allocator, memory zones, nodes
  2. [Linternals: The User Virtual Address Space](https://sam4k.com/linternals-virtual-memory-0x02)
  3. [Linternals: The Kernel Virtual Address Space](https://sam4k.com/linternals-virtual-memory-part-3/)
- [Linux Kernel Exploitation Part 2: Buddy Allocator and SLUB Allocator](https://dangokyo.me/2018/10/30/linux-kernel-exploitation-buddy-allocator-and-slub-allocator/)

#### Books

- **Understanding The Linux Virtual Memory Manager**, [Chapter 6. Physical Page Allocation](https://www.kernel.org/doc/gorman/html/understand/understand009.html), Mel Gorman

### Unsorted

- ...
