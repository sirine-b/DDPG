# DDPG Reinforcement Learning for Continuous Control

## Project Description
This repository contains an implementation of **Deep Deterministic Policy Gradient (DDPG)**, a Reinforcement Learning algorithm designed for environments with continuous action spaces. It features **Actor-Critic architecture**, **Experience Replay**, **Target Networks**, and **Exploration Strategies**, and is tested on the like **MountainCarContinuous-v0** environment. **Batch Normalisation** is also included to stabilise training. For a deeper explanation of DDPG, the theory behind it, how it works and the structure of the code, check out my [Medium blog](https://towardsdatascience.com/understanding-ddpg-the-algorithm-that-solves-continuous-action-control-challenges-742c67e0783a).

## Features
- **Actor-Critic Architecture**: DDPG uses two networks—one for policy (actor) and one for value estimation (critic).
- **Replay Buffer**: Stores past experiences to ensure more stable training.
- **Target Networks**: Helps to stabilise learning by slowly updating the target networks.
- **Exploration Noise**: Implements **Ornstein-Uhlenbeck noise** to facilitate smooth exploration in continuous action spaces.
- **Batch Normalisation**: Used to stabilise training by normalising activations and reducing internal covariate shifts.
- **Testing & Visualisation**: Includes functionality to test the agent’s performance and visualise its actions in the MountainCar environment.

## Steps to Run
To be able to run this DDPG implementation and experiment with it, please follow the steps described below by copying and pasting the relevant lines onto your command prompt.
# 1. Clone the repository
```bash
git clone https://github.com/sirine-b/DDPG.git
cd DDPG
```
# 2. Install the required libraries
```bash
pip install -r requirements.txt
```
# 3. Open the Jupyter notebook
```bash
jupyter notebook DDPG_model.ipynb
```
# 4. You're good to go!
You can now run the code yourself and experiment with the training and testing of the DDPG agent by trying out different hyperparameters, environments ... etc

