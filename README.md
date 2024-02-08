# Reinforcement Learning in RaceTrack Environment

This repository contains Python code implementing different reinforcement learning algorithms applied to a custom RaceTrack environment.

## Overview

In this project, we explore various reinforcement learning algorithms to teach an agent to navigate a RaceTrack environment. The RaceTrack environment consists of a grid where the agent (a car) must reach a goal position while avoiding obstacles. We implemented the following algorithms:

- **SARSA (State-Action-Reward-State-Action)**
- **Q-Learning**
- **N-Step SARSA**

We also performed hyperparameter tuning for each algorithm to find the best parameters for learning.

## Environment

The RaceTrack environment is implemented using OpenAI Gym. The agent (car) can move in four directions: up, down, left, and right. The goal is to reach a specific position on the grid while avoiding negative obstacles and walls.

## Algorithms

### SARSA

SARSA is an on-policy TD learning algorithm. We experimented with different values for the learning rate (alpha), discount factor (gamma), and epsilon-greedy exploration.

### Q-Learning

Q-Learning is an off-policy TD learning algorithm. Similarly, we explored different values for alpha, gamma, and epsilon to find the optimal parameters.

### N-Step SARSA

N-Step SARSA is a variant of SARSA that considers n steps ahead for updates. We implemented a 2-step SARSA and tuned its parameters.

## Results

We evaluated the performance of each algorithm based on the rewards obtained during training episodes and the number of timesteps taken to reach the goal. We visualized the training progress using plots and compared the performance of SARSA, Q-Learning, and N-Step SARSA.

## Usage

To use the code provided in this repository, follow these steps:

1. Install the required dependencies using pip.
2. Import the necessary modules and classes.
3. Instantiate the environment and agent.
4. Train the agent using the desired algorithm and hyperparameters.
5. Evaluate the trained agent's performance.

## Conclusion

Through this project, we gained insights into the effectiveness of different reinforcement learning algorithms in solving the RaceTrack environment. We observed how tuning hyperparameters can significantly impact the learning process and ultimately the agent's performance.
