# Udacity Deep Reinforcement Learning Project 1


## Objective

The goal to train an agent to collect yellow bananas (score of +1 ) and avoid blue bananas (score of -1). Input dimension is 37 (contains the agent's velocity, along with ray-based perception of objects around agent's forward direction) and there are 4 discrete actions corresponding to the directions. The learning is complete when an average score of 13 is obtained.

## Instructions

1) Install Python 3.6 and other dependencies as defined in https://github.com/udacity/deep-reinforcement-learning#dependencies
  
2) Download the Unity environment for the relevant OS place the file in the p1_navigation folder and unzip it

3) Run Navigation.ipynb file from terminal. Imported scripts include deep_agent.py which contains the agent code and model.py which contains the neural network.

## Architecture

Deep neural network architecture:

First layer - input: input_dim, output: 256 ; Second layer - input: 256, output 128 ; Final layer - input: 128

Model Parameters:

Learning Rate = 0.0001 ; Replay Buffer Size = 100000 ; Batch size = 32 
Tau = 0.001 
Update Frequency = 5    

Parameters used in DQN algorithm:

Steps/episode: 1000 ; decay rate: 0.999 ; eps_start: 1.0 ; eps_end: 0.01




