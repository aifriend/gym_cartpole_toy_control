# Gym CartPole Toy Control

Reinforcement learning experiments solving the CartPole control problem using OpenAI Gym and PyTorch.

## Overview

Implementations of various RL approaches to the classic CartPole balancing task, from basic control to Deep Q-Networks (DQN).

## Experiments

| Directory | Description |
|-----------|-------------|
| `gym-basic/` | Basic Gym environment setup and random agents |
| `cartpole/` | CartPole-specific control implementations |
| `pytorch-ls-dqn/` | PyTorch DQN with experience replay |

## Tech Stack

- **Language:** Python 3
- **Environment:** OpenAI Gym
- **ML Framework:** PyTorch
- **Algorithm:** Deep Q-Network (DQN)

## Requirements

- Python 3.6+
- PyTorch
- OpenAI Gym

## Quick Start

```bash
pip install gym torch numpy
cd cartpole
python main.py
```

## The CartPole Problem

A pole is attached to a cart on a frictionless track. The agent must apply forces (left/right) to keep the pole balanced upright. The episode ends when the pole tilts too far or the cart moves off-screen.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## Author

**Jose** — [@aifriend](https://github.com/aifriend)
