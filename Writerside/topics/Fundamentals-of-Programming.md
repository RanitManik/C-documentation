# Fundamentals of a Program

## Basics

- An **algorithm** is the approach or method used to solve a problem.
- A **program** comprises statements that solve a specific problem.
- The set of instructions implementing the algorithm constitutes the program.
- Writing a program involves expressing these instructions in a specific computer language, such as Java, C++,
  Objective-C, or C.

## Terminology

- **CPU (Central Processing Unit):** Performs the majority of computing work, executing instructions.
- **RAM (Random Access Memory):** Temporarily stores a program's data during runtime.
- **Hard Drive (Permanent Storage):** Stores program source code files even when the computer is off.
- **Operating System:** Manages computer resources, handles program execution, and facilitates user interactions (e.g.,
  Windows, Unix, Android).
- **Fetch/Execute Cycle:** The life cycle of a CPU, where it fetches instructions from memory and executes them.

Learn more about Systems Architecture on [BBC Bitesize](https://www.bbc.co.uk/bitesize/guides/z7qqmsg/revision/1).

## Fetch/Execute Cycle

The fetch-execute cycle, or fetch-decode-execute cycle, is a processor's method for processing instructions. The cycle
involves several stages:

1. The memory address in the program counter (PC) is copied into the Memory Address Register (MAR).
2. The program counter's address is incremented by one.
3. The processor sends a signal along the address bus to the MAR.
4. The instruction/data from that memory address is sent along the data bus to the Memory Buffer Register/Data
   Register (MBR/MDR).
5. The instruction/data in the MBR/MDR is copied into the Current Instruction Register (CIR).
6. The CIR's instruction/data is decoded and executed, with results stored in the Accumulator (ACC).
7. The cycle returns to step one.

## Higher Level Programming Languages

- **High-level programming languages** simplify program writing, providing a more abstract representation of actions.
- Examples include C, offering statements resembling problem-solving steps.
- High-level languages are easier to learn and program in than machine languages.
- **Compilers** translate high-level language source code into detailed machine language instructions, handling syntax
  checking.

## Steps in Writing a Program

1. **Define Program Objectives:**
    - Understand program requirements and objectives clearly.

2. **Design:**
    - Plan how the program will meet the defined requirements.
    - Consider user interface and program organization.

3. **Write the Code:**
    - Begin implementation by translating the design into C syntax.
    - Create a source code file using a text editor.

4. **Compile:**
    - Translate the source code into machine code, forming an executable file with CPU instructions.

5. **Run the Program:**
    - Execute the program using the generated executable file.

6. **Test and Debug:**
    - Test the program to ensure it functions as intended.
    - Debugging involves finding and fixing errors.

7. **Maintain and Modify the Program:**
    - Continue fixing bugs and adding features as needed.
    - Iteratively go through steps based on evolving requirements.

> **Note:** Many new programmers skip steps 1 and 2, heading straight to coding. However, for larger programs, planning
> is crucial. Developing a habit of planning before coding is advisable. When coding, work in small, testable steps to
> streamline the process (divide and conquer).

*For effective development, consider jumping between steps and repeating them as necessary.*