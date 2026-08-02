# Bulk and Single-Cell RNA-seq Analysis

This project investigates transcriptional changes in acute myeloid leukaemia using both bulk and single-cell RNA sequencing.

## Questions

- How does azacitidine treatment change gene-expression profiles in the HL-60 cell line over time?
- Are biological replicates consistent within treatment groups?
- What cellular heterogeneity and marker patterns can be identified in a single-cell AML sample?

## Workflow

The bulk RNA-seq section filters and normalises a count matrix, selects variable genes, applies PCA, and compares within-group and between-group distances. The single-cell section performs quality-aware preprocessing, normalisation, feature selection, PCA, neighbourhood construction, UMAP, clustering, and marker exploration with Scanpy.

## Data

The analysis is based on public GEO studies:

- `GSE184891` — bulk RNA-seq of myeloid leukaemia cells exposed to azacitidine;
- `GSE116256` — single-cell RNA-seq of AML bone-marrow samples.

Processed input files are not stored in this repository. Download the relevant files from [NCBI GEO](https://www.ncbi.nlm.nih.gov/geo/) and adapt the paths in the notebook if necessary.

## Notebook

[Open the analysis](analysis.ipynb)
