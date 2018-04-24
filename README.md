# CTF-buf2
Binary challenge 2 for Beginner CTF @ Nerdlab

Will be run on a vurnerable x86 host, if you try to solve this locally, compile with:

gcc -g -static --no-pie -o buf2 buf2.c

Before running execute:

echo 0 > /proc/sys/kernel/randomize_va_space 

this will disable ASLR and make your host vurnerable (please don't do this on your main OS), tested on a vurnerable x86 kali machine.
