# Data Learning meets Computational Modelling: Successfully using Physics-Informed Neural Networks for Biomedical Applications
## A MICCAI 2024 tutorial in Marrakesh, Morocco (6th October 2024)

### Overview:
This tutorial aims to provide an introduction to physics-informed neural networks (PINNs) using examples from medical imaging. It is expected that by the end of the session attendees will be able to use PINNs to solve their own problems related to medical imaging and beyond. PINNs are a type of deep learning framework that explicitly incorporates physical equations into the learning process as a regulariser, such that the network approximates the data whilst conforming to the equations and associated boundary and initial conditions. This enables them to learn with a relatively small amount of data compared to conventional neural networks and provides trust that the NNs' inferences obey the known physics laws. 

The tutorial will:
- Introduce the architecture of PINNs and their unique advantages and potentialities for medical problems.
- Compare PINNs with conventional neural networks, numerical solvers for ordinary and partial differential equations (ODEs, PDEs) and model parameterisation methods, highlighting their advantages as well as spaces for development.
- Demonstrate how PINNs can be used in forward mode to solve differential equations; and inverse mode to estimate model parameters, with examples related to biomedical applications.
- Introduce operator learning with physics-informed DeepONets, where we learn the solution operator of parametric PDEs (maps between infinite dimensional function spaces) instead of functions (maps between finite dimensional vector spaces). This could be useful for surrogate modelling.
- Discuss opportunities for PINNs in the biomedical setting.

In addition, there will be a hands-on code-based session that covers examples from cardiovascular medicine and neuroscience. In detail:
- ODE example: Given some experimental data, use PINNs to parameterise a popular ODE-based model of cardiac electrophysiology -- the single-cell Fenton-Karma model.
- PDE example: Given some electroencephalographic (EEG) signals, use PINNs to solve the Poisson PDE and locate the electrical sources of the measured signals.
- Operator learning example: Use PINNs to learn the solutions to the 2D diffusion eikonal equation using as inputs Gaussian Random Fields that represent the likely distributions of activation times in the heart.

### Organising Team:
Marta Varela (National Heart and Lung Institute, Imperial College London), Ching-En Chiu (Department of Electrical and Electronic Engineering, Imperial College London), Christoforos Galazis (National Heart and Lung Institute, Imperial College London), Yu Hon On (National Heart and Lung Institute, Imperial College London), Danilo Mandic (Department of Electrical and Electronic Engineering, Imperial College London), Phil Livermore (School of Earth and Environment, University of Leeds), Zack Xuereb Conti (Data-Centric Engineering / TRIC:DT, The Alan Turing Institute, London)
