# Linear Probing Hash Table & Pair Finder

This project implements a custom **hash table** using **linear probing** in C++, with dynamic resizing and collision resolution. It also applies the hash table to solve a real-world algorithmic challenge: finding two numbers in an array that sum to a given target.

## Components

### 1. HashingLinearProbingDemo
- Implements an integer hash table with:
  - Open addressing (linear probing)
  - Collision handling
  - Dynamic resizing via rehashing when the load factor exceeds threshold
- Core methods: `Insert`, `Search`, `Delete`, `Display`

### 2. PairFinder (`FindSum.h`)
- Solves the "Find Pair With Given Sum" problem
- Uses the custom hash table for fast lookups
- Rejects zero inputs to maintain internal constraints

### 3. Test Files
- `HashingLinearProbingDemoTester.cpp`: Tests insertion, search, deletion, and rehashing behavior
- `FindSumTester.cpp`: Runs 5 use cases with varying arrays and targets to verify the pair-finding logic

## Skills Demonstrated
- Hashing with open addressing
- Collision resolution via linear probing
- Load factor management and rehashing
- C++ class design and dynamic memory use
- Real-world application of hashing to algorithmic problems

## 🛠 Compile & Run

```bash
g++ HashingLinearProbingDemoTester.cpp -o hash_demo
./hash_demo

g++ FindSumTester.cpp -o pair_finder
./pair_finder
