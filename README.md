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


# Module IV: Function Approximation and Deep Reinforcement Learning

This notebook explores advanced Reinforcement Learning techniques, including function approximation, eligibility traces, experience replay, and Deep Q-Networks.

## Implemented Algorithms and Techniques

### 1. Linear Function Approximation
- State-value estimation using feature vectors.
- Weight-based value prediction.

### 2. Gradient Monte Carlo
- Gradient-based value function updates.
- Prediction error tracking.

### 3. Semi-Gradient TD(0)
- Temporal Difference learning with function approximation.
- State-value updates using TD errors.

### 4. Gradient MC vs TD(0)
- Comparative learning analysis.
- Mean squared error visualization.

### 5. TD(lambda)
- Eligibility trace implementation.
- Comparison of different lambda values.
- Analysis of eligibility trace effects.

### 6. Action-Value Function Approximation
- Q-value estimation using feature vectors.
- Action selection based on estimated Q-values.

### 7. Approximate Q-Learning
- 3x3 Gridworld environment.
- Epsilon-greedy action selection.
- Approximate Q-value updates.

### 8. Experience Replay
- Replay buffer implementation.
- Transition storage and random mini-batch sampling.

### 9. Experience Replay Comparison
- Learning with and without experience replay.
- Rolling-average reward visualization.

### 10. Deep Q-Network (DQN)
- Neural network-based Q-value approximation.
- Two hidden layers with 128 neurons each.
- Target network implementation.
- Experience replay buffer.
- Adam optimization.
- Smooth L1 loss.
- Epsilon-greedy exploration.

### 11. CartPole-v1 Environment
- DQN training over 300 episodes.
- Reward tracking.
- Training loss visualization.
- Epsilon decay analysis.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- PyTorch
- Gymnasium
- Google Colab / Jupyter Notebook

Notebook: Reinforcement_Learning_Module_IV.ipynb


# Module I: MDP Fundamentals and Bellman Equations

This notebook covers the fundamentals of Markov Decision Processes and policy evaluation.

## Implemented Concepts

- MDP Environment Formulation
- State and Action Representation
- Transition and Reward Functions
- State Transition Diagram
- Bellman Expectation Equation
- Iterative Policy Evaluation
- State-Value Function
- Action-Value Function
- Policy Comparison
- Stochastic MDP
- Value Function Convergence Visualization

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- NetworkX
- Google Colab / Jupyter Notebook

Notebook: Reinforcement_Learning_Module_I_MDP_Fundamentals.ipynb


# Practical: Markov Chains, Markov Reward Processes and Bellman Equations

This practical implements Markov Chain modeling, examines the Markov Property, and computes state values using Markov Reward Processes and Bellman equations.

## Implemented Concepts

### Part I: Markov Chain and Markov Property
- Weather Prediction Markov Chain
- Weather State Representation
- Transition Probability Matrix
- Transition Matrix Validation
- Markov Chain State Transition Diagram
- Weather Sequence Simulation
- Empirical Verification of the Markov Property

### Part II: Markov Reward Process
- MRP Formulation
- State Reward Function
- Discount Factor
- Bellman Equation
- NumPy Matrix-Based Value Computation
- Iterative Bellman Updates
- State-Value Convergence Visualization

### Part III: Bellman Recursive Equation
- Manual Bellman Value Calculation
- Python-Based Bellman Computation
- Numerical Verification
- Direct Matrix Solution vs Iterative Solution

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- NetworkX
- Google Colab
- Jupyter Notebook

Notebook: Markov_Chain_MRP_and_Bellman_Equation.ipynb


# Tic-Tac-Toe Reinforcement Learning Agent

## Project Overview

Developed a Reinforcement Learning agent that learns to play Tic-Tac-Toe through repeated interaction with the environment using Tabular Q-Learning.

## Implemented Concepts

- Tic-Tac-Toe Environment Development
- State and Action Representation
- Reward Function Design
- Q-Learning Algorithm
- Epsilon-Greedy Action Selection
- Exploration and Exploitation
- Q-Table Training over 50,000 Episodes
- Training Performance Visualisation
- Agent Evaluation against Random Opponent
- Random Agent vs Trained Agent Comparison
- AI Gameplay Demonstration
- Optional Human vs AI Gameplay

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Google Colab / Jupyter Notebook

Notebook: Reinforcement_Learning_Agent_for_Tic_Tac_Toe.ipynb

