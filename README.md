# Distributed Multi-Task Learning for Stochastic Bandits with Context Distribution and Stage-wise Constraints

## Description

This repository provides the implementation necessary to reproduce the experiments presented in the paper "Distributed Multi-Task Learning for Stochastic Bandits with Context Distribution and Stage-wise Constraints", focusing on both synthetic datasets and the MovieLens data.

## Usage

- Synthetic_setting.ipynb: A Jupyter notebook containing all baselines and the proposed DiSC-UCB approach for synthetic data. 
- Synthetic_agent.ipynb: This notebook provides the code for DiSC-UCB to reproduce experiments with varying numbers (K) of arms for synthetic data. 
- Synthetic_alpha.ipynb: Contains the implementation for DiSC-UCB to reproduce experiments by adjusting the alpha values for synthetic data. 
- Movielens_setting.ipynb: DiSC-UCB code for the MovieLens dataset. 
- Movielens_agent.ipynb: DiSC-UCB implementation for experiments with varying arm numbers for the MovieLens data. 
- Movielens_alpha.ipynb: DiSC-UCB implementation for experiments with varying alpha values for the MovieLens data. 

Lastly:
- Unknown_Baseline_Reward_synthetic.ipynb:  Contains both DiSC-UCB and DiSC-UCB2 implementations for synthetic data.
- Unknown_Baseline_Reward_movielens.ipynb: Contains the DiSC-UCB and DiSC-UCB2 code specifically for the Movielens dataset. 
