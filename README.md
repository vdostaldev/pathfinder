# Pathfinder

An interactive pathfinding visualizer in a single HTML file: no build step, no dependencies.

Open `index.html` in a browser.

## Algorithms

| Algorithm | Uses weights | Finds the cheapest path |
|---|---|---|
| A* (Manhattan heuristic) | yes | yes |
| Dijkstra | yes | yes |
| Greedy best-first | no (only distance to the target) | no |
| Breadth-first | no | fewest steps only |
| Depth-first | no | no |

Each algorithm is a generator that yields `visit` and `frontier` events, so the same code can run animated (a few steps per frame) or instantly to the end.

## Using it

- **Draw**: drag on the grid with the Wall, Weight (costs ×5) or Erase brush.
- **Move start and end**: drag the green ● or the red ◎.
- **Live mode**: after a run finishes, editing the board, moving a marker or switching algorithm recomputes the result instantly.
- **Generate**: Maze is a recursive backtracker with some walls knocked out so there are loops. Scatter places random walls and weights.
- **Keys**: `Space` run/stop · `M` maze · `S` scatter · `C` clear.
