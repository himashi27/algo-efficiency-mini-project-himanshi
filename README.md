💻 Lab Assignment 3 — Graph Algorithms in Real-Life Applications

🧠 Overview

This project demonstrates how fundamental graph algorithms power real-world systems — from social networks and navigation to disaster response and infrastructure optimization.

It implements and analyzes four classical algorithms — BFS / DFS, Bellman-Ford, Dijkstra, and MST (Prim’s / Kruskal’s) — to solve practical, real-life problems through efficient Python implementations, profiling, and visualization.

📊 Problem Summary
| 🧩 **Problem**                       | ⚙️ **Algorithm**         | ⏱ **Time Complexity** | 🌍 **Application Domain**   | 🎯 **Objective**                                   |
| ------------------------------------ | ------------------------ | --------------------- | --------------------------- | -------------------------------------------------- |
| **Social Network Friend Suggestion** | BFS / DFS                | O(V + E)              | Social Media                | Suggest mutual friends                             |
| **Google Maps Route Finder**         | Bellman-Ford             | O(V × E)              | Navigation Systems          | Compute shortest routes (handles negative weights) |
| **Emergency Response System**        | Dijkstra’s               | O(E log V)            | Disaster Management         | Find fastest routes in positive-weighted maps      |
| **Network Cable Installation**       | MST (Prim’s / Kruskal’s) | O(E log V)            | Infrastructure & Networking | Minimum cost to connect all nodes                  |

⚙️ Implementation Details

Each problem includes:

Graph Modeling: Adjacency-list / edge-list representation.

Algorithm Design: Clean, efficient Python logic using standard data structures.

Profiling: Execution-time and memory tracking with time and memory_profiler.

Visualization: Optional matplotlib plots (execution time vs nodes/edges).

Analysis: Complexity and scalability discussion for each algorithm.

💭 Reflections

🔹 Real-World Context Influence

Each application domain naturally maps to a specific algorithm:

🧑‍🤝‍🧑 Social Media → mutual connections → BFS / DFS

🗺️ Navigation Systems → possible negative routes → Bellman-Ford

🚑 Disaster Routing → positive travel times → Dijkstra

🏗️ Infrastructure Design → minimal connection cost → MST

🔹 Performance Profiling

Empirical results align with theoretical complexities:

| Algorithm              | Growth Trend    | Observation                                    |
| ---------------------- | --------------- | ---------------------------------------------- |
| **BFS / DFS**          | Linear O(V + E) | Scales efficiently with network size           |
| **Bellman-Ford**       | Linear in E × V | Handles negative weights safely                |
| **Dijkstra**           | O(E log V)      | Very fast for sparse, positive-weighted graphs |
| **MST (Prim/Kruskal)** | O(E log V)      | Efficient for infrastructure optimization      |

📚 References & Acknowledgments

📖 Cormen, Leiserson, Rivest & Stein (CLRS) – Introduction to Algorithms

🐍 Python Docs: https://docs.python.org/3/

💡 Learning Resources: GeeksforGeeks | TutorialsPoint

🧰 Tools Used:

memory_profiler – runtime memory tracking

matplotlib – data visualization

time – execution profiling

👩‍🏫 Faculty Guidance: Dr. Aarti Sangwan, Department of SOET, K.R. Mangalam University

🧾 Project Metadata
| Field          | Detail                                                        |
| -------------- | ------------------------------------------------------------- |
| **Course**     | ENCA 351 — Design and Analysis of Algorithms Lab              |
| **Assignment** | Lab Assignment 3 — Graph Algorithms in Real-Life Applications |
| **Author**     | 👩‍💻 **Himanshi**                                            |
| **Date**       | 📅 12 November 2025                                           |

