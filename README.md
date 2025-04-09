This is a simple mini compiler.

Steps for running the project:

1. If the nessesary package is not installed then install the packages first.
   For Linux run the commands in terminal:-
   
   sudo apt-get update
   sudo apt-get install flex bison
 
2. After installing the packages run this command in the terminal.
  ./compile.bash
  ./compiler simple.mini.c
   Here, simple.mini.c is a input c program.

   After running these commands a simple.mini.c.ir file will be create. In this file you will see the intermediate code generated by the compiler for the input c code named the file as simple.mini.c 

