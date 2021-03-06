# Deep deterministic policy gradient for solving Unity's reacher environment

<img src="trained_agent.gif" width="400">

This project was done as part of the Udacity Deep Reinforcement Nanodegree. Some of the text in this README is adapted from the original [Udacity Deep Reinforcement Learning Nanodegree repo](https://github.com/udacity/deep-reinforcement-learning). Read `Report.pdf` for more information.


## Introduction

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.


## Getting Started


1. Clone this repository with the command `git clone https://github.com/cjm715/Udacity-drln-p2.git` or simply download as a zip folder by using the green button labeled 'clone or download' on this page. Note that there is no need to separately download the Unity environment. The necessary files are included in the repo.

2. Make sure you have the following python library dependencies:
    - pytorch
    - numpy
    - unityagents
    - matplotlib
    - jupyter notebook

If you have virtual environments or conda environments. You can handle these dependencies
by creating an environment with Python 3.6 and running the command `pip install -r requirements.txt`.

3. Run jupyter notebook and open `project2.ipynb`.
