# Pathfinding Visualizer

A small web page that shows how different pathfinding algorithms search a grid.

Open `index.html` in a browser. No install needed.

## Algorithms

- BFS (breadth-first search)
- DFS (depth-first search)
- Dijkstra
- A* (Manhattan distance heuristic)
- Greedy best-first search

## How to use

- Click and drag on the grid to draw walls, or weights (cost 5) if Draw is set to Weights.
- Drag the green square (start) and the red square (end) to move them.
- Press **Visualize** to watch the search step by step.
- **Generate maze** makes a random maze.
- After a search finishes, moving start/end or changing the algorithm updates the result right away.

Light blue cells are the frontier (cells waiting to be explored), darker blue cells have been visited, and yellow is the final path.
