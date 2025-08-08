# Zero-Kata: Tic-Tac-Toe Game

## Overview

Zero-Kata is a simple single-player Tic-Tac-Toe game built using Python's Tkinter library. The player (using 'X') competes against a computer opponent (using 'O') that makes random moves. The game features a 3x3 grid, a reset button to start a new game, and a display for win/loss messages.

# Features





Interactive GUI: A 3x3 grid of buttons for gameplay, built with Tkinter.



Single-Player Mode: Play as 'X' against a computer that randomly selects 'O' moves.



Win Detection: Automatically checks for win conditions (rows, columns, diagonals) after each move.



Reset Functionality: A "Start Again" button to reset the board and start a new game.



Responsive Design: Fixed window size (381x500 pixels) with non-resizable window for consistent experience.

## Installation

To run Zero-Kata, you need Python installed with the Tkinter library (included by default in standard Python installations).




Navigate to the project directory:

cd zero-kata



### Ensure Python is installed: Verify Python 3 is installed by running:

python3 --version

### Tkinter is typically included, but you can confirm by running:

python3 -m tkinter

### If Tkinter is missing, install it (e.g., on Ubuntu):

sudo apt-get install python3-tk

Usage





### Run the game by executing the main script:

python3 zero_kata.py



The game window will open, displaying a 3x3 grid.



## Click any empty cell to place an 'X'. The computer will respond by placing an 'O' in a random empty cell.



The game checks for a win or loss after each move:





If you align three 'X's (row, column, or diagonal), "You Won!" is displayed.



If the computer aligns three 'O's, "You Lost." is displayed.



All buttons are disabled upon a win or loss.



Click the "Start Again" button to reset the board and play a new game.

Contributing

Contributions are welcome! To contribute:





# Fork the repository.


Create a new branch: git checkout -b feature-name



Make your changes and commit: git commit -m "Add feature-name"



Push to the branch: git push origin feature-name



## Open a pull request.

Please ensure your changes are well-documented and tested before submitting.

# License

This project is licensed under the MIT License - see the LICENSE file for details.

# Contact

For questions or feedback, please open an issue on the repository.
