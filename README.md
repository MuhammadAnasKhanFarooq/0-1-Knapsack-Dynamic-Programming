# 0/1 Knapsack Problem using Dynamic Programming

A fourth-semester Design and Analysis of Algorithms (DAA) project focused on solving the 0/1 Knapsack Problem using Dynamic Programming.

The project studies how a logistics company can select items for a delivery vehicle in order to maximize profit without exceeding the vehicle's weight capacity.

## Problem Overview

In the 0/1 Knapsack Problem:

- Each item has a weight
- Each item has a profit/value
- The vehicle has a maximum capacity
- Each item can either be selected completely or not selected at all
- Partial selection is not allowed

The objective is to maximize total profit while keeping the total weight within the allowed capacity.

## Algorithm Used

The project uses **Dynamic Programming** because the problem has:

- Optimal substructure
- Overlapping subproblems
- Binary include/exclude decisions
- A capacity constraint
- A profit-maximization objective

## Main Features

- Manual input of items
- Random dataset generation
- Dynamic Programming table
- Maximum profit calculation
- Backtracking to identify selected items
- Total selected weight calculation
- Execution time measurement
- Memory usage estimation
- Time complexity analysis
- Space complexity analysis

## Complexity

The implemented Dynamic Programming solution has:

- **Time Complexity:** `O(nW)`
- **Space Complexity:** `O(nW)`

Where:

- `n` = number of items
- `W` = knapsack capacity

The project also discusses a possible space optimization to `O(W)` when item traceback is not required.

## Algorithm Comparison

The project compares Dynamic Programming with:

- Brute Force
- Greedy Algorithm
- Divide and Conquer
- Backtracking

Dynamic Programming was selected because it provides an optimal solution while avoiding the exponential behavior of brute force and backtracking.

## Performance Analysis

The project includes empirical testing using increasing input sizes and compares measured execution time with theoretical complexity.

It also discusses:

- Scalability
- Memory consumption
- Pseudo-polynomial complexity
- Execution-time vs optimality trade-offs
- Memory vs speed trade-offs
- Solution quality vs scalability

## Project Files

- `01-DAA-Knapsack-Analysis.pdf`
- `02-DAA-Knapsack-Implementation.pdf`

These documents contain the complete algorithm explanation, pseudocode, implementation, complexity analysis, test results, and performance evaluation.

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
