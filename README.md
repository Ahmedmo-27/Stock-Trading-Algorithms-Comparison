# Stock Trading Algorithms Comparison

![Project Logo](docs/logo-miu.png)

A web-based comparison of algorithmic approaches for optimal stock trading under transaction constraints.

## Table of Contents
- [Project Description](#project-description)
- [Key Features](#key-features)
- [Algorithms](#algorithms)
- [Performance](#performance)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Project Description

Interactive comparison of two fundamental algorithmic trading approaches:
1. **Dynamic Programming**: Optimal solutions with O(nk) complexity
2. **Greedy Algorithm**: Fast execution with O(n) complexity

## Key Features

- Interactive trading visualization
- Step-by-step algorithm execution
- Side-by-side performance comparison
- Transaction limit and fee handling
- Responsive web interface

## Algorithms

### Dynamic Programming
- **Time Complexity**: O(nk)
- **Space Complexity**: O(k)
- **Best For**: Strategic portfolio management
- **Characteristics**: 
  - Guaranteed optimal profit
  - Higher computational cost
  - Excellent volatility handling

### Greedy Approach
- **Time Complexity**: O(n)
- **Space Complexity**: O(1)
- **Best For**: High-frequency trading
- **Characteristics**:
  - Near-instant execution
  - Locally optimal decisions
  - Moderate volatility handling

## Performance

| Metric                | Dynamic Programming | Greedy  |
|-----------------------|--------------------|---------|
| Avg. Profit (k=2)     | $1,842 ± 156       | $1,340  |
| Execution Time (n=10K)| 48ms ± 3.2         | 2ms ± 0.4 |
| Volatility Handling   | Excellent          | Moderate |

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/stock-trading-algorithms-comparison.git
```

2. Install dependencies:
```bash
cd stock-trading-algorithms-comparison
npm install
```

3. Open `Stock Trading.html` in your browser.

## Usage

1. Enter stock prices (comma-separated values)
2. Set transaction limit (k)
3. Set transaction fee amount
4. Click "Calculate" to compare results

## Results

The web interface displays:
- Calculated maximum profits for both algorithms
- Visual representation of trading decisions
- Step-by-step execution details
- Performance metrics comparison
