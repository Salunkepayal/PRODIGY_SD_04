
* This Java program solves a 9x9 Sudoku puzzle using a backtracking algorithm.

* Key Features:
1.Input: A partially filled Sudoku board (0 represents empty cells).
2.Output: The solved Sudoku board (if solvable), or a message saying it cannot be solved.
# How it Works:
* solveBoard():
Tries placing numbers 1–9 in each empty cell.
Recursively solves the puzzle using backtracking.
If a placement leads to a dead end, it resets the cell to 0 and tries the next number.
* isValidPlacement():
1.Checks if a number can be legally placed in a cell based on Sudoku rules:
Not in the same row
Not in the same column
Not in the same 3x3 sub-grid
* printBoard():
Nicely prints the board with visual separation for 3x3 boxes.
