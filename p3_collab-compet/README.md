[//]: # (Image References)


# Project 3: Collaboration and Competition

### Introduction

In this exercise, the tennis environment given by the Udacity project is used. The DDPG code is modified based on the DDPG-pendulum exercise. The agents each control a racket to try to bounce the ball over the net as many times as possible. If an agent hits the ball over the net, it receives a reward of +0.1.  If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01.  Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation.  Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping. 

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents).

The memory buffer is modified from the DDPG-pandulum version and allow copying a local memory of a given agent into the main memory. A local memory is kept for each of the agent and the winning agent's experience is selected to include in the experience replay for training.

### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

2. Place the file in the DRLND GitHub repository, in the `p3_collab-compet/` folder, and unzip (or decompress) the file. 

### Running the Code

1. This report is part of Calvin Chan's work on Udacity exercise as part of required submission of the Deep Reinforcement Learning course.  The code can be found in the github repository: https://github.com/calvinwy/deep-reinforcement-learning

2. This file is located in `p3_collab-compet` folder of the above repository.

3. Please make sure the environment described in the previous section is installed properly along with all required libraries: Pytorch, Numpy, gym 

4. Please open the `Report.ipynb` from Jupyter notebook to explore the report.

5. The demonstration of the environment was given by the Udacity template in section 1-3 of the report.

6. To train a model using the DDPG for continuous action, you can run all the code in section 4.  The latest model will be saved and overwrite the existing model file `checkpoint_actor.pth` and `checkpoint_critic.pth` for the actor and critic network respectively in the running folder.

7. To load and demonstrate the saved model, run code in section 5.