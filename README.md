# Antibody affinity modeling

This repository contains examples of how to work with AI models for protein design.

* `esmfold_multimer.ipynb` demonstrates how to predict the folding of an antibody sequence 
using [HuggingFace's ESMFold model](https://huggingface.co/facebook/esmfold_v1). This
model can be used to predict the folding on any protein.
* `antibody-affinity.ipynb` demonstrates how to load the antibody affinity dataset from
[TDCommons](https://tdcommons.ai/multi_pred_tasks/antibodyaff/) and train a 
neural network with PyTorch Lightning. (Currently the model makes very bad predictions.)

![antibody](https://upload.wikimedia.org/wikipedia/commons/3/3b/Inmunoglobulina.png)
A 3D model of an Immunoglobulin molecule, showing heavy chains in blue and light chains in green. 
By the National Library of Medicine. Public domain.

## Installation

1. Install miniconda
2. `conda env create -f environment.yml` to create the conda environment called `antibody-env`.
3. `conda activate antibody-env` to activate the conda environment.
4. `jupyter lab` to run a Jupyter Lab server. Click on the url in the output log.
5. Run the notebooks.

