# Population Genetics with PCA

This project explores genetic structure among Angolan and other African populations using genotype data and principal component analysis.

## Workflow

- genotype quality control with PLINK;
- filtering of rare variants by minor allele frequency;
- linkage-disequilibrium pruning before PCA;
- calculation and visualisation of principal components;
- comparison of population clusters;
- integration of geographic metadata;
- analysis of relationships between principal components and latitude/longitude.

The project demonstrates why geographic proximity does not necessarily imply genetic similarity and how data preprocessing affects population-genetic inference.

## Requirements

The notebook downloads or expects genotype and metadata files used in the analysis. PLINK 1.9 is also required; its installation commands are included in the notebook. Large genotype files and derived PLINK outputs are excluded from Git.

## Notebook

[Open the analysis](analysis.ipynb)

Population-level patterns should not be interpreted as deterministic properties of individuals, and conclusions remain specific to the sampled populations and variants.
