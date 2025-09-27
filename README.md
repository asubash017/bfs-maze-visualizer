# BFS Maze Visualizer with Python Curses

This is a simple **BFS (Breadth-First Search) pathfinding visualizer** implemented in Python using the `curses` module.  
It shows how BFS explores multiple paths simultaneously in a maze and finds the shortest path from the start (`O`) to the end (`X`).

## Features
- Visualizes BFS queue exploration in real-time.
- Marks visited cells and the path found.
- Supports mazes with multiple branching paths.
- Works in terminal/console using `curses`.

## Maze Legend
- `#` : Wall  
- `O` : Start position  
- `X` : End position  
- `*` : Path taken (can be customized)  
- `o` : Optional (frontier/queue cells, if implemented)

## How to Run
1. Make sure you have **Python 3** installed.
2. Install dependencies (see `requirements.txt`).
3. Run the program in your terminal:

```bash
python maze_bfs_curses.py
