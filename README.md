# Taxi Game Reinforcement Learning Project

## Overview
### What is the Taxi Game?
The goal of the Taxi game is to train an agent (the taxi) to pick up a passenger at one of four designated locations and drop them off at a specified destination, which is also one of these four locations. The taxi operates in a 5x5 grid world. 
* **R, G, Y, B** represent the four pickup and drop-off locations.
* The `:` characters represent open grid cells.
* The `|` and `+` characters form the boundaries of the grid.

The taxi and passenger start at random locations within this grid, and a destination location is also randomly chosen.
<pre>
```
+---------+
|R: | : :G|
| : | : : |
| : : : : |
| | : | : |
|Y| : |B: |
+---------+
```
</pre>

This project is a comprehensive implementation of various reinforcement learning algorithms to solve the Taxi-v3 environment from OpenAI's Gym. This project includes implementations of Q-learning, Monte Carlo, and Deep Q-Network (DQN) algorithms, showcasing their application in a classic control task.

## Features
- Implementation of **Q-learning**: A tabular method for reinforcement learning.
- Implementation of **Monte Carlo**: A method based on averaging sample returns.
- Implementation of **Deep Q-Network (DQN)**: A neural network-based approach to reinforcement learning.
- Visualization of training progress and results.

## Installation
To get started with the Taxi Game Reinforcement Learning project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/shallowManica/Taxi_Game_RL_Project.git
   cd Taxi_Game_RL_Project
   ```

## Dependencies
Here are the dependencies required for this project:
```text
gym
numpy
tensorflow
pyvirtualdisplay
ipykernel
matplotlib
pandas
keras
```

## Usage
To run the notebook and observe the results of different reinforcement learning algorithms, use the following steps:

1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open the `taxiGame.ipynb` notebook file and run the cells to see the implementation and results of Q-learning, Monte Carlo, and DQN algorithms on the Taxi-v3 environment.

## Directory Structure
```plaintext
Taxi_Game_RL_Project/
├── taxiGame.ipynb            # Jupyter Notebook with RL implementations
├── README.md               # Project documentation
```

