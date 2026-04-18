# Algorithmic Trading using Reinforcement Learning

## Overview
This repository focuses on building **algorithmic trading strategies using Reinforcement Learning (RL)**.  
The goal is to train RL agents that can autonomously make trading decisions (Buy, Sell, Hold) by learning from historical market data and maximizing long-term rewards (profits).

The project explores and compares **value-based** and **policy-based** reinforcement learning approaches for financial trading.

---

## Repository Structure

| File | Description |
|-----|------------|
| `DQN.ipynb` | Deep Q-Network (DQN) based trading agent |
| `PPO.ipynb` | Proximal Policy Optimization (PPO) based trading agent |
| `README.md` | Project documentation |

---

## Reinforcement Learning Approach

In this project:
- The **environment** simulates a financial market.
- The **agent** observes the market state (prices, indicators, etc.).
- The agent takes actions: **Buy, Sell, Hold**.
- A **reward function** guides learning based on trading performance (profit/loss).

Over time, the agent learns a policy that maximizes cumulative returns.

---

## Implemented Algorithms

### 🔹 Deep Q-Network (DQN)
- Value-based reinforcement learning algorithm
- Uses a neural network to approximate Q-values
- Suitable for discrete action spaces like Buy/Sell/Hold

### 🔹 Proximal Policy Optimization (PPO)
- Policy-gradient reinforcement learning algorithm
- More stable training using clipped objective functions
- Performs well in complex or noisy environments
