# ADA Lab Programs

A collection of Algorithm Design and Analysis (ADA) lab programs implemented in C.

## Programs

| Program | Algorithm | Category |
|---------|-----------|----------|
| [Program 1](PROGRAM%201.txt) | Kruskal's Algorithm | Greedy – Minimum Spanning Tree |
| [Program 2](PROGRAM%202.txt) | Prim's Algorithm | Greedy – Minimum Spanning Tree |
| [Program 3A](PROGRAM%203A.txt) | Floyd's Algorithm | Dynamic Programming – All-Pairs Shortest Path |
| [Program 3B](PROGRAM%203B.txt) | Warshall's Algorithm | Dynamic Programming – Transitive Closure |
| [Program 4](PROGRAM%204.txt) | Dijkstra's Algorithm | Greedy – Single-Source Shortest Path |
| [Program 5](PROGRAM%205.txt) | Topological Sort | Graph Algorithms |
| [Program 6](PROGRAM%206.txt) | 0/1 Knapsack Problem | Recursive / Backtracking |
| [Program 7](PROGRAM%207.txt) | Fractional Knapsack Problem | Greedy |
| [Program 8](PROGRAM%208.txt) | Sum of Subsets | Backtracking |
| [Program 9](PROGRAM%209.txt) | Selection Sort | Sorting |
| [Program 10](PROGRAM%2010.txt) | Quick Sort | Divide and Conquer – Sorting |
| [Program 11](PROGRAM%2011.txt) | Merge Sort | Divide and Conquer – Sorting |
| [Program 12](PROGRAM%2012.txt) | N-Queens Problem | Backtracking |

## Descriptions

### Program 1 – Kruskal's Algorithm
Finds the Minimum Spanning Tree (MST) of a weighted undirected graph by sorting edges and using a Union-Find data structure to avoid cycles.

### Program 2 – Prim's Algorithm
Builds the Minimum Spanning Tree by greedily adding the lowest-cost edge that connects a visited vertex to an unvisited vertex.

### Program 3A – Floyd's Algorithm
Computes shortest paths between all pairs of vertices in a weighted graph using dynamic programming (Floyd-Warshall).

### Program 3B – Warshall's Algorithm
Determines the transitive closure of a directed graph — whether a path exists between every pair of vertices.

### Program 4 – Dijkstra's Algorithm
Finds the shortest path from a single source vertex to all other vertices in a weighted graph.

### Program 5 – Topological Sort
Produces a linear ordering of vertices in a Directed Acyclic Graph (DAG) such that for every directed edge u → v, u comes before v.

### Program 6 – 0/1 Knapsack Problem
Solves the 0/1 Knapsack problem recursively: each item is either included or excluded to maximize profit without exceeding the capacity.

### Program 7 – Fractional Knapsack Problem
Solves the Fractional Knapsack problem greedily by selecting items in decreasing order of profit-to-weight ratio, allowing fractions of items.

### Program 8 – Sum of Subsets
Uses backtracking to find all subsets of a given set whose elements sum to a specified target value.

### Program 9 – Selection Sort
Sorts an array by repeatedly finding the minimum element and placing it in the correct position. Counts basic operations performed.

### Program 10 – Quick Sort
Sorts an array using the divide-and-conquer Quick Sort algorithm with a partition step. Counts basic operations performed.

### Program 11 – Merge Sort
Sorts an array using the divide-and-conquer Merge Sort algorithm. Counts basic operations (comparisons) performed.

### Program 12 – N-Queens Problem
Uses backtracking to place N queens on an N×N chessboard so that no two queens attack each other, printing all valid solutions.

## How to Compile and Run

Each program is a standalone C source file. To compile and run any program:

```bash
gcc -o program <PROGRAM_FILE.txt> && ./program
```

**Example:**
```bash
gcc -o prog1 "PROGRAM 1.txt" && ./prog1
```
