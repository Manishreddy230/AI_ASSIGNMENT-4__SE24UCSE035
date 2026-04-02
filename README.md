# AI_ASSIGNMENT-4__SE24UCSE035
CODES FOR THE AI ASSIGNMENT 4
# Constraint Satisfaction Problems (CSP) Assignment

This repository contains implementations of classic Constraint Satisfaction Problems (CSP) using Python.  
The problems are solved using the Backtracking algorithm while satisfying all constraints.

---

## Problem 1: Australia Map Coloring

### Description
The Australia map coloring problem treats each state as a variable:
WA, NT, SA, Q, NSW, V, and T.

Each state is assigned a color from a domain (Red, Green, Blue).

### Constraint
No two adjacent states can have the same color.

### Approach
- Represent states and their neighbors using a graph
- Use backtracking to assign colors
- Check constraints before each assignment

### Output
A valid coloring where no neighboring states share the same color.

---

## Problem 2: Telangana Map Coloring

### Description
This problem extends map coloring to the districts of Telangana.

### Constraint
Adjacent districts must have different colors.

### Approach
- Treat each district as a variable
- Define adjacency relationships
- Use backtracking to assign colors

### Output
A valid color assignment for all districts without conflicts.

---

## Problem 3: Sudoku Solver (CSP)

### Description
Sudoku is modeled as a CSP where each cell is a variable with values from 1 to 9.

### Constraints
- No repeated numbers in any row
- No repeated numbers in any column
- No repeated numbers in any 3x3 grid

### Approach
- Use backtracking to fill empty cells
- Validate constraints before placing numbers

### Output
A fully solved Sudoku grid.

---

## Problem 4: Cryptarithmetic Puzzle (TWO + TWO = FOUR)

### Description
Each letter represents a unique digit.

### Constraints
- Each letter maps to a unique digit
- Leading digits cannot be zero
- The arithmetic equation must be correct

### Approach
- Generate permutations of digits
- Map letters to digits
- Check equation validity

### Output
A valid mapping such that:
TWO + TWO = FOUR

---

## Concepts Used

- Constraint Satisfaction Problems (CSP)
- Backtracking Algorithm
- Constraint Checking
- Search Space Exploration

---

## Conclusion

This project demonstrates how CSP techniques can solve map coloring problems, Sudoku puzzles, and cryptarithmetic problems.  
Backtracking efficiently explores possible solutions while satisfying all constraints.

---

## How to Run

python filename.py

---

## Author

Your Name
