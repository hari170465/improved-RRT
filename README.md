# Improved RRT-Connect Algorithm with Quadruple Tree Structure

This project implements an **Improved RRT-Connect Algorithm** designed for faster and more efficient path planning in complex environments. The algorithm incorporates a **quadruple tree structure** that achieves an **8.82x speed improvement** compared to the traditional RRT-Connect, which was already faster than RRT and RRT*.

## Key Features
- **Quadruple Tree Structure**: Enhances pathfinding efficiency, significantly reducing computational time.
- **Goal Biasing**: Improves path convergence accuracy by prioritizing the goal, minimizing unnecessary node exploration during the search.
- **Comparative Implementation**: Includes RRT, RRT*, RRT-Connect, and the improved RRT-Connect algorithm to benchmark performance.
- **Optimized for Complex Environments**: Demonstrates robust navigation capabilities in dynamically challenging scenarios.

## Results
- Achieved **8.82x faster pathfinding** compared to traditional RRT-Connect.
- Reduced node redundancy, resulting in smoother and more direct paths.

## Demonstration Video
![Algorithm Demo](C:\Users\sudan\OneDrive\Documents\GitHub\improved-RRT\output\Improved_RRT)


## Implementation Details
The project integrates a third midpoint and biases the tree flow for rapid convergence to a common point. The improvements ensure efficient navigation and accurate path planning in environments with high obstacle density.



## How to Run the Code
1. Clone this repository and ensure the required packages are installed:
   - `OpenCV`
   - `math`
   - `random`
   - `time`
   - `numpy`

2. Enter the star and goal coordinates. One such exampple is given below.
  - Enter the start coordinates (x, y): 20,20
  - Enter the goal coordinates (x, y): 580,50
