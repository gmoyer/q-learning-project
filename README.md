# q-learning-project

## Overview

This project demonstrates the implementation of both approximate Q-learning and regular Q-learning using Gymnasium's Lunar Lander environment. The goal is to train an agent to successfully land a lunar module on a designated landing pad by optimizing its actions through reinforcement learning techniques.

## Features

- **Regular Q-Learning**: Learns the optimal policy by updating Q-values for approximate state-action pairs.
- **Approximate Q-Learning**: Employs features to generalize Q-values across similar states, enabling scalability to larger state spaces.
- **Gymnasium Integration**: Leverages the Lunar Lander environment for simulation and testing.
- **Visualization**: Includes environment wrapping and matplotlib to visualize and record the agent's performance and learning progress.

## Results

The agent learns to land the lunar module efficiently by optimizing its actions over episodes. Approximate Q-learning demonstrates better scalability for larger state spaces, while regular Q-learning provides a straightforward approach for smaller environments.
