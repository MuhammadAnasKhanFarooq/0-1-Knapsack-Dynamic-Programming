# 0/1 Knapsack Problem using Dynamic Programming

A fourth-semester Design and Analysis of Algorithms (DAA) project focused on solving the 0/1 Knapsack Problem using Dynamic Programming.

The project studies how a logistics company can select items for a delivery vehicle to maximize profit without exceeding the vehicle's weight capacity.

## Problem Overview

In the 0/1 Knapsack Problem:

- Each item has a weight
- Each item has a profit/value
- The vehicle has a maximum capacity
- Each item can either be selected completely or not selected
- Partial selection is not allowed

The objective is to maximize total profit while keeping the selected weight within the available capacity.

## Algorithm Used

The project uses **Dynamic Programming** because the problem contains:

- Optimal substructure
- Overlapping subproblems
- Include/exclude decisions
- Capacity constraints
- Profit maximization

## Implementation Features

The C++ implementation supports:

- Manual item input
- Random dataset generation
- Dynamic Programming table construction
- Maximum profit calculation
- Backtracking to determine selected items
- Total selected weight calculation
- Execution time measurement
- Memory usage estimation
- Time and space complexity reporting

The program supports up to 1000 items and a maximum capacity of 1000 in the current implementation. :contentReference[oaicite:0]{index=0}

## How the Algorithm Works

The program creates a Dynamic Programming table where each state represents the best profit possible using a given number of items and a given capacity.

For each item, the algorithm compares:

- Including the item
- Excluding the item

The better result is stored in the DP table.

After the table is completed, the program performs backtracking to determine which items were selected. :contentReference[oaicite:1]{index=1}

## Complexity

The implemented solution reports:

- **Time Complexity:** `O(n × W)`
- **Space Complexity:** `O(n × W)`

Where:

- `n` = number of items
- `W` = knapsack capacity

The project analysis also discusses the trade-offs of Dynamic Programming compared with other approaches.

## Algorithm Comparison

The project discusses and compares:

- Brute Force
- Greedy Algorithm
- Divide and Conquer
- Backtracking
- Dynamic Programming

Dynamic Programming was selected because it provides an optimal solution while avoiding the exponential behavior of approaches such as brute force and backtracking.

## Performance Analysis

The implementation also reports:

- Execution time
- Estimated memory usage
- Maximum profit
- Total selected weight
- Selected items

The source code calculates and displays these results after solving the problem. :contentReference[oaicite:2]{index=2}

## Project Files

### `knapsack.cpp`

Contains the complete C++ implementation of the 0/1 Knapsack solver using Dynamic Programming.

### `01-DAA-Knapsack-Analysis.pdf`

Contains the project analysis, algorithm explanation, pseudocode, complexity discussion, algorithm comparison, and performance analysis.

## How to Run

1. Download or clone this repository.
2. Open `knapsack.cpp` in a C++ IDE or compiler.
3. Compile the program.
4. Run the executable.
5. Choose either:
   - Manual Input
   - Random Dataset
6. Enter the required values.
7. View the selected items, maximum profit, weight usage, and performance information.

## Project Background

**Academic Project — 4th Semester**  
**Program:** BS Information Technology  
**Course:** Design and Analysis of Algorithms

AI-assisted support was used during parts of the learning and project-development process.

## Status

Completed as a fourth-semester academic project.

## Author

**Muhammad Anas Khan Farooq**

BS Information Technology
