# Graphs
Graphs are data structures used to model pairwise relationships between objects. They are composed of vertices (nodes) and edges (connections). <br>
## Types of Graphs
Directed Graphs:<br>
Edges have a direction, meaning they point from one vertex to another.
Example: A → B (indicates a connection from A to B).<br>
Undirected Graphs:<br>
Edges have no direction, meaning the connection is bidirectional.
Example: A — B (A is connected to B, and B is connected to A).<br>
Weighted Graphs:<br>
Each edge has a weight (cost, distance, etc.).
Example: A —(5)— B (The weight of the edge between A and B is 5).<br>

## Graphs Representations
### Adjacency Matrix:
A 2D matrix where matrix[i][j] indicates the presence (and weight, if applicable) of an edge between nodes i and j.<br>
### Adjacency List:
A list where each node stores a list of its adjacent nodes.<br>
### Edge List:
A list of edges, where each edge is represented as a pair (or triplet for weighted graphs).<br>
## Graph Algorithms
**Breadth-First Search (BFS):** Traverses the graph level by level.
**Depth-First Search (DFS):** Explores as far as possible along each branch.
**Dijkstra's Algorithm:** Finds the shortest path in weighted graphs.
**Kruskal's Algorithm:** Finds the Minimum Spanning Tree in a graph.<br>

# Dynamic Programming
**Dynamic Programming** (DP) is an optimization technique used to solve problems by breaking them into overlapping subproblems and building solutions incrementally.<br>
we have the Core Concepts and which are:
Overlapping Subproblems: Problems can be broken down into smaller, repeating subproblems.
Optimal Substructure: The solution to a larger problem can be constructed from solutions to its subproblems.
we also have Techniques used:

Memoization: Store results of solved subproblems in memory to avoid recomputation (Top-Down approach).
Tabulation: Use an iterative approach with a table to build solutions (Bottom-Up approach).

### common problems
Knapsack Problem: Find the maximum profit given weights and values within a weight limit.

Longest Common Subsequence (LCS): Find the longest subsequence common to two strings.

Matrix Chain Multiplication: Minimize the number of scalar multiplications needed to multiply a chain of matrices.

Shortest Path Algorithms: Example: Floyd-Warshall Algorithm for all-pairs shortest paths.



