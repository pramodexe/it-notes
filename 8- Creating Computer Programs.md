# Creating Computer Programs Study Notes

## 1. What is a Computer Program?

- Definition: A set of sequenced instructions to cause a computer to perform particular operations.
- Hardware/Software Interaction:
  - Programs tell the CPU to process interrupts (sets of steps to perform tasks).
  - Machine code/language: Binary code (1s and 0s) that controls hardware.
  - Source code: Program written in human-readable programming language.
  - Object code: Binary version of source code, created by compilers or interpreters.

### Compilation and Interpretation
- **Compiler**:
  - Translates entire program into machine language before execution.
  - Creates stand-alone executable file.
  - Each programming language requires its own compiler.
  - Examples: Pascal, C
- **Interpreter**:
  - Translates and executes instructions one at a time.
  - Slower than compilers, doesn't generate object code.
  - Examples: LISP, BASIC, PERL

| Aspect | Compiler | Interpreter |
|--------|----------|-------------|
| Processing | Entire program at once | Line by line |
| Speed | Faster execution | Slower execution |
| Memory | More (due to object code) | Less |
| Error handling | All at once after compilation | One by one during execution |
| Languages | C, C++, C# | PHP, Perl, Python, Ruby |

## 2. How Programs Solve Problems

### Program Control Flow
- The order in which program statements are executed.
- Tools:
  - Flowcharts: Visual representation of program sequence.
  - Pseudocode: Simple text version of program's code.

### Algorithms
- Definition: A set of steps that always lead to a solution.
- Represented in flowcharts.
- A program may contain thousands of algorithms, each for a specific task.

### Flowchart Symbols and Constructs
- Symbols:
  - Terminal: Start/End
  - Input/Output
  - Process
  - Decision
  - Connector
  - Flow lines
- Constructs:
  - Sequence
  - Selection (if-then-else)
  - Repetition (loops)

### Common Flow Patterns
- Conditional statements: Determine if a condition is true.
- Loops: Repeat until a condition is met.

### Variables and Functions
- Variables: Named placeholders for data being processed.
- Functions: Sets of steps to perform specific tasks.

## 3. Two Approaches: Structured & Object-Oriented Programming

### Structured Programming
- Eliminates use of 'goto' statements.
- Uses three control structures:
  1. Sequence: Default control flow.
  2. Selection: Built around conditional statements (if-then-else).
  3. Repetition: Uses loops based on conditions.

### Object-Oriented Programming (OOP)
- Based on objects and classes.
- Key concepts:
  - Objects: Blocks of code with functions and attributes.
  - Classes: Groups of objects sharing common attributes.
  - Subclasses: Divisions of classes (inheritance).
  - Messages: Communication between objects.
  - Encapsulation: Objects can contain other objects.
- Advantages:
  - Code reuse
  - Simplified program development
  - Better data hiding (more secure)

### Structured vs. Object-Oriented Programming

| Aspect | Structured | Object-Oriented |
|--------|------------|-----------------|
| Division | Functions | Objects |
| Approach | Top-down | Bottom-up |
| Data hiding | Less secure | More secure |
| Examples | C, FORTRAN, Pascal, Basic | C++, C#, Java, Python |

## Additional Concepts
- Integer division: `div` operator
- Modulus: `mod` operator (remainder in integer division)

## Study Tips
- Practice creating flowcharts for everyday tasks.
- Understand the differences between compilation and interpretation.
- Focus on the three main constructs of structured programming: sequence, selection, and repetition.
- For OOP, visualize real-world objects and their attributes to understand classes and objects.
- Practice tracing program flow using flowcharts and pseudocode.
