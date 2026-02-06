# Depth first search (DFS) Java implementation

This project is a simple Java implementation of the Depth first search(DFS) algorithm using an adjacency matrix to represent a directed graph.
The goal of the project is to demonstrate how DFS works internally, including graph creation, node traversal, and recursive exploration of connected nodes.

## Features
- Graph representation using an adjacency matrix
- Custom `Node` class to store node data
- Ability to add nodes and directed edges
- Console visualization of the adjacency matrix
- Recursive Depth first search traversal
- Tracks visited nodes to prevent infinite loops

## How Depth first search works
Depth first search explores a graph by:
1. Starting from a selected source node
2. Visiting the node and marking it as visited
3. Recursively visiting the first unvisited adjacent node
4. Continuing until all reachable nodes are visited
5. Backtracking when no unvisited neighbors remain

This implementation uses recursion and a `boolean[] visited` array.

## Technologies used
- Java SE
- Object oriented programming(OOP)
- Recursion
- Data Structures(Graph, Adjacency Matrix)

## Purpose
This project is intended for:
- Learning graph data structures
- Understanding DFS traversal
- Practicing recursion in Java
- Academic and educational use
