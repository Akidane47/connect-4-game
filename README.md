Connect 4 Game

Overview

This is a simple implementation of the classic Connect 4 game using Python and Pygame. The game can be played by two players taking turns to drop pieces into a 6-row by 7-column grid. The objective is to connect four of your pieces in a row, column, or diagonally before your opponent does.

Features

Two-player mode (local multiplayer)

Graphical user interface using Pygame

Animations for dropping pieces

Winning detection for horizontal, vertical, and diagonal connections

Restart functionality

Requirements

Make sure you have Python installed (version 3.x recommended). You will also need to install Pygame.

Install Dependencies

Run the following command to install Pygame:

pip install pygame

How to Play

Run the game script using Python:

python connect4.py

Players take turns clicking on a column to drop their piece.

The game checks for a win condition after each move.

If a player connects four pieces in a row (horizontally, vertically, or diagonally), they win!

The game allows for restarting after a match.
