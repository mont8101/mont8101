Instructions:To run our program, make sure you are in the project directory. Type make clean, enter, type make, enter. This will set up the simulator file to be run. You can then enter for example ./msim -i tests/class.mc That will run the program with the supplied instructions. You can interchange class.mc with any other test we have provided inside the tests folder.

Files Included: Makefile: helps run the program by preloading all of the gcc commands into assembler so all you have to type is ./msim to run

msim.c: This is the c code we have written to run machine code and print the output to the command line. It will show the state of each register and memory location after operations are ran from the machine code using input from our tests.

tests/ class.asm: This is the supplied assembly language code that can be built into runnable machine code.

class.mc: This is the supplied machine code file that is used to test correctness our simulator output.

addtest.asm: We created this assembley code as a benchmark for thousands of adds.

addtest.mc: This is the machine code for our add test.

beqtest.asm: We created this assembley code as a benchmark for thousands of branch on equals.

beqtest.mc: This is the machine code for our branch on equals test.

jalrtest.asm: We created this assembley code as a benchmark for thousands of jump and link registers.

jalrtest.mc: This is the machine code for our jump and link register test.

lwtest.asm: We created this assembley code as a benchmark for thousands of load words.

lwtest.mc: This is the machine code for our load word test.

swtest.asm: We created this assembley code as a benchmark for thousands of store words.

swtest.mc: This is the machine code for our store word test.

nandtest.asm: We created this assembley code as a benchmark for thousands of nands.

nandtest.mc: This is the machine code for our nand test.

mixedtest.asm: We created this assembley code as a benchmark for thousands of all operations.

mixedtest.mc: This is the machine code for our mixed test.
