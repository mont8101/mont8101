Instructions: To run our program, make sure you are in the project directory. Type make clean, enter, type make, enter. This will set up the assembler file to be run. You can then enter for example ./asm -i tests/supplied.asm That will run the program with the supplied instructions. You can interchange supplied.asm with any other test we have provided inside the tests folder.

Files Included: Makefile: helps run the program by preloading all of the gcc commands into assembler so all you have to type is ./asm to run

assembler.c: This is the c code we have written to produce a working assembler to be used with any assembly language in an .asm file as input, and outputs the contents as machinecode into a .mc file.

tests/ supplied.asm: This is the supplied assembly language file that is used to test correctness our machine code output.

undefined.asm: This tests if the program can handle the use of indefined labels, for example ones that start with numbers or use weird characters

duplicate.asm: This tests if the program can handle the use of duplicate labels in the assembly language

offset.asm: This tests if the program can handle offset fields that don't fit in 16 bits

unrecognized.asm: This tests if the program can handle unrecognized opcodes that aren't add, nand, lw, sw, beq, jalr, halt or noop

spaces.asm: This tests if the program can handle the the assembly language being entirely spaces
