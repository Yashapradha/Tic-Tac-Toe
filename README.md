# OX Game

This project is an OX (Tic-Tac-Toe) game implemented in Python. The game allows two players to take turns marking spaces in a 3×3 grid with their respective symbols (O and X). The player who succeeds in placing three of their symbols in a horizontal, vertical, or diagonal row wins the game.

## Features

- Two-player mode
- Simple text-based interface
- Detection of win conditions
- Detection of draw conditions

## Technologies Used

- **Python**: The programming language used to implement the game logic and interface.

## Setup and Usage

1. **Clone the repository or download the ZIP file.**
    ```bash
    git clone https://github.com/yourusername/ox-game.git
    ```

2. **Navigate to the project directory.**
    ```bash
    cd ox-game
    ```

3. **Run the game.**
    ```bash
    python ox_game.py
    ```

## How to Play

1. The game starts with Player 1 (O) and Player 2 (X) taking turns.
2. On your turn, enter the number corresponding to the cell where you want to place your symbol.
3. The grid cells are numbered 1 to 9 as follows:

    ```
     1 | 2 | 3
    -----------
     4 | 5 | 6
    -----------
     7 | 8 | 9
    ```

4. The game checks for a winner or a draw after each move.
5. The game ends when a player gets three of their symbols in a row (horizontally, vertically, or diagonally) or when all cells are filled without any player winning (draw).
