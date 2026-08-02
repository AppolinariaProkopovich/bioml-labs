# Multi-omics Integration and Survival Modelling

This project compares approaches for integrating multiple molecular data modalities and evaluates whether the resulting latent representations are informative for survival modelling.

## Workflow

- loading and harmonising molecular and clinical data;
- scaling and alignment of samples across modalities;
- baseline dimensionality reduction with PCA;
- latent-factor modelling with MOFA;
- representation learning with autoencoders;
- UMAP visualisation of latent spaces;
- CatBoost regression with and without clinical covariates;
- evaluation using MAPE and the concordance index;
- sensitivity analysis of MOFA convergence and autoencoder training duration.

The notebook discusses an important modelling distinction: accurate prediction of survival time and correct ranking of patients by risk are related but not equivalent objectives.

## Data and compute

The analysis expects locally available multi-omics matrices and clinical data. These files are not included. MOFA and neural-network experiments may require substantial memory and execution time.

## Notebook

[Open the analysis](analysis.ipynb)

The survival analysis is methodological and is not a validated prognostic model.
