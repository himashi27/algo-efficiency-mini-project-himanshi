# Delivery Route Optimization

## Overview
This project optimizes delivery routes considering:
- Distance between locations
- Vehicle capacity constraints
- Parcel value and weight
- Customer time windows

It implements multiple strategies:
- **Greedy Parcel Selection** for maximizing value-to-weight ratio
- **Dynamic Programming** for delivery feasibility within time windows
- **Dijkstra's Algorithm** for shortest paths
- **Prim’s Minimum Spanning Tree (MST)** for route estimation
- **Traveling Salesman Problem (TSP)** using brute-force and dynamic programming

## Requirements
```bash
pip install networkx matplotlib memory_profiler
