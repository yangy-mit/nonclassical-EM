# nonclassical-EM
Implementation of nonclassical electromagnetic simulation in COMSOL Multiphysics

Nonclassical electromagnetic theory based on Feibelman *d* parameters has been developed for modeling nanoscale electromagnetic phenomena ([Yang, Yi, et al. "A general theoretical and experimental framework for nanoscale electromagnetism." Nature 576.7786 (2019): 248-252.](https://www.nature.com/articles/s41586-019-1803-1)). COMSOL Multiphysics implementation of the nonclassical electromagnetic theory has also been developed in this paper.

To faciliate the implementation of the nonclassical electromagnetic theory for various model setups, this repository includes an exemplary COMSOL model that is modified from the models developed in the aforementioned paper, with the following changes:
* Periodic boundary conditions
* Port excitation and full-field calculation
* Flexible auxiliary domain configuration
