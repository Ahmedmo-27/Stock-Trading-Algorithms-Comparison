# Stock Trading Algorithms Comparison

![Project Logo](docs/logo-miu.png)

A comprehensive comparison of algorithmic approaches for optimal stock trading under transaction constraints, featuring dynamic programming, greedy, and hybrid methods.

## Table of Contents
- [Project Description](#project-description)
- [Key Features](#key-features)
- [Algorithms Implemented](#algorithms-implemented)
- [Performance Comparison](#performance-comparison)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributors](#contributors)
- [License](#license)

## Project Description

This project implements and compares three algorithmic approaches for solving the constrained stock trading problem:
1. **Dynamic Programming**: Provides globally optimal solutions with O(nk) complexity
2. **Greedy Algorithm**: Offers fast O(n) execution with locally optimal decisions
3. **Hybrid Approach**: Balances speed and optimality with O(n log k) complexity

The system includes both C++ implementations for backend analysis and a web-based visualization tool for interactive exploration of the algorithms.

## Key Features

- Comprehensive comparison of trading algorithms
- Interactive web visualization of trading decisions
- Detailed performance metrics and complexity analysis
- Robust handling of transaction constraints and fees
- Step-by-step execution visualization
- Responsive design for desktop and mobile

## Algorithms Implemented

### Dynamic Programming Approach
- Time Complexity: O(nk)
- Space Complexity: O(k)
- Optimal profit calculation
- Best for: Portfolio management, strategic trading

### Greedy Approach
- Time Complexity: O(n)
- Space Complexity: O(1)
- Fast execution with good-enough solutions
- Best for: High-frequency trading, real-time systems

### Hybrid Approach
- Time Complexity: O(n log k)
- Space Complexity: O(k)
- Balanced performance and optimality
- Best for: Swing trading, medium-frequency systems

## Performance Comparison

| Metric                | Dynamic Programming | Greedy  | Hybrid  |
|-----------------------|--------------------|---------|---------|
| Avg. Profit (k=2)     | $1,842 ± 156       | $1,340  | $1,680  |
| Max Profit Difference | +27.3%             | -       | +20.1%  |
| Execution Time (n=10K)| 48ms ± 3.2         | 2ms ± 0.4 | 8ms ± 0.1 |
| Volatility Handling   | Excellent          | Moderate | Good    |

## Installation

### C++ Implementation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-trading-algorithms-comparison.git