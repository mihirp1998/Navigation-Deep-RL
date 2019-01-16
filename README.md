# Unity Banana Navigation

![banana](images/banana-intro.gif)

## Intro

This project is for training a Dqn agent to collect the right bananas which yield the highest reward.
This is based on Banana enviornment available in udacity nanodegree
```
Unity brain name: BananaBrain
        Number of Visual Observations (per agent): 0
        Vector Observation space type: continuous
        Vector Observation space size (per agent): 37
        Number of stacked Vector Observation: 1
        Vector Action space type: discrete
        Vector Action space size (per agent): 4
        Vector Action descriptions: , , , 
```
Above is the information about the enviornment, the goal is to get 13+ mean reward for 100 consecutive episodes.

## Installation

To install the required packages run the below command

```
python python/setup.py
```

## Instructions

The main code to run is there in `Navigation.ipynb` notebook. You can find the architecture of the model in `model.py`.
We have the agent in `agent.py`
