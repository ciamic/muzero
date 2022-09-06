# MuZero

 [Implementation of the MuZero algorithm](https://medium.com/@_michelangelo_/alphazero-for-dummies-5bcc713fc9c6 "Implementation of the MuZero algorithm")
 
## Introduction
This repo contains: 
- a simple but working implementation of the MuZero algorithm 
- an agent trained using the MuZero algorithm to play an openAI gym game (CartPole-v1)

### Project details

The code is an implementation of the official [MuZero pseudocode](https://arxiv.org/src/1911.08265v1/anc/pseudocode.py "MuZero pseudocode").

This is an implementation of an agent that uses MuZero in order to play the openAI gym game of CartPole.

### Getting Started

Execute the code in the notebook to train the agent! 

### Dependencies

To set up your python environment to run the code in this repository, follow the instructions below.

1. Create (and activate) a new environment with Python 3.6.

	- __Linux__ or __Mac__: 
	```bash
	conda create --name MuZero python=3.6
	source activate MuZero
	```
	- __Windows__: 
	```bash
	conda create --name MuZero python=3.6 
	activate MuZero
	```

3. Clone the repository, and then, install the required packages (see requirements).
```bash
git clone https://github.com/ciamic/MuZero.git
```

4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `MuZero` environment.  
```bash
python -m ipykernel install --user --name MuZero --display-name "MuZero"
```

5. Before running code in a notebook, change the kernel to match the `MuZero` environment by using the drop-down contextual `Kernel` menu. 

### Requirements

- `Python 3`
- `numpy`
- `matplotlib`
- `gym`
- `Tensorflow`

