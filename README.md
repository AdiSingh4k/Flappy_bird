# RL_DQN

# 🐦 Flappy Bird AI using Deep Q-Network (DQN)

## Overview

This project implements a Deep Q-Network (DQN) agent to learn and play Flappy Bird through Reinforcement Learning.

The agent interacts with the environment, collects experiences, stores them in a replay buffer, and learns an optimal policy using a neural network built with PyTorch.

## Features

* Deep Q-Network (DQN)
* Experience Replay Buffer
* Epsilon-Greedy Exploration
* Target Network Updates
* Reward-Based Learning
* Real-Time Gameplay Visualization

## Tech Stack

* Python
* PyTorch
* Gymnasium
* Flappy Bird Gymnasium
* NumPy
* Matplotlib

## Reinforcement Learning Pipeline

Environment → State Observation → DQN Agent → Action Selection → Reward Collection → Experience Replay → Network Update

## Results

The agent progressively learns to survive longer and navigate through obstacles by maximizing cumulative rewards.

## Future Improvements

* Double DQN
* Dueling DQN
* Prioritized Experience Replay
* PPO Implementation
* Hyperparameter Optimization

## How to Run

```bash
python agent.py flappybirdv0 --train
```
