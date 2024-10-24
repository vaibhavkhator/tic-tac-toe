# tic-tac-toe
tic tac toe using tkinter


# Tic Tac Toe Game

A simple Tic Tac Toe game implemented using Python's `tkinter` library. This project demonstrates a basic graphical user interface (GUI) application for playing Tic Tac Toe, where two players take turns marking X's and O's on a 3x3 grid. The game detects when a player wins or if it ends in a draw.

## Features

- Two-player game with alternating turns between X and O.
- Checks for winning conditions (horizontal, vertical, and diagonal).
- Detects a draw when all cells are filled with no winner.
- Displays a message when a player wins or the game ends in a draw.
- Automatically resets the game after a win or draw.

## Prerequisites

- Python 3.x installed on your machine.
- `tkinter` library (usually comes pre-installed with Python).

## How to Run the Game

1. Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
2. Save the provided code in a file named `tic_tac_toe.py`.
3. Open a terminal or command prompt and navigate to the directory containing `tic_tac_toe.py`.
4. Run the game by executing: python tic_tac_toe.py

## Game Instructions

1. The game starts with player X.
2. Players take turns clicking on the empty cells to mark their symbol (X or O).
3. The game checks for a winner after each turn:
- A player wins if they successfully mark three consecutive cells horizontally, vertically, or diagonally.
- If all cells are filled and no player has won, the game ends in a draw.
4. The game resets automatically after a win or draw.

## Code Overview

- The game uses a 3x3 grid of buttons created with `tkinter.Button` widgets.
- `current_player` keeps track of whose turn it is (X or O).
- The `check_winner` function checks if a player has won by comparing button text values.
- The `check_draw` function checks if all cells are filled.
- The `on_button_click` function handles the button click events to update the game state and check for win/draw conditions.
- The `reset_game` function clears the board for a new game.

## License

This project is open-source and available for use under the MIT License.

## Acknowledgements

- Built using the `tkinter` library in Python for GUI programming.
- Inspired by the classic Tic Tac Toe game played on paper.
