Lab Assignment 3 —  Graph Algorithms in Real-Life Applications

🧠Overview

This project demonstrates the use of fundamental graph algorithms in real-world contexts, including social networks, navigation systems, disaster response, and infrastructure optimization.

It implements and analyzes four classical graph algorithms — BFS/DFS, Bellman-Ford, Dijkstra, and MST — to solve practical, real-life problems.

| **Problem**                      | **Algorithm**            | **Time Complexity** | **Real-World Application**  | **Objective**                                      |
| -------------------------------- | ------------------------ | ------------------- | --------------------------- | -------------------------------------------------- |
| Social Network Friend Suggestion | BFS / DFS                | O(V + E)            | Social Media                | Suggest mutual friends                             |
| Google Maps Route Finder         | Bellman-Ford             | O(V × E)            | Navigation Systems          | Compute shortest routes (handles negative weights) |
| Emergency Response System        | Dijkstra’s               | O(E log V)          | Disaster Management         | Find fastest routes in positive-weight maps        |
| Network Cable Installation       | MST (Prim’s / Kruskal’s) | O(E log V)          | Infrastructure & Networking | Minimum cost to connect all nodes                  |

⚙️Implementation Details

Each problem includes:

Graph Modeling: Representation using adjacency lists or edge lists.

Algorithm Design: Efficient implementation using core Python data structures.

Profiling: Time and memory usage measurement using time and memory_profiler.

Visualization: Optional plots using matplotlib for time vs. nodes/edges.

Analysis: Complexity discussion and scalability commentary.

💭Reflections

Real-World Contexts Influence Algorithm Choice:
Each domain’s requirements directly map to the algorithm’s characteristics:

Social media → mutual links → BFS/DFS

Navigation with negative roads → Bellman-Ford

Disaster routing → positive weights → Dijkstra

Infrastructure → minimal cost connection → MST

Performance Profiling:
Execution times align with theoretical complexities:

BFS/DFS → Linear with V + E

Bellman-Ford → Increases linearly with E × V

Dijkstra → Faster for sparse graphs

MST → Efficient with min-heaps (O(E log V))

📚References & Acknowledgments

Textbook: Introduction to Algorithms by Cormen, Leiserson, Rivest, and Stein (CLRS)

Python Docs: https://docs.python.org/3/

Graph Concepts: GeeksforGeeks, TutorialsPoint

Tools Used:

memory_profiler – runtime memory tracking

matplotlib – visualizations

time module – performance profiling

Faculty Guidance: Dr. Aarti Sangwan, Department of SOET, K.R. Mangalam University

Course: ENCA351 — Lab Assignment 3
Project: Graph Algorithms in Real-Life Applications
Author: Himanshi 
Date: 12 November 2025
