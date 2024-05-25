Overview

The Snake Game with A* Pathfinding is a simple implementation of the classic Snake game with an added feature of an A* pathfinding algorithm. The snake navigates through a grid-based environment, avoiding blocked cells, and the user can set the destination for the snake to reach using a mouse click. The A* algorithm calculates the shortest path from the current snake position to the destination, and the snake moves accordingly

User Guide

Run the Python script.
The snake starts moving automatically.
Click the left mouse button to set the destination for the snake.
The snake will find the shortest path using the A* algorithm and move towards the destination.
The game window can be closed by clicking the close button.

Implementation Details

Snake Movement: The snake moves automatically, and its direction can be changed when the user sets a new destination.
A Pathfinding Algorithm:* The A* algorithm calculates the shortest path from the snake's current position to the destination, considering blocked cells.
Blocked Cells: Certain cells in the grid are marked as blocked, and the snake avoids these cells.
Mouse Click Event: The user can set the destination by clicking the left mouse button.
