# Minimum Spanning Tree (MST) Algorithms in Python

This project implements two popular Minimum Spanning Tree algorithms:

- Kruskal's Algorithm
- Prim's Algorithm

Both algorithms are implemented in Python and tested on the same weighted undirected graph.

## Features

- Kruskal's Algorithm using Union-Find (Disjoint Set)
- Path Compression
- Union by Rank
- Prim's Algorithm using Min Heap (Priority Queue)
- Prints MST edges and total cost

## Algorithms

### Kruskal's Algorithm

- Sorts edges by weight.
- Uses Union-Find to avoid cycles.
- Time Complexity: **O(E log E)**

### Prim's Algorithm

- Uses a Priority Queue (Min Heap).
- Expands the MST one vertex at a time.
- Time Complexity: **O((V + E) log V)**

## Graph Used

Vertices: **7**

Weighted Edges:

```
0 --7-- 1
|       |\
5       8 7
|       |  \
3       2---4
| \     |   |
6  15   5   9
|    \  |   |
5------4----6
```

## Output

### Kruskal's MST

```
Edge (0 - 3) Weight: 5
Edge (2 - 4) Weight: 5
Edge (3 - 5) Weight: 6
Edge (0 - 1) Weight: 7
Edge (1 - 4) Weight: 7
Edge (4 - 6) Weight: 9

Total MST Cost: 39
```

### Prim's MST

```
Edge (0 - 3) Weight: 5
Edge (3 - 5) Weight: 6
Edge (0 - 1) Weight: 7
Edge (1 - 4) Weight: 7
Edge (4 - 2) Weight: 5
Edge (4 - 6) Weight: 9

Total MST Cost: 39
```

## Run

```bash
mst_algorithms.py
```

## Concepts Used

- Graph Theory
- Greedy Algorithms
- Minimum Spanning Tree
- Union-Find (Disjoint Set)
- Path Compression
- Union by Rank
- Priority Queue (heapq)

## Author

Harshitha B
