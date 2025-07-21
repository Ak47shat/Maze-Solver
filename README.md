# Maze Solver Visualizer

This project is an interactive pathfinding visualizer built with Python and Pygame. It demonstrates and compares two classic algorithms—A* Search and Dijkstra's Algorithm—for solving mazes and finding the shortest path between two points.

## Features
- **A* Pathfinding Algorithm:** Visualizes the heuristic-based A* search for efficient shortest path discovery.
- **Dijkstra's Algorithm:** Visualizes the classic uniform-cost search for shortest path finding.
- **Interactive Grid:** Users can draw barriers, set start/end points, and watch the algorithms in action.
- **Color-coded Visualization:** Different colors represent open/closed nodes, barriers, start/end points, and the final path.

## How to Run
1. **Install dependencies:**
   ```bash
   pip install pygame
   ```
2. **Run A* Visualizer:**
   ```bash
   python astar.py
   ```
3. **Run Dijkstra Visualizer:**
   ```bash
   python DIJKSTRA.py
   ```

## Controls
- **Left Click:** Draw barriers, set start and end points
- **Right Click:** Remove barriers or reset nodes
- **Spacebar:** Start the algorithm
- **C:** Clear the grid

## Requirements
- Python 3.x
- pygame

## Project Structure
- `astar.py` — A* pathfinding visualizer
- `DIJKSTRA.py` — Dijkstra's algorithm visualizer


## License
This project is for educational and demonstration purposes.
