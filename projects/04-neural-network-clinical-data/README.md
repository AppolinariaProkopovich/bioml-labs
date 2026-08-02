# Neural Networks for Clinical Tabular Data

This project studies neural-network design choices for classification of patients from tabular clinical measurements related to pancreatic and urinary disease.

## Workflow

- preprocessing and train/test splitting;
- construction of a feed-forward network in PyTorch;
- monitoring training and validation behaviour;
- confusion-matrix analysis;
- comparison of weight decay settings;
- evaluation of batch normalisation;
- experiments with network depth, activation functions, and optimisers;
- comparison with a logistic-regression baseline.

Rather than reporting a single model, the notebook demonstrates how architecture and optimisation choices affect convergence and generalisation.

## Data

The notebook expects `urinary_disease.csv` in its working directory. The dataset is not redistributed here. To reproduce the analysis, obtain an authorised copy and verify that its column structure matches the preprocessing code.

## Notebook

[Open the analysis](analysis.ipynb)

This is an educational model and is not suitable for diagnosis or clinical decision-making.
