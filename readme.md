
# Project Overview

For this project, you will train an agent to navigate (and collect bananas!) in a large, square world. 

## Project details
### State space and Action space

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:


    0 - move forward.
    1 - move backward.
    2 - turn left.
    3 - turn right.

### Reward

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas. 

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

## Getting Started

### Step 1: Clone the DRLND Repository
1. If you haven't already, please clone the DRLND GitHub repository.
2. Navigate to the `p1_navigation/` folder in the DRLND GitHub repository, and run the command below to obtain a few packages.
```
pip3 install -r requirements.txt
```

### Step 2: Download the Unity Environment
Next, please download the environment from one of the links below. You need only select the environment that matches your operating system:

* Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
* Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
* Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
* Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

Then, place the file in the p1_navigation/ folder in the DRLND GitHub repository, and unzip (or decompress) the file.

(For Windows users) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

### Step 3: Install ML-Agents

1. Clone the ML-Agents repository, and enter the python/ subdirectory:
```
    git clone https://github.com/Unity-Technologies/ml-agents.git
    cd ml-agents/python
```
2. Run the following command in a terminal to install the necessary dependencies:
```
    pip3 install .
```

### Step 4: Explore the Environment
After you have followed the instructions above, open `Navigation.ipynb` (located in the `p1_navigation/` folder in the DRLND GitHub repository) and follow the instructions to learn how to use the Python API to control the agent.


## Instructions
Follow the instructions in `Navigation.ipynb` to get started with training your own agent!  To use a Jupyter notebook, run the following command from the `p1_navigation/` folder:
```
jupyter notebook
```
and open `Navigation.ipynb` from the list of files.  Alternatively, you may prefer to work with the [JupyterLab](https://jupyterlab.readthedocs.io/en/latest/) interface.  To do this, run this command instead:
```
jupyter-lab
```
