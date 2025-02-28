# A* Pathfinding Algorithm Visualizer

## Overview
This project is an interactive visualization of the A* (A-star) pathfinding algorithm using Python and Pygame. The algorithm efficiently finds the shortest path between a start and an end point while avoiding obstacles. Users can place obstacles, set start and end points, and visualize the pathfinding process in real time.

## Features
- **Interactive Grid**: Click to place barriers, start, and end points.
- **A* Algorithm Implementation**: Uses Manhattan distance heuristic for optimal pathfinding.
- **Real-time Visualization**: See the algorithm's step-by-step execution.
- **Path Highlighting**: Shows explored nodes and the final shortest path.
- **Reset Functionality**: Clear the grid and restart anytime.

## Technologies Used
- Python
- Pygame
- A* Algorithm
- Heuristic Search
- Graph Traversal
- Data Structures

## How to Run
1. Install Python (>=3.6) if not already installed.
2. Install Pygame:
   ```bash
   pip install pygame
   ```
3. Clone the repository:
   ```bash
   git clone <your-repo-link>
   cd <your-repo-name>
   ```
4. Run the script:
   ```bash
   python main.py
   ```

## How to Use
- **Left Click**:
  - First Click: Set the start node (Orange).
  - Second Click: Set the end node (Turquoise).
  - Subsequent Clicks: Place obstacles (Black).
- **Right Click**:
  - Remove barriers, start, or end nodes.
- **Press `SPACE`**: Start the A* pathfinding algorithm.
- **Press `C`**: Clear the grid.

## Algorithm Explanation
- **A* Algorithm**:
  - Uses **f(n) = g(n) + h(n)**, where:
    - `g(n)`: Cost from start to node `n`.
    - `h(n)`: Estimated cost from `n` to end (Manhattan distance heuristic).
  - Explores the most promising path while keeping track of visited nodes.
  - Ensures optimal and efficient path discovery.

---
Feel free to contribute and improve the project!

