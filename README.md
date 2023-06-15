# Bypassing-ASLR
Used problem solving and reverse engineering to find the exploits for 10 binaries with ASLR turned on. Exploited the vulnerabilities in ASLR using Heap Buffer Overflows and Return Oriented Programming. Created the shellcode and deduced the NOP Slide required to overwrite the return address to point to the heap, text, data or bss regions.
