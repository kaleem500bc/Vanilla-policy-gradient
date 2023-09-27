# Reinforcement Learning with PyTorch

This repository contains an implementation of a reinforcement learning agent using PyTorch. The agent is trained to perform in the CartPole-v0 environment from OpenAI Gym. It uses policy gradient methods to learn a policy that maximizes cumulative rewards.

## Overview

- **Environment**: The agent interacts with the CartPole-v0 environment, where the goal is to balance a pole on a moving cart.

- **Policy Network**: The agent uses a neural network model to represent its policy. The policy network takes the current state as input and outputs a probability distribution over available actions.

- **Training**: The agent is trained using policy gradient methods. It collects trajectories during training episodes, computes the loss based on the rewards obtained, and updates its policy network through backpropagation.

- **Visualization**: The training progress is visualized using Matplotlib, displaying the agent's score (number of successful episodes) over time.
