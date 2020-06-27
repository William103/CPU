# CPU
Inspired by an assignment in CS31, Introduction to Computer
Systems, at Swarthmore, in which we built an ALU in Logisim,
my roommate and lab partner Quinn Okabayashi and I decided
that an ALU was not enough, so we built an entire CPU with
the eventual extremely nerdy goal of implementing it in
Minecraft. Still a WIP, it is almost Turing Complete, featuring
jumps, loads, addition, and subtraction with 8, 8-bit registers
and 8 bytes of memory, each containing one 15-bit word.

## Machine Code and Programming
It is quite difficult to program. At the moment I don't have
access to my notebook containing how the machine code works,
and it is way too complicated to do from memory, but each 15-bit
word instruction (all instructions are 1 "byte" to simplify
things considerably) is made up of a 3-bit opcode, 1 bit
indicating whether the op1 is a register or immediate value,
8 bits for op1 (register or immediate value), and 3 bits
selecting the register for op2.
