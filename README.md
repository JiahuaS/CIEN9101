# CIEN9101
The summary of research on PINN for discovering PDE based on given data on Spring 2024 supervised by Zhaobin Mo

# Summary
Physics-informed neural network (PINN) or Physics-informed deep learning is a new topic in machine learning. The fundamentals of PINN originated from the work of Marziar Raissi of Prof. George Karniadarkis' group in 2017 titled: Physics Informed Deep Learning:Data-driven Solutions of Nonlinear Partial Differential Equations \citep{RAISSI2019686}. It was later accepted by the Journal of Computational Physics. The complete work is separated into two main parts. One is an inverse problem; one is a forward problem. In this paper, we will introduce a new method for discovering the partial differential equations (PDE) by using the PINN method, find some interesting points raised from other related papers, and further extensions on the papers we are interested in for finding new PDEs based on the dataset, and do some code realizations for my new method as much as I can.  

The code part is "NTM_Code_Part.ipynb", the paper is "manuscript.tex".

# Weekly Work Summary 
## Apr 19 - May 15, 2024
Finished the research work of Nontrivial Transform Method. 
Produced a paper talking about the theory part and realized the NTM in python. 
Paper named:  Nontrivial Transform Method in Physics-Informed Deep Learning Discovering Partial Differential Equations

## Apr 6 - Apr 19, 2024
Attendees: Zhaobin Mo, Jiahua Song
Focus on paper on learning pde equations, instead of solutions (Determine the inverse problem). 
Read and understand the work of Rassi's work: https://maziarraissi.github.io/PINNs/
Revisit https://arxiv.org/abs/2207.00529, and https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.4.023174
Read the new papers: https://www.science.org/doi/10.1126/sciadv.1602614, and https://arxiv.org/abs/2111.03794
Figure out the idea of finding PDE and construct a new way in theory.
 
## Feb 25 - Apr 6, 2024
Attendees: Zhaobin Mo, Jiahua Song
More relevent papers about using symbolic regression for learning/discovering partial differential equations
One relevant paper: https://arxiv.org/pdf/2303.07009.pdf 
https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.4.023174 
https://openreview.net/pdf?id=zjbSx8-m1wJ 


## Feb 25, 2024 | Jiaohua/Zhaobin chat
Attendees: Zhaobin Mo, Jiahua Song

Discussed two papers:
Physics-constrained symbolic model discovery for polyconvex incompressible hyperelastic materials
Discovering interpretable elastoplasticity models via the neural polynomial method enabled symbolic regressions
A state-of-the-art paper:
https://arxiv.org/pdf/2303.06833.pdf
Our proposed method (just a whole picture):
https://arxiv.org/pdf/2210.01741.pdf
Follow the SOTA paper above; only follow the training part.


