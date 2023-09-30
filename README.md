# fetch-decode-execute-cycle-Simulator-OperatingSystem
# Introduction:
This readme file provides instructions on how to compile and run the fetch-decode-execute-cycle-Simulator program and explains its outputs. Additionally, it provides details about the supported opcodes, memory layout, and sample programs included in the simulation.

# Program Overview
The Instruction Simulator is a C++ program that emulates a simple computer with memory and registers. It executes a sequence of instructions stored in memory, including basic arithmetic operations (LOAD, ADD, SUB, MUL), memory storage (STORE). The program is designed to demonstrate the execution of these instructions and their effects on the computer's memory and registers.

# Compilation and Execution
To compile and run the Instructon Simulator program, follow these steps:

1. Compile the Program:
    Open a terminal or command prompt and navigate to the directory containing the program source code (instruction_simulator.cpp). Use a C++ compiler (e.g., g++) to compile the program:

    ![image](https://github.com/anumsajid13/fetch-decode-execute-cycle-Simulator-OperatingSystem/assets/119041733/56fcf918-38cd-4fc7-9e3b-783b183ba687)

    This command compiles the program and generates an executable file named computer_simulator.
   
    Execute the compiled program by running:
   
    ![image](https://github.com/anumsajid13/fetch-decode-execute-cycle-Simulator-OperatingSystem/assets/119041733/9c2d7c87-6ed2-492a-9914-720dff28bfac)


# Program Outputs
The program provides detailed outputs as it executes the sample program. Here's an explanation of the key outputs:

1. Memory Display: 
At the beginning of execution, the program displays the contents of memory, showing the opcode and value for each memory location. Empty memory locations are labeled as "EMPTY." This provides an initial view of the program's memory layout.

![image](https://github.com/anumsajid13/fetch-decode-execute-cycle-Simulator-OperatingSystem/assets/119041733/dd26a8fd-2598-4387-8abb-13b41b8549d3)


# Instruction Execution
As the program progresses, it displays the current instruction being executed, the program counter (PC), and the contents of the instruction register (IR). For example:

![image](https://github.com/anumsajid13/fetch-decode-execute-cycle-Simulator-OperatingSystem/assets/119041733/d0b4423c-73c3-4d50-9428-9ea031241341)

This output indicates that the program is executing the instruction at memory location 0, which is "LOAD 3." The instruction register (IR) holds the current instruction, and the accumulator (AC) is updated accordingly.

# Memory Updates
When STORE instructions are executed, the program displays updates to memory, indicating the new values stored in specific memory locations. For example:

![image](https://github.com/anumsajid13/fetch-decode-execute-cycle-Simulator-OperatingSystem/assets/119041733/dfc9c67d-9ec8-4889-ae64-bd2ba02870ec)

This output shows that the program has executed a STORE instruction, storing the value 12 in memory location 5.

# Supported Opcodes
The program supports the following opcodes:

LOAD: Load a value from memory into the IR.

ADD: Add a value from memory to the value in AC.

SUB: Subtract a value from memory from the value in AC.

MUL: Multiply the value in AC by a value from memory.

STORE: Store the AC value into memory.

# Memory Layout
The computer's memory is organized into a fixed array of memory locations. In the sample program, memory locations are used for both instructions and data. Instructions have associated opcodes, values, and types ("Instruction" or "Data"). The memory layout is defined in the program source code, and it can be modified to create custom programs.

# Sample Programs
The program includes several sample programs in memory to demonstrate its functionality. These sample programs contain sequences of instructions and data, and they are executed one after the other.

![image](https://github.com/anumsajid13/fetch-decode-execute-cycle-Simulator-OperatingSystem/assets/119041733/91769792-cc80-4754-bbb0-ca3707b45504)

![image](https://github.com/anumsajid13/fetch-decode-execute-cycle-Simulator-OperatingSystem/assets/119041733/729f9a5f-8a6e-40f9-b322-5b8a3fb39e6b)






