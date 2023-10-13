<img align="center" src="book.png">

Hacking
====

This repository contains the source code that comes from the book:
[Hacking The Art of Exploitation](https://en.wikipedia.org/wiki/Hacking:_The_Art_of_Exploitation#Content_of_2nd_edition).

## Notes
The VM that this code runs on is an Ubuntu-based Live Linux Distro.
It contains all of the source code and the code all compiles under GCC version 3.3.6.  

It's also worth noting that much of the exploits won't work under GCC 4 with the buffer overflow
detection. Instead of stack-smashing and moving on, it will detect buffer overflows and seg fault
without overflowing the buffers. (Using the VM lets you play with the exploits).

## Related Links
https://nostarch.com/hacking2.htm - book on nostarch
https://www.amazon.com/Hacking-Art-Exploitation-Jon-Erickson/dp/1593271441 - book on amazon
