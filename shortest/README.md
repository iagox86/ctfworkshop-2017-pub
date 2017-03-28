This simply runs code sent to it. The goal is to read the context of flag.txt,
which is loaded into memory.

The trick: you have a maximum of 5 bytes of shellcode in order to read the
memory.

Probably requires some reverse engineering! Including the binary.

Good luck!

`nc ctf.skullspace.net 6127`
