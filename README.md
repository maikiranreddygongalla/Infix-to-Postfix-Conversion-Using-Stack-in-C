# Infix to Postfix Conversion Using Stack in C

## Project Description
This project implements an **Infix to Postfix Expression Conversion** using the Stack Data Structure in C programming.

It converts mathematical expressions from infix notation into postfix notation based on operator precedence and associativity. A stack is used to temporarily store operators and parentheses during the conversion process.

## Objectives
- Understand the Stack Data Structure.
- Implement Push, Pop, and Peek operations.
- Convert infix expressions into postfix expressions.
- Understand operator precedence and associativity.
- Handle parentheses and brackets.
- Improve problem-solving and logical thinking skills.

## Technologies Used
- Programming Language: C
- Compiler: GCC
- Platform: Linux / Windows
- Data Structure: Stack

## Operators Supported

| Operator | Description | Precedence |
|---|---|---|
| `^` | Exponentiation | 3 |
| `*` | Multiplication | 2 |
| `/` | Division | 2 |
| `%` | Modulus | 2 |
| `+` | Addition | 1 |
| `-` | Subtraction | 1 |

## Features
- Stack implementation using an array.
- Operator precedence handling.
- Supports parentheses `()` and brackets `[]`.
- Ignores whitespace characters.
- Checks invalid characters and unmatched brackets.
- Converts infix expressions into postfix notation.

## Example

**Input:**
```text
A+B*C
```

**Output:**
```text
ABC*+
```

Another example:

**Input:**
```text
(A+B)*C
```

**Output:**
```text
AB+C*
```

## Stack Operations
1. Push – Inserts an element into the stack.
2. Pop – Removes the top element from the stack.
3. Peek – Returns the top element without removing it.
4. Precedence – Determines operator priority.

## How to Compile and Run

Compile using GCC:

```bash
gcc infix_to_postfix.c 
```

Run the program:

```bash
./a.out
```

## Concepts Covered
- Stack Data Structure
- Arrays
- Functions
- Strings
- Character Handling
- Operator Precedence
- Conditional Statements
- Loops

## Applications
- Expression evaluation.
- Compiler design.
- Mathematical expression processing.
- Syntax analysis.

## Author
**Gongalla Maikiran Reddy**

## Conclusion
This project demonstrates the practical implementation of a Stack Data Structure in C and helps understand how mathematical expressions are converted from infix notation to postfix notation.
