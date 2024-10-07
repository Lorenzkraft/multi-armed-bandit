# Bandit Algorithms Notebook

## Overview

This notebook demonstrates the implementation and comparison of two classic algorithms used for solving multi-armed bandit problems: **Epsilon-Greedy** and **Upper Confidence Bound (UCB)**. These algorithms are useful in reinforcement learning for balancing exploration and exploitation when selecting actions in uncertain environments.

## Structure

The notebook consists of the following sections:

1. **Libraries and Setup**:
   - The required libraries are imported, including `numpy` for numerical operations and `matplotlib` for visualization.

2. **Bandit Problem Setup**:
   - Defines the bandit environment with a number of arms, each associated with a reward probability.
   - Functions for generating rewards from each arm are included.

3. **Epsilon-Greedy Algorithm**:
   - Implements the Epsilon-Greedy algorithm, where exploration is balanced with exploitation by randomly choosing between a random arm and the arm with the highest known reward.

4. **Upper Confidence Bound (UCB) Algorithm**:
   - Implements the UCB algorithm, which uses an optimistic estimate of the arm's potential reward to decide whether to explore it further.

5. **Simulation and Results**:
   - Simulates both algorithms over time, calculating the total reward collected by each.
   - A log-scale plot of the rewards over time is generated to compare the performance of both algorithms.

## How to Use

1. **Prerequisites**:
   - Install the required Python packages:
     ```
     pip install numpy matplotlib
     ```

2. **Running the Notebook**:
   - Run all the cells sequentially to simulate the algorithms and visualize the results.

3. **Customizing the Simulation**:
   - You can modify parameters like:
     - Number of arms (bandits).
     - Reward probabilities for each arm.
     - Exploration rate for the Epsilon-Greedy algorithm.
     - Number of iterations for the simulation.

## Output

The notebook produces a plot comparing the total rewards collected by the Epsilon-Greedy and UCB algorithms over time, using a logarithmic scale for the y-axis.

## License

Feel free to modify and use this notebook for educational or research purposes.
