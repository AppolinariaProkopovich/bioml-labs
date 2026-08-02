# OCT Image Classification

This project develops a binary classifier that distinguishes normal retinal optical coherence tomography (OCT) images from images showing disease.

## Workflow

- download and exploratory analysis of the Kermany2018 OCT dataset;
- conversion of four diagnostic labels into `NORMAL` and `DISEASE`;
- class-balance and train/test leakage checks;
- stratified train/validation splitting;
- transfer learning with a pretrained ResNet-50;
- class-weighted training and threshold-aware evaluation;
- sensitivity, specificity, precision, F1, ROC AUC, and PR AUC;
- Grad-CAM and Integrated Gradients for visual interpretation;
- discussion of dataset coverage and model limitations.

The evaluation prioritises sensitivity because missed pathological cases are particularly important in a screening-oriented binary task.

## Data and compute

The notebook downloads the [Kermany2018 OCT dataset](https://www.kaggle.com/datasets/paultimothymooney/kermany2018) through `kagglehub`. Kaggle authentication may be required. A CUDA-capable GPU is recommended for full training; the notebook also provides a reduced quick-run configuration.

## Notebook

[Open the analysis](analysis.ipynb)

This model is an educational demonstration and is not validated for clinical use.
