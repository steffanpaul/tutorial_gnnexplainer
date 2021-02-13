# tutorial_gnnexplainer

Prelinimary code for a tutorial on GNNExplainer to be prepared for the Zitnik lab github tutorials on GNNs. 

The repository contains:

- Tutorial draft 1.ipynb: the tutorial in a jupyter notebook
- goID_terms.tsv: reference table for GO annotations
- helper_functions.py: utility functions
- model_params: a folder for model parameter states. The tutorial comes with a file for a pretrained Graph Attention Network to be used when a gpu is not available for training.

Note about .gitignore: in the tutorial a dataset is downloaded into the root directory which is too large to commit. The .gitignore is already set to ignore the dataset file when making commits.
