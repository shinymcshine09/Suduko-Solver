# Sudoku Solver

A simple Sudoku solver that efficiently finds solutions to a given Sudoku puzzle.

## Features

- 🧩 Solves **9x9 Sudoku puzzles** using a backtracking algorithm.
- 📥 Supports **user input puzzles** in a text-based format.
- 🖥️ Outputs the solved Sudoku grid to the console.
- 🚀 Written in **HTML/JavaScript/CSS**.

## Installation

Clone this repository:

```bash
git clone https://github.com/shinymcshine09/sudoku-solver.git
cd sudoku-solver
```

## Usage

Simply open sudoku.html in your browser:

1.	Open sudoku.html in any modern web browser (Chrome, Firefox, Edge, etc.).
2.	Enter a Sudoku puzzle in the provided grid.
3.	Click the Solve button to generate the solution.
4.	Reset or edit the grid to try another puzzle.

## How It Works

The solver uses backtracking to find a valid solution by:
	1.	Identifying an empty cell.
	2.	Trying numbers 1-9 while ensuring Sudoku rules are met.
	3.	Recursively solving the puzzle, backtracking if necessary.
	4.	Displaying the completed grid once solved.

## Contributing

Contributions are welcome! Feel free to submit issues or open a pull request to improve the solver.

## License

This project is licensed under the MIT License – see the LICENSE file for details.
