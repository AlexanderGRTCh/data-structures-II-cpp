# Data Structures II – C++ Project Collection

This repository contains 8 core C++ assignments completed for a Data Structures II course. Each project is implemented with practical focus, demonstrating proficiency in advanced data structures, algorithm design, and object-oriented programming. Test drivers are included to demonstrate usage and expected output.

## Assignment Overview

### 1. AVL Tree
- Self-balancing binary search tree with rotation logic (LL, RR, LR, RL).
- Features: insert, delete, height, level-order, diameter, nodes in range.
- File: `AVLTree.h`, `TesterTemp.cpp`

### 2. Binary Search Tree (BST)
- Classic BST supporting insertion, deletion, traversal, and range queries.
- Includes closest common ancestor, level-order, and validation.
- File: `theBST.h`, `testBST.cpp`, `Notes.h`

### 3. Graph-Based Movie Recommendation Engine
- Bipartite graph between users and movies with edge weights as ratings.
- Suggests top-rated movies based on shared user preferences.
- File: `RecommendationEngine.h`, `testRecommendationEngine.cpp`

### 4. Linear Probing Hash Table & Pair Finder
- Custom hash table with linear probing and rehashing.
- Includes a tool to find two numbers in an array that sum to a target.
- File: `HashingLinearProbingDemo.h`, `FindSum.h`, testers

### 5. Round Robin Process Scheduler
- Simulates time-sliced CPU scheduling using a circular linked list.
- Reports individual and average turnaround times.
- File: `RoundRobinProcessScheduling.h`, `CircularLinkedList.h`, `Tester.cpp`

### 6. Skip List & Circular Linked List Implementation
- Includes both probabilistic skip list and singly circular linked list.
- Skip list supports log-time operations with random level generation.
- File: `SkipList.h`, `Node.h`, `CircularLinkedList.h`, `testSkip.cpp`

### 7. Hash Table Using Skip List Chaining
- Hash table using skip lists as buckets for collision resolution.
- Dynamic rehashing based on load factor, modular class structure.
- File: `HashingSkipList.h`, `SkipList.h`, `Node.h`, `HashingSkipListTester.cpp`

### 8. Undirected Graph Analyzer
- Class-based graph with DFS, cycle detection, adjacency/edge list views.
- Generates and analyzes random graphs.
- File: `Graph.h`, `testGraph.cpp`

## 🧠 Skills Demonstrated

- Custom implementation of core data structures
- Collision resolution (linear probing, skip list chaining)
- Balanced tree operations and analysis
- Graph traversal and structure analysis
- Scheduling simulation with circular linked lists
- Modular, test-driven C++ development

## 🛠 How to Compile

Each assignment has its own `README.md` inside the folder with compile/run instructions. Most follow the pattern:

```bash
g++ filename.cpp -o output
./output
