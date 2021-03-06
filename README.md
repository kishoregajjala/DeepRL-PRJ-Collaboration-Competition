# Deep Reinforcement Learning : Collaboration and Competition

This repository has my work for the Udacity's Deep Reinforcement Learning Nanodegree Project 3: Collaboration and Competition

## Project Details

### Project Description
In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a positive reward. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a negative reward. Thus, the goal of each agent is to keep the ball in play.

### Reward
In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01.  

### State Space and Action
The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. 

The action space is continuous, which allows each agent to execute more complex and precise movements. There's an unlimited range of possible action values to control the rocket. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

### Project Goal
The goal of each agent is to keep the ball in play. The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

* After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
* This yields a single score for each episode.

The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

## The Environment
For this project, we will work with the [Tennis](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis) environment. The project environment is similar to, but not identical to the Tennis environment.

![](tennis.gif)

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

* After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
* This yields a single score for each episode.

The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

We are required to work with the environment that we will provide as part of the project. In particular, the project submission should not use the environment on the ML-Agents GitHub page.

## Getting Started

Follow the instructions below to explore the environment on your own machine! You will also learn how to use the Python API to control your agent.

### Step 1: Activate the Environment
If you haven't already, please follow the [instructions in the DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies/ "instructions in the DRLND GitHub repository") to set up your Python environment. These instructions can be found in README.md at the root of the repository. By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to complete the project.

(For Windows users) The ML-Agents toolkit supports Windows 10. While it might be possible to run the ML-Agents toolkit using other versions of Windows, it has not been tested on other versions. Furthermore, the ML-Agents toolkit has not been tested on a Windows VM such as Bootcamp or Parallels.

SPECIAL NOTE TO BETA TESTERS - please also download the p3_collab-compet folder from [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/tmp/p3_collab-compet.zip) and place it in the DRLND GitHub repository.

### Step 2: Download the Unity Environment
For this project, we will not need to install Unity - this is because Udacity has already built the environment for us, and we can download it from one of the links below. You need only select the environment that matches your operating system:

 * Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
 * Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
 * Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
 * Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)

(For Windows users) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(For AWS) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux_NoVis.zip) (To watch the agent, you should follow the instructions to [enable a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md), and then download the environment for the Linux operating system above.)

### Step 3: Explore the Environment
After you have followed the instructions above, open Tennis.ipynb (located in the p3_collab-compet/ folder in the DRLND GitHub repository) and follow the instructions to learn how to use the Python API to control the agent.

## How to train a agent
Directly run the notebook within the online Workspace provided by Udacity Nanodegree for the  Project #3 Collaboration and Competition. Follow the instructuions in tennnis.ipynb to get started with training your own agent.

