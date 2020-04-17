[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation

### Introduction

This project is based on the Udacity DQN exercise and applied on the banana collection game. The state space with 37 dimensions output from the Unity environment is extracted and feed into the Deep Q-Learning algorithm to train an agent to collect as many yellow banana and avoid blue banana as much as possible.



### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.
    
    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Place the file in the DRLND GitHub repository, in the `p1_navigation/` folder, and unzip (or decompress) the file. 

### Running the Code

1. This report is part of Calvin Chan's work on Udacity exercise as part of required submission of the Deep Reinforcement Learning course.  The code can be found in the github repository: https://github.com/calvinwy/deep-reinforcement-learning

2. This file is located in `p1_navigation` folder of the above repository.

3. Please make sure the environment described in the previous section is installed properly along with all required libraries: Pytorch, Numpy, gym 

4. Please open the `Report.ipynb` from Jupyter notebook to explore the report.

5. The demonstration of the environment was given by the Udacity template in section 1-3 of the report.

6. To train a model using thie DQN, you can run all the code in section 4.  The latest model will be saved and overwrite the existing model file `qnetwork_checkpoint.pth` in the running folder.

7. To load and demonstrate the saved model, run code in section 5.