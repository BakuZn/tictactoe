This is a simple Tic-Tac-Toe game implemented in Python using the Pygame library. The game allows a human player ('O') to play against an AI ('X') that uses the Minimax algorithm to make optimal moves.

Features:

Graphical User Interface (GUI): Uses Pygame to create an interactive game board.

AI Opponent: The AI ('X') uses the Minimax algorithm for optimal gameplay.

Player vs AI Mode: The player ('O') takes turns with the AI ('X').

Winner Detection: The game checks for a winner after each move.

Hover Effect: Tiles highlight when hovered over with the mouse.

Installation

Ensure you have Python installed on your system. Then, install Pygame using pip:

pip install pygame

How to Play

Run the script using:

python tic_tac_toe.py

The game window will open, displaying a 3x3 grid.

The player ('O') can click on an empty tile to make a move.

The AI ('X') will automatically make its move.

The game will announce the winner once a player wins.

Game Rules:

The game is played on a 3x3 grid.

Players take turns placing their marks ('X' or 'O') on empty tiles.

The first player to align three marks horizontally, vertically, or diagonally wins.

If all tiles are filled without a winner, the game ends in a draw.

Minimax Algorithm:

The AI ('X') uses the Minimax algorithm to evaluate the best possible move:

It checks for winning or blocking moves.

It recursively explores all possible moves and chooses the one with the highest score.

The AI plays optimally and will either win or force a draw if played correctly.
