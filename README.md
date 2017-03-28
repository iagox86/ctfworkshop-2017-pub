Welcome to the SkullSpace CTF workshop!

This is a list of all the levels. You can find all the files you need to complete each level in the appropriate folders. You'll be given the port number, and occasionally source files or other things you need. And sometimes hints!

You might also want to check out FLAGS.md to verify your flags and TOOLS.md for a list of the tools I suggest.

These are roughly ordered by difficulty, easiest to hardest.

# Easier / training challenges

These are challenges designed to teach basic CTF skills, the primary theme being writing shellcode.

## [easyauth](easyauth/)

Port: 6112

A simple web problem.

## dontcrash

Port: 6113

This is a great beginner level, simply write shellcode that doesn't crash!

## easycap

Port: n/a

Can you read a pcap?

## easyreverse

Port: n/a

Reverse engineer this simple program!

## seteax, seteax-nz

Port: 6114 (basic) and 6115 (nz)

Write some fairly simple shellcode (the -nz variation doesn't allow NUL bytes)

## readmem, readmem-nz

Port: 6116 (basic) and 6117 (nz)

Read the flag from a known memory address

## writemem, writemem-nz

Port: 6118 (basic) and 6119 (nz)

Write a special value to a known memory address

## readstack, readstack-nz

Port: 6120 (basic) and 6121 (nz)

Read the flag off the stack!

## writestack, writestack-nz

Port: 6122 (basic) and 6123 (nz)

Write a special value to the stack (without damaging the rest of the stack)

## readfile, readfile-nz

Port: 6124 (basic) and 6125 (nz)

Read the flag from a file on the disk

# Harder / real challenges

These are challenges from BSidesSF CTF. Some are easier, some are harder. You can find solutions if you google the name, so only do that if you're completely stuck!

## skipper, skipper2

Port: n/a

Modify a binary (on disk or in memory) to decrypt the flag

## hashecute

Port: 6126

Shellcode with an MD5 prefix

## shortest

Port: 6127

Shellcode, in 5 bytes or less

## b-64-b-tuff

Port: 6128

Shellcode, that's base64 compatible

## in-plain-sight

Port: n/a

A fun little crypto problem

## ximage

Port: n/a

Good luck figuring out the flag! Just remember the theme. :)

## vhash

Port: 6129

Some reverse engineering, some crypto, and some web. Fairly difficult!

## nibbler

Port: 6130

Write some game AI to build shellcode! Really
