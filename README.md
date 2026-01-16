# Python Keyword Crossword Puzzle (Overnight Challenge)

This project was developed for a college **Overnight Challenge**. It is a Python-based interactive crossword puzzle game that generates a grid filled with hidden Python keywords and random characters. The objective is to find the hidden keywords within the grid.

## Project Description

The core of this project is a script that dynamically creates a crossword puzzle. It randomly selects Python keywords from a predefined list and places them into a grid of user-defined size. The words can be placed in six different directions:
1.  Left to Right
2.  Top to Bottom
3.  Right to Left
4.  Bottom to Top
5.  Main Diagonal
6.  Off Diagonal

After placing the words, the remaining empty spaces are filled with random alphabets to conceal the potential matches.

## Features

*   **Dynamic Grid Generation**: Users can specify the size of the grid (rows and columns).
*   **Random Word Placement**: Words are chosen randomly and placed in random positions and directions.
*   **Interactive Gameplay**: The game prompts the user to identify words by specifying the keyword, starting coordinates (row and col), and direction.
*   **Score Tracking**: Keeps track of the number of words correctly identified.
*   **Replayability**: Option to restart the game with a new grid.

## How to Run

1.  Ensure you have Python installed with the necessary libraries:
    *   `numpy`
2.  Open the Jupyter Notebook `overnightlmc.ipynb`.
3.  Run all cells to define the functions and start the game loop given in the last cell.
4.  Follow the on-screen prompts:
    *   Enter grid dimensions (e.g., 8 rows, 8 cols).
    *   The console will print the words placed and their directions (for debugging/demonstration) and then the full grid.
    *   You will be asked to find specific keywords. Enter the keyword, starting row index (0-based), starting column index (0-based), and the direction number.

## Game Rules

1.  The grid uses 0-based indexing (Row 0, Column 0 is the top-left).
2.  Direction numbers correspond to:
    1.  Left to Right
    2.  Top to Bottom
    3.  Right To Left
    4.  Bottom to Top
    5.  Main diagonal (Top-Left to Bottom-Right)
    6.  Off diagonal (Top-Right to Bottom-Left)
3.  You have 5 attempts/rounds to find words in each game session.

## Technologies Used

*   **Python**: Core programming language.
*   **NumPy**: Used for grid representation and manipulation.
*   **Random Module**: For random selection of words, positions, and characters.
