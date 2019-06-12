# Udacity Deep Reinforcement Learning Project 1


## Objective

The goal to train an agent to collect yellow bananas and avoid blue bananas. Input dimension is 37 and there are 4 discrete actions. The learning is said to be complete when an average score of 13 is obtained.

## Instructions

Install dependencies and run Navigation.ipynb file from terminal. deep_agent script contains agent code and model.py contains the neural network.

## Architecture

Deep neural network architecture:

First layer - input: input_dim, output: 256 ; Second layer - input: 256, output 128 ; Final layer - input: 128

Model Parameters:

Learning Rate = 0.0001 ; Replay Buffer Size = 100000 ; Batch size = 32 
Tau = 0.001 
Update Frequency = 5    

Parameters used in DQN algorithm:

Steps/episode: 1000 ; decay rate: 0.999 ; eps_start: 1.0 ; eps_end: 0.01




