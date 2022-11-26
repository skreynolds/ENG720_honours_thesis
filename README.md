<img src="https://www.cdu.edu.au/images/cdu-logo-og.jpg" alt="Charles Darwin University - ENG720 Honours Thesis" width="200" />

# ENG720 Honours Thesis

Final assessment for Bachelor of Engineering (Electrical). Thesis presents a case for automatic generation control of a two area power system using a deep reinforcement learning agent. The developed model is compared against classical control techniques.

The assessment for Part A of the thesis is made up of the following items:

1. Research proposal
2. Literature review
3. Interim report
4. Poster presentation

As I undertake my research, I am maintaining a blog in which I hope to summarise the important aspects on my research in a less formal language. A link to the blog can be found [here](https://skreynolds.github.io/).

## MATLAB Simulation
Work has been undertaken to develop a selection of power systems models with load frequency controllers. These were built for experimentation purposes using MATLAB and Simulink to replicate research papers, understand different model architectures, test model parameters, or try different classical control schemes for the AGC/LFC problem.

A link to the reposistory containing this work can be found [here](https://github.com/skreynolds/ENG720_matlab_models).

## Python Simulation
A key part of this thesis work is simulation in an environment which has an existing DRL toolset - because building that from scratch would be hard. MATLAB is easy to simulate things in, but doesn't have simple access to the OpenAI gym, developed in Python. Single area and two area power system models have been created in a Python environment. Models are expressed as a system of ordinary differential equations, and simulations are undertaken using Pythons Scipy odeint (which is originally from FORTRAN, apparently).

The link to this repository is [here](https://github.com/skreynolds/ENG720_python_models).
