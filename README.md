# Sudoku Solver 

This is a Sudoku Solver built in Python as part of my SkillCraft Technology Internship – Task 3.
The program uses a backtracking algorithm to solve any valid Sudoku puzzle automatically.

## Features

Takes a Sudoku grid as input (with 0 representing empty cells).

Uses a backtracking algorithm to fill in the missing numbers.

Prints both the unsolved puzzle and the solved puzzle.

Handles any valid 9x9 Sudoku puzzle.

## How It Works

The program scans the Sudoku grid for empty cells (0).

It tries placing numbers 1–9 in each empty cell.

For each placement, it checks if the number is valid:

Not repeated in the row

Not repeated in the column

Not repeated in the 3x3 subgrid

If valid, it continues to the next empty cell.

If no valid number is found, it backtracks and tries a different number.

## Output

Unsolved Sudoku:
5 3 . . 7 . . . .
6 . . 1 9 5 . . .
. 9 8 . . . . 6 .
8 . . . 6 . . . 3
4 . . 8 . 3 . . 1
7 . . . 2 . . . 6
. 6 . . . . 2 8 .
. . . 4 1 9 . . 5
. . . . 8 . . 7 9

Solved Sudoku:
5 3 4 6 7 8 9 1 2
6 7 2 1 9 5 3 4 8
1 9 8 3 4 2 5 6 7
8 5 9 7 6 1 4 2 3
4 2 6 8 5 3 7 9 1
7 1 3 9 2 4 8 5 6
9 6 1 5 3 7 2 8 4
2 8 7 4 1 9 6 3 5
3 4 5 2 8 6 1 7 9


The process continues until the Sudoku is solved.
