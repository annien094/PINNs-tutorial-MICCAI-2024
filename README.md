# Data Learning meets Computational Modelling: Successfully using Physics-Informed Neural Networks for Biomedical Applications
### A MICCAI 2024 tutorial in Marrakesh, Morocco 🇲🇦 

Date: 6th October 2024 <br>
Time: 8:00am-12:30pm <br>
Location: Room Amandier, Conference Centre 

## Overview:
This tutorial aims to provide an introduction to physics-informed neural networks (PINNs) using examples from biomedical applications. It is expected that by the end of the session attendees will be able to use PINNs to solve their own problems related to medical imaging and beyond. PINNs are a type of deep learning framework that explicitly incorporates physical equations into the learning process as a regulariser, such that the network approximates the data whilst conforming to the equations and associated boundary and initial conditions. This enables them to learn with a relatively small amount of data compared to conventional neural networks and provides trust that the NNs' inferences obey the known physics laws. 

In this tutorial, we:
- Give an introduction to PINNs, including:  
  - the motivation and types of problems of interest
  - the architecture of a PINN
  - some considerations when designing PINNs
- Demonstrate how PINNs can be used in forward mode to solve differential equations; and inverse mode to estimate model parameters, with examples related to biomedical applications.
- Discuss opportunities and advantages for PINNs in the biomedical setting.
- Dicuss drawbacks of PINNs and recent developments to address them, including:
  - difficulties in converging
  - difficulties with long time ranges
  - difficulties with complicated geometries
  - generalisibility


In addition, there are two hands-on exercises that cover examples from neuroscience and cardiovascular medicine. In detail:
1. 🧠 ODE example: Estimate cerebral perfusion in an infant using data from arterial spin labelling (ASL) MRI.
2. 🫀 PDE example: Model the propagation of electrical signals in cardiac tissue in a 2D rectangular geometry, using the Aliev-Panfilov model.

## What's included in the repository
1. Presentation slides: [`PINNsTutorial1_Oct2024.pdf`](PINNsTutorial1_Oct2024.pdf) and [`PINNsTutorial2_Oct2024.pdf`](PINNsTutorial2_Oct2024.pdf)
2. Two hands-on tutorial exercises: 🧠[`PINNs_ASL.ipynb`](PINNs_ASL.ipynb) and 🫀[`PINNs_AP2D.ipynb`](PINNs_AP2D.ipynb)
3. Data used in the second tutorial exercise: [`APdata.mat`](APdata.mat)

Suggested workflow: [`PINNsTutorial1_Oct2024.pdf`](PINNsTutorial1_Oct2024.pdf) ▶️ [`PINNs_ASL.ipynb`](PINNs_ASL.ipynb) ▶️ [`PINNs_AP2D.ipynb`](PINNs_AP2D.ipynb) ▶️ [`PINNsTutorial2_Oct2024.pdf`](PINNsTutorial2_Oct2024.pdf).

## Related work
We also encourage you to have a look at the work [`PINNing Cerebral Blood Flow`](https://github.com/cgalaz01/supinn) and [`PINNs for cardiac electrophysiology in 3D and fibrillatory conditions`](https://arxiv.org/pdf/2409.12712), for examples in more complex scenarios and in-depth discussions of how PINNs could be useful in biomiedical applications.

## Organising Team:
Marta Varela (National Heart and Lung Institute, Imperial College London), <br>
Annie Ching-En Chiu (Department of Electrical and Electronic Engineering, Imperial College London),<br>
Christoforos Galazis (National Heart and Lung Institute, Imperial College London), <br>
Yu Hon On (National Heart and Lung Institute, Imperial College London), <br>
Danilo Mandic (Department of Electrical and Electronic Engineering, Imperial College London), <br>
Phil Livermore (School of Earth and Environment, University of Leeds),<br>
Zack Xuereb Conti (Data-Centric Engineering / TRIC:DT, The Alan Turing Institute, London)

### Contact
Feel free to reach out at marta.varela@imperial.ac.uk or ching-en.chiu18@imperial.ac.uk if you have any questions or feedback on this tutorial! We hope you enjoy(ed) it 🙂.
