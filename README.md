# Sudoku Solver using AC3 arc consistency and BTS backtrack search

BTS is used with MRV (Minimum remaining value) to determine which nodes to expand first.
Some boards can be solved using only AC3 without needing BTS. The algorithm will show if that happened.
This notebook also prints the time needed to completely solve the board. It can solve any sudoku board in under 1 second (given that the board is correct and doesn't have any errors).
