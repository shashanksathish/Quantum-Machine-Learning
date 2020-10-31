# Quantum Machine Learning

This repo contains three projects on Quantum Machine Learning for Generative Modeling 
1. Fair and Biased Coin Toss
2. Entanglement Generator 
3. Quantum Circuit Born Machine (QCBM) 

For Project 3, there are two helper scripts for utility functions (utils.py) and our classical optimizer (pso.py). Please make sure these are in the same folder as the Project 3 script in order to ensure that you can import functions from these scripts. 

## Installation 

Installation Requirements: 
- Python 3.7 (at least) 
- Python Package NumPy 
- Python Package random2
- Python Package Matplotlib 
- Jupyter Lab or Notebook 
- PyQuil 
- Quilc 
- Rigetti QVM 

Installation Instructions: 

If not already installed, please install at least Python Version 3.7. Instructions on installing Python can be found here: https://www.python.org/downloads/. Along with Python 3.7, please install the Python package NumPy. Instructions can be found here: https://numpy.org/install/. Please install the package random2 with instructions found here: https://pypi.org/project/random2/. Please install the package Matplotlib with instructions found here: https://pypi.org/project/matplotlib/. 

If not already installed, please install Jupyter Notebook or Jupyter Lab prior to this workshop. Instructions on installing Jupyter can be found here: https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html. 

You can utilize the package manager 'pip' to install Jupyter Lab with 'pip install jupyterlab'.

The last thing you'll need to install is PyQuil. PyQuil is a Python library for quantum programming using Quil, the quantum instruction language developed at Rigetti Computing. Installation instructions can be found here: https://pyquil-docs.rigetti.com/en/stable/start.html. 

PyQuil can be installed using 'pip install pyquil'. PyQuil, along with quilc, the QVM, and other libraries, make up what is called the Forest SDK. To make full use of pyQuil, you will need to additionally have installed quilc and the Quantum Virtual Machine (QVM). These can be downloaded together directly from here: https://qcs.rigetti.com/sdk-downloads. 

# Start Up

First, open up two separate terminal windows for the quilc compiler and the qvm. 
In the first terminal type 'qvm -S'.
In the second terminal type 'quilc -S'

Then open the Jupyter Notebook and run the Project




