# Taxi-v3 Reinforcement Learning: Q-Learning vs. Policy Gradient (REINFORCE)

## Project Overview
The project was done for the course "Introduction to Reinforcement Learning", Faculty of Economic Sciences, University of Warsaw. 
This project explores two distinct branches of Reinforcement Learning (RL) to solve the Taxi-v3 problem from the Gymnasium library. The goal is to train an autonomous taxi agent to navigate a 5x5 grid, pick up a passenger from one of four designated locations, and drop them off at a specific destination in the minimum number of steps. We compare a traditional tabular method (Q-Learning) against a deep learning approach (Policy Gradient/REINFORCE).

## Installation & Requirements
To run this project, you will need Python 3.8+ and the following libraries:
- gymnasium 
- numpy 
- torch 
- matplotlib 
- pandas
- time
- os
- random

## Project Structure
Taxi_Driver_Q_Learning.ipynb: Q-Learning implementation and results.

Taxi_PolicyGR - Final.ipynb: REINFORCE implementation, training loop, and evaluation.

policy_taxi_videos: folder contains videos from PolicyGR training.

weights: folder contains the pre-trained weights from PolicyGR.

## Key findings 
This project demonstrates the trade-offs between tabular and neural-network-based RL. While Q-learning is superior for small, discrete grids, the Policy Gradient approach provides a foundation for scaling to continuous or high-dimensional state spaces where tables are no longer feasible.