# Python Compiler

**Author:** Deepanshu (210310)  
**Contributors:**  
- Ujjwal Gautam (211122)  
- Nirmal Prajapati (210735)  

## Project Overview

This project is a Python compiler that converts Python code into x86 assembly language. The compiler supports essential features such as primitive data types, loops, functions, and basic object-oriented programming constructs.

### Features
- Primitive Data Types: `int`, `bool`, `str`
- Arithmetic, Relational, Logical, and Bitwise operations
- Static 1D Lists with `len()` functionality
- Class definitions, Constructors, Methods
- Loop constructs, including `for`, `while`, and branching (`if-else`)
- Functions and recursion support
- Output: `output.s` file containing x86 assembly code

### Instructions for Running

1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd <repository-folder>
    ```

2. Compile the project:
    ```bash
    cd src
    make
    ```

3. To compile a Python file, use:
    ```bash
    ./final --input <file.py>
    ```

4. For additional options:
    ```bash
    ./final --help
    ```

### Contents

- `src/`: Source code including `lexer.l`, `parser.y`, `makefile`, etc.
- `tests/`: Test cases (`test1.py` to `test5.py`)
- `outputs/`: Compiler output files
- `doc/`: Documentation
