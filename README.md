# <h1 align="center">🔤 LC-3 Character Counter 🔤</h1>

## Description

This project is an LC-3 Assembly Language application that analyzes a user's full name and displays the frequency of each letter that appears in the input.

The program accepts alphabetic characters, ignores spaces, and reports an error if invalid characters are entered. All lowercase letters are converted to uppercase before counting, ensuring that uppercase and lowercase letters are treated equally.

This project was developed as part of an Assembly Language course and demonstrates fundamental LC-3 programming concepts, including memory management, stack usage, subroutines, branching, loops, pointers, and ASCII conversion.

---

## Features

* Accepts uppercase and lowercase letters.
* Ignores spaces in the input.
* Detects and rejects invalid characters.
* Counts occurrences of letters A-Z.
* Displays only letters that appear in the input.
* Uses multiple subroutines and register save/restore techniques.

---

## Project Goals

The objective of this project was to practice low-level programming concepts through the implementation of a complete LC-3 application. Major goals included:

* Developing modular programs using subroutines.
* Implementing stack operations and register preservation.
* Using arrays and pointers to manage memory.
* Performing character validation and ASCII manipulation.
* Applying branching and loop structures.
* Processing and displaying data through LC-3 system calls.

---

## Program Flow

1. Prompt the user to enter their full name.
2. Store the input in memory.
3. Validate each character.
4. Ignore spaces and convert lowercase letters to uppercase.
5. Count the frequency of each letter.
6. Display the resulting counts.
7. Terminate the program.

---

## How to Run

### Requirements

* LC3Edit
* LC3Sim

### Instructions

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Open the `FinalProject.asm` source file in **LC3Edit**.

3. Assemble the program.

4. Launch **LC3Sim**.

5. Load the generated object file.

6. Set the PC to the program starting address (`x3000`) if necessary.

7. Run the program and enter a full name when prompted.

---

## Example

### Input

```text
John Doe
```

### Output

```text
Count of D is 1
Count of E is 1
Count of H is 1
Count of J is 1
Count of N is 1
Count of O is 2
```

---

## Concepts Demonstrated

* LC-3 Assembly Language
* Arrays and Buffers
* Stack Management
* Register Save Area (RSA)
* Subroutines
* Branching and Iteration
* ASCII Character Manipulation
* Input and Output System Calls
* Memory Allocation

---

## Contributors

* Keanu Arao
* Justin Sweers
* Suleny Perez

---

## Course Information

**Course:** CIS 11: Computer Organization and Assembly Language
**Architecture:** LC-3
**Language:** LC-3 Assembly
