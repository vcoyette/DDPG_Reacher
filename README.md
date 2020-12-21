# DDPG_Reacher
This repository contains the code for the second project of the Deep RL nano degree from Udacity.

## Goal 
The objective of this project is to train a RL agent to solve the Unity Reacher environment.

![The environment](images/reacher.gif)

The goal is for a double-jointed arm  to follow a target location.
A reward of +0.1 is provided if the hand is the goal location at each timestep.
The state space is of composed of 33 variables corresponding to position, rotation, velocity and angular velocity of the arm.
Each action is a vector with four numbers, corresponding to torque applicable to joints.
Each torque should be a number between 0 and 1.

The agent will be trained on a variant of the environment containing 20 arms in parallel, to collect samples faster.

## Gettting Started
First, follow the instructions [here](https://github.com/udacity/deep-reinforcement-learning#dependencies) to create a virtual environment.

Then, the unity environment should be downloaded.
Download the version that matches your system and unzip the archive.
Remember the path to the extracted folder.

* Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
* Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
* Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
* Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

The notebook `Continuous_Control.ipynb` contains code for the training and rendering of trained agent.
