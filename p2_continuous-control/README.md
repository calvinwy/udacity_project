[//]: # (Image References)


# Project 2: Continuous Control

### Introduction

This project is based on the Udacity DDPG exercise and applied on the double-jointed arm target reaching environment. The DDPG code is modified based on the DDPG-pendulum exercise. The continuous control of a double-jointed arm is trained to move towards target locations. The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

### Getting Started

For this exercise the second version contains 20 identical agents is used.  

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:

    - **_Twenty (20) Agents_**
        - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
        - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
        - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
        - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.


2. Place the file in the DRLND GitHub repository, in the `p2_continuous-control/` folder, and unzip (or decompress) the file. 

### Running the Code

1. This report is part of Calvin Chan's work on Udacity exercise as part of required submission of the Deep Reinforcement Learning course.  The code can be found in the github repository: https://github.com/calvinwy/deep-reinforcement-learning

2. This file is located in `p2_continuous-control` folder of the above repository.

3. Please make sure the environment described in the previous section is installed properly along with all required libraries: Pytorch, Numpy, gym 

4. Please open the `Report.ipynb` from Jupyter notebook to explore the report.

5. The demonstration of the environment was given by the Udacity template in section 1-3 of the report.

6. To train a model using the DDPG for continuous action, you can run all the code in section 4.  The latest model will be saved and overwrite the existing model file `checkpoint_actor.pth` and `checkpoint_critic.pth` for the actor and critic network respectively in the running folder.

7. To load and demonstrate the saved model, run code in section 5.