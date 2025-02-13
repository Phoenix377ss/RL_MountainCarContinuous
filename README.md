## DDPG для MountainCarContinuous
This project implements the Deep Deterministic Policy Gradient (DDPG) algorithm to train an agent to solve the MountainCarContinuous-v0 environment from OpenAI Gym.

The agent uses deep neural networks to approximate the Actor and Critic functions. It also employs Ornstein-Uhlenbeck noise to improve action exploration in continuous action spaces.

Key Features:
DDPG (Deep Deterministic Policy Gradient) – reinforcement learning algorithm for continuous control.
Replay Buffer – stores past experiences for stable training.
Target Networks – stabilize learning by using separate target models.
Ornstein-Uhlenbeck Noise – temporally correlated noise for better exploration.
PyTorch – deep learning framework for training neural networks.
