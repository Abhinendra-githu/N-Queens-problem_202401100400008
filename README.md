N-Queens Problem

Overview

The N-Queens problem is a classical combinatorial problem that involves placing N queens on an N×N chessboard so that no two queens attack each other. This means that no two queens should share the same row, column, or diagonal. The problem is often solved using backtracking algorithms.

Features

Implementation of the N-Queens problem.

Uses a backtracking approach to find valid placements of queens.

Visual representation of the chessboard and queen positions.

How to Run


Run the script by executing:

solveNQueens(board, 1, N);

The solution will be displayed as a chessboard with queens placed correctly.

Code Explanation

Backtracking Algorithm: The script places queens row by row and checks for safe positions recursively.

Validation Function: Ensures that no two queens attack each other.
