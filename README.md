# virtual-machine
This project implements a basic virtual machine using a Pascal-like instruction set. It executes instructions read from a file, simulating a simple stack-based machine. The virtual machine supports various operations including arithmetic, logic, control flow, and I/O operations.

## Features
**Array Management:** Uses a stack (pas) to store and manage instructions and data.

### Instruction Set: ###
- LIT: Load literal value into the stack.
- OPR: Perform operations (e.g., ADD, SUB, MUL, DIV, EQL, NEQ, LSS, LEQ, GTR, GEQ).
- LOD: Load data from a specific base level.
- STO: Store data into a specific base level.
- CAL: Call a subroutine.
- INC: Increase the stack pointer by a given value.
- JMP: Jump to a specific instruction.
- JPC: Jump to a specific instruction if the top of the stack is zero.
- SYS: System calls (e.g., INPUT, OUTPUT, HALT).

## How to Run ## 
1) **Compile the code:**
  gcc virtualMachine.c -o virtualMachine
2) **Run:**
  ./virtualMachine <input_file>
