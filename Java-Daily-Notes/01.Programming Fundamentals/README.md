# Module 1: Introduction to Programming
## 1. What is Programming?
Programming is the process of writing instructions (called code) that tell a computer what to do.
#### Example:
      Calculator app
      ATM software
      YouTube
      WhatsApp
All of these work because programmers wrote code.
## 2. Why do we need programming?
Programming is used to instruct a computer to perform tasks and solve problems.
#### Without programming, computers cannot:
      Perform calculations
      Display websites
      Play videos
      Store information
      Run applications
## 3. Use of Programming?
Programming is used to create software and instruct computers to perform tasks automatically, accurately, and efficiently.
## 4. What is a Programmer?
A programmer is a person who writes, tests, and maintains computer programs.
#### Responsibilities:
      Solve problems
      Write code
      Fix errors
      Improve software
## 5. Coding vs Programming
#### coding:
Coding is the process of writing instructions in a programming language to perform a specific task.
#### Programming:
Programming is the complete process of solving a problem, which includes analyzing the problem, designing a solution, writing code, testing, debugging, and maintaining the software.
## 6. History of Programming Languages
      1940s – Machine Language
      1950s – Assembly Language
      1972 – C
      1983 – C++
      1991 – Python
      1995 – Java
Modern languages are easier to learn and more powerful.
# Module 2: Programming Languages
## 1. What is Programming Language?
A programming language is a set of rules and syntax used to write programs that instruct a computer to perform specific tasks. It acts as a bridge between humans and computers. 
#### Examples:
      Java
      Python
      C
      C++
## 2. What are the Types Of Programming Languages?
Programming languages are mainly classified into three types: Machine Language, Assembly Language, and High-Level Language. 
### 1. Machine Language (1GL)
Machine language is the lowest-level programming language that consists only of 0s and 1s (binary code). It is directly understood by the computer.
#### Features
      Written in binary (0 and 1)
      Fast execution
      Machine dependent
      Difficult for humans to read and write
#### Example
      10110010 11001100
### 2. Assembly Language (2GL)
Assembly language uses mnemonic codes (such as ADD, MOV, SUB) instead of binary numbers. It requires an assembler to convert it into machine language.
#### Features
      Easier than machine language
      Machine dependent
      Faster than high-level languages
#### Example
      MOV A, B
      ADD A, C
### 3. High-Level Language (3GL)
A high-level language is easy for humans to read, write, and understand. It uses English-like syntax and must be translated into machine language using a compiler or interpreter.
#### Features
      Easy to learn and write
      Machine independent (portable)
      Used to develop software, websites, mobile apps, AI, and games
#### Examples
      Java
      Python
      C
      C++
      C#
      JavaScript
#### what are the Types of High-Level Languages
High-level languages are further divided into procedural, object-oriented, functional, and scripting languages.
#### A. Procedural Programming Language
Programs are written as a sequence of procedures or functions.
Focuses on step-by-step execution
#### Examples: C, Pascal
#### B. Object-Oriented Programming (OOP)
Programs are organized using objects and classes.
Supports code reuse and easier maintenance.
#### Examples: Java, C++, C#
#### C. Functional Programming Language
Programs are built using functions.
Emphasizes immutability and avoids changing data directly.
#### Examples: Haskell, Lisp, Scala
#### D. Scripting Language
Used to automate tasks and create dynamic web applications.
Usually interpreted instead of compiled.
#### Examples: JavaScript, Python, PHP
### 4. 4GL (Fourth-Generation Language)
A Fourth-Generation Language (4GL) is a high-level programming language designed to make programming easier by allowing developers to specify what they want to do rather than how to do it.
#### Features
      Easy to learn and use
      Requires fewer lines of code
      Focuses on database applications and report generation
      Increases programmer productivity
#### Examples
      SQL
      MATLAB
      SAS
      Oracle Reports
#### Uses
      Database management
      Report generation
      Data analysis
      Business applications
#### Example (SQL)
      SELECT * FROM Employee;
This retrieves all records from the Employee table.
### 5. 5GL (Fifth-Generation Language)
A Fifth-Generation Language (5GL) is a programming language mainly used in Artificial Intelligence (AI) and expert systems. Instead of writing detailed algorithms, the programmer specifies the problem or goal, and the system determines how to solve it.
#### Features
      Used for AI and expert systems
      Based on logic and constraints
      Focuses on problem-solving rather than step-by-step coding
#### Examples
      Prolog
      Mercury
      Uses
      Artificial Intelligence (AI)
      Expert systems
      Natural Language Processing (NLP)
Robotics
#### Example (Prolog)
     parent(john, mary).

This represents the fact that John is the parent of Mary.
## 3. What is a Translator?
A translator is a system software that converts source code written in a programming language into machine code, allowing the computer to understand and execute the program.
### 1.Why Do We Need a Translator?
Computers understand only machine language (0s and 1s).
Programmers write code in languages like Java, C, and Python.
A translator converts the source code into machine code.
#### Flow
     Programmer → Source Code → Translator → Machine Code → Computer → Output
### 2. Types of Translators
There are three main types of translators:
#### 1. Compiler
A compiler translates the entire source code into machine code at once before execution.
#### Features
      Converts the whole program at once.
      Generates an executable file.
      Faster execution after compilation.
      Reports all errors after compilation.
#### Examples
      C
      C++
      Java (compiles to bytecode using javac)
### 2. Interpreter
An interpreter is a translator that converts and executes a program one line at a time, stopping immediately if an error is encountered.
#### Features
      Translates line by line.
      Stops when an error is found.
      No separate executable file is created.
      Slower execution than a compiler.
#### Examples
      Python
      JavaScript
      Ruby
#### 3. Assembler
An assembler translates assembly language into machine language.
#### Features
      Converts assembly instructions to binary code.
      Used in low-level programming.
      Machine dependent.
#### Example
      MOV A, B
      ADD A, C
### 3. Which Is Faster: Compiler or Interpreter?
A compiler is faster during execution because it translates the entire program before running it. An interpreter is slower because it translates and executes the program line by line.
### 4. What is the difference between a Compiler and an Interpreter?
A compiler translates the entire source code into machine code at once before execution, whereas an interpreter translates and executes the program one line at a time. A compiler generates an executable file and reports all errors after compilation. An interpreter does not generate an executable file and stops execution immediately when it encounters an error. Compiled programs generally execute faster than interpreted programs.
### 5. Which is better compiler or interpreter?
It depends on the requirement. A compiler is preferred when fast execution is important, while an interpreter is preferred when quick testing and debugging are needed.
# Module 3: Problem Solving
## 1. What is a Problem?
A task or challenge that needs a solution.
#### Example:
Find the largest of three numbers.
## 2. Problem Statement
A clear description of what needs to be solved.
## 3. IPO Model
Input → Process → Output
#### Example:
      Input: 10, 20
      Process: Add numbers
      Output: 30
## 4. Breaking Problems into Smaller Steps
Large problems become easier by dividing them into smaller tasks.
## 5. Logical Thinking
Using reasoning to solve problems step by step.
# Module 4: Algorithm
## 1. What is an Algorithm?
An algorithm is a set of step-by-step instructions to solve a problem and produce the desired output.
#### Example:
      Start
      Input two numbers A and B.
      Calculate Sum = A + B.
      Display the sum.
      Stop.
## 2. Why do we need an algorithm?
We need an algorithm to solve problems systematically, reduce errors, and make coding easier.
## 3. What are the characteristics of an algorithm?
Input, Output, Definiteness, Finiteness, and Effectiveness.
## 4. What is the difference between an algorithm and a program?
An algorithm is the plan or solution, while a program is the implementation of that solution using a programming language.
## 5. What is the difference between an algorithm and a flowchart?
An algorithm is written as text, whereas a flowchart represents the same logic using graphical symbols. 
# Module 5: Flowchart
## 1. What is a Flowchart?
A flowchart is a diagram that shows the steps of an algorithm using symbols.
## 2. Why Use Flowcharts?
      Easy to understand.
      Helps plan programs.
      Finds logical mistakes early.
      Improves communication.
## 3. Common Symbols
#### ⭕ Oval → Start/End → Indicates where the flowchart begins or ends.
#### Example:
     (Start)
#### ▭ Rectangle → Process → Represents an operation or processing step.
#### Example:
     Calculate Total = A + B
#### ▱ Parallelogram → Input/Output → Used for accepting input or displaying output.
#### Examples:
     Input A, B
     Display Sum
#### ◇ Diamond → Decision → Represents a condition with two or more possible outcomes.
#### Example:
      Is Age ≥ 18?
             /   \
           Yes    No
#### → Arrow → Flow of control → Connects symbols and shows the direction of execution.
#### Example:
      Start
        ↓
      Input
        ↓
      Process
        ↓
      Output
        ↓
      End
#### ○ Circle → Connector → Connects different parts of a flowchart without drawing long lines.
<img width="292" height="415" alt="image" src="https://github.com/user-attachments/assets/2d47dc84-a73e-4d35-a4db-73b9ac243c8b" /><br>
#### ⬟ Pentagon → Off-Page Connector → Connects the flowchart to another page.
#### Example:
<img width="332" height="415" alt="image" src="https://github.com/user-attachments/assets/61d5ace1-56b2-4732-9a53-aed84cf1e867" /><br>
# Module 6: Pseudocode
## 1. What is Pseudocode?
Pseudocode is an informal way of writing program logic using plain English.
#### Example:
      START
      Read A
      Read B
      Sum = A + B
      Print Sum
      STOP
## 2. Why Use It?
Easier than writing code first.
Independent of any programming language.
Helps organize thoughts.
# Module 7: Program Development Process
## 1. What is Program Development Process?
      Identify the problem.
      Analyze the requirements.
      Design an algorithm.
      Draw a flowchart or write pseudocode.
      Write the program.
      Compile the code (if required).
      Execute the program.
      Test with different inputs.
      Debug errors.
      Maintain and improve the software.
# Module 8: Errors in Programming
## 1. What is an Error?
An error is a mistake that prevents a program from working correctly.
## 2. Types of Errors
There are three main types of errors in programming:
      i. Syntax Errors
      ii. Runtime Errors
      iii. Logical Errors
### 1. Syntax Error
A syntax error occurs when the rules (syntax) of a programming language are violated.

The compiler or interpreter detects these errors before the program runs.
#### Example (Java)
    public class Demo {
        public static void main(String[] args) {
            System.out.println("Hello")   // Missing semicolon
        }
    }
#### Error
     ';' expected
#### Causes
Missing semicolon (;)
Missing braces ({ })
Misspelled keywords
Missing parentheses
### 2. Runtime Error
A runtime error occurs while the program is executing (running).

The program compiles successfully but crashes or throws an exception during execution.
#### Example (Java)
    int a = 10;
    int b = 0;
    System.out.println(a / b);
#### Error
     ArithmeticException: / by zero
#### Other Examples
      Division by zero
      Array index out of bounds
      Null pointer exception
      File not found
## 3. Logical Error
A logical error occurs when the program runs without crashing but produces the wrong output because of incorrect logic.
#### Example (Java)
    int length = 5;
    int width = 4;
    int area = length + width;   // Wrong logic
    System.out.println(area);
    Correct Logic
    int area = length * width;
#### Causes
Wrong formula
Incorrect conditions
Incorrect algorithm
## 3. Debugging
Debugging is the process of finding and fixing errors in a program.

