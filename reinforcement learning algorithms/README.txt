
Overleaf READ-ONLY link:
https://www.overleaf.com/read/gqfvpphxpkyr#a28228

Github link repository:
https://github.gatech.edu/gt-omscs-ml/cs-7641-2025-spring-ylei82/tree/81d820a438b062822ea114616f26cd66bd5b89bc/Assignment-4


## Overview
This notebook implements and compares four reinforcement learning algorithms—Value Iteration, Policy Iteration, SARSA, and Q-Learning—across two environments from OpenAI Gym: Blackjack and CartPole.

The experiments cover:
- Model-based vs model-free RL comparisons
- Effects of discretization on CartPole
- Exploration strategies (e.g., epsilon-greedy with decay)
- Convergence behavior and reward visualization

All figures presented in the report can be reproduced using the notebook.

## Requirements
No external dataset is required. All experiments use standard Gym environments.
Ensure the following packages are installed:

- gym==0.26.2
- numpy
- matplotlib
- tqdm

To install, run:

    pip install gym==0.26.2 numpy matplotlib tqdm


## Code Structure
- `A4_code.ipynb`: Contains all implementation and experiments, divided into:
  - Environment setup and discretization
  - Value Iteration & Policy Iteration
  - SARSA and Q-Learning
  - Reward curves, episode lengths, convergence curves, and heatmaps
  - Sensitivity tests (gamma, epsilon decay, bin size)

## Reproducibility
- Run `A4_code.ipynb` from top to bottom in Jupyter Lab or VSCode.
- Random seeds are fixed for consistency.
- All key plots are auto-generated and displayed inline.

## Output
- Console: displays intermediate results and learning metrics
- Notebook figures:
  - Convergence curves for VI and PI
  - Heatmaps of Blackjack policies
  - Episode reward and length curves for SARSA and Q-Learning
  - Discretization sensitivity plots for CartPole

##  Notes
- The report is written in IEEE format (8 pages max).
- All four required references (Bellman, Howard, Rummery, Watkins) are cited.
- OpenAI Gym environments (Blackjack and CartPole) are properly referenced.
- This project assumes default OpenAI Gym setup; no custom environments required.
