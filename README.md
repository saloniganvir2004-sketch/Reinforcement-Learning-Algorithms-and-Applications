# Reinforcement Learning Algorithms and Applications

## Project Overview

This project demonstrates fundamental Reinforcement Learning algorithms using Python, NumPy, Pandas, and Matplotlib.

It explores Monte Carlo methods, Temporal Difference Learning, SARSA, and Q-Learning through state-value estimation, Gridworld simulations, policy generation, and algorithm comparisons.

## Implemented Algorithms

### 1. First-Visit Monte Carlo
- Generates episodes using a predefined state sequence.
- Calculates discounted returns.
- Estimates state values using first-visit Monte Carlo.

### 2. First-Visit vs Every-Visit Monte Carlo
- Examines repeated state visits.
- Calculates returns for individual visits.
- Compares first-visit and every-visit value estimates.

### 3. Incremental Monte Carlo
- Updates value estimates incrementally.
- Compares incremental estimates with ordinary averages.

### 4. Temporal Difference Learning (TD(0))
- Implements temporal difference updates.
- Uses learning rate alpha = 0.1.
- Uses discount factor gamma = 0.9.
- Tracks state-value estimates over multiple episodes.

### 5. Monte Carlo vs TD(0)
- Compares state-value estimation methods.
- Visualizes learning and convergence behaviour.

## SARSA and Q-Learning

### 6. Gridworld Environment
- Implements a 4 × 4 grid environment.
- Defines starting and goal positions.
- Supports four directional actions.
- Uses reward-based state transitions.

### 7. SARSA
- Implements an on-policy learning algorithm.
- Uses epsilon-greedy action selection.
- Trains over 500 episodes.
- Generates a learned policy.

### 8. Q-Learning
- Implements an off-policy learning algorithm.
- Updates Q-values using maximum future action values.
- Trains over 500 episodes.
- Generates a Q-table and learned policy.

### 9. Algorithm Comparison
- Compares SARSA and Q-Learning.
- Evaluates average rewards.
- Evaluates average steps.
- Visualizes learning progress using rolling-average reward plots.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Random
- Collections (defaultdict)
- Google Colab / Jupyter Notebook

## Project Structure

Reinforcement-Learning-Algorithms-and-Applications/
├── Reinforcement_Learning_Module_III.ipynb
├── README.md
└── requirements.txt

## Execution

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required dependencies.
3. Execute the cells sequentially.
4. Observe Monte Carlo and TD(0) value estimates.
5. Examine the SARSA and Q-Learning policies.
6. Compare the learning performance of both algorithms.

