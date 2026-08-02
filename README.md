# Computational Biology and Biomedical Machine Learning Portfolio

A collection of six applied projects spanning population genetics, transcriptomics,
multi-omics integration, clinical machine learning, and medical imaging. The analyses
use public or externally obtained datasets and focus on reproducible exploration,
model evaluation, and biologically informed interpretation.

## Projects

| Project | Methods |
|---|---|
| [Breast cancer classification](projects/01-breast-cancer-classification/) | EDA, PCA, SMOTE, logistic regression, KNN, SVM, random forest, gradient boosting, XGBoost |
| [Population genetics with PCA](projects/02-population-genetics-pca/) | PLINK QC, MAF filtering, LD pruning, PCA, geographic metadata integration |
| [Bulk and single-cell RNA-seq](projects/03-rna-seq-analysis/) | Count filtering, normalisation, PCA, UMAP, Leiden clustering, marker exploration |
| [Neural networks for clinical data](projects/04-neural-network-clinical-data/) | PyTorch, regularisation, batch normalisation, architecture and optimiser comparisons |
| [Multi-omics integration](projects/05-multiomics-integration/) | MOFA, PCA, autoencoders, UMAP, CatBoost, survival metrics |
| [OCT image classification](projects/06-oct-image-classification/) | Transfer learning, ResNet-50, threshold analysis, Grad-CAM, Integrated Gradients |

Each project directory contains a notebook and a short description of its data,
workflow, and limitations. Large datasets and trained model files are not stored in
the repository.

## Environment

Install the locked Python environment with [uv](https://docs.astral.sh/uv/):

```bash
uv sync
uv run jupyter lab
```

Some projects additionally require external tools, dataset credentials, or substantial
compute. See the corresponding project README before running a notebook.

## Scope

These projects are educational research analyses. Models involving clinical or medical
data are not validated diagnostic or prognostic systems and must not be used for patient
care.

## Author

Appolinaria Prokopovich
