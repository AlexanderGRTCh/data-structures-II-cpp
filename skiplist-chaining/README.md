# Skip List Chaining

This assignment demonstrates an alternative hash table implementation using **Skip Lists** for collision resolution instead of linear probing. It showcases advanced data structure design, dynamic resizing, and probabilistic balancing for efficient insertions, deletions, and lookups.

## Components

### 1. SkipList (`SkipList.h`, `Node.h`)
- A multi-level probabilistic linked structure for sorted key storage
- Supports fast `Insert`, `Search`, and `Delete` operations
- Balances levels randomly using coin-flip logic (`RandomLevel`)
- Automatically adjusts the maximum active level after deletions

### 2. HashingSkipList (`HashingSkipList.h`)
- Hash table structure that uses SkipLists for collision resolution
- Dynamically resizes when the load factor exceeds a set threshold
- Maintains efficient access while managing collisions through structure-level separation

### 3. Tester (`HashingSkipListTester.cpp`)
- Demonstrates:
  - Insertions that trigger rehashing
  - Searches for existing and missing keys
  - Deletions with structural validation
  - Step-by-step output of hash table state before and after operations

## Key Concepts Demonstrated
- Skip List fundamentals: probabilistic balancing, level-based traversal
- Hash table design and open-structure collision handling
- Load factor threshold control and rehashing logic
- Modular, object-oriented C++ with dynamic memory allocation
- Alternative collision resolution strategies beyond linear probing

## How to Compile & Run

```bash
g++ HashingSkipListTester.cpp -o skiplist_hash
./skiplist_hash
