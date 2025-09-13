# scRNA-seq-Project-Normal-Vs-Tumor

Mini scRNA-seq Project: Normal vs Tumor Epithelial Cells
Project Overview

This mini-project explores single-cell RNA sequencing (scRNA-seq) data from a breast cancer study, focusing on transcriptional differences between normal and tumor epithelial cells.

The analysis demonstrates key steps in scRNA-seq workflows including:

Data preprocessing & quality control

Normalization & selection of highly variable genes

Dimensionality reduction & clustering

Differential expression analysis

Exploration of gene expression patterns in normal vs tumor epithelial cells

Application of machine learning techniques for predictive modeling

Dataset Description

The dataset comes from the publicly available breast cancer dataset GSE161529
 in the Gene Expression Omnibus (GEO).

Raw data file: GSE161529_RAW.tar

Source: Breast cancer scRNA-seq samples

Selected Subset for This Project

To simplify the workflow and ensure manageable computation, four epithelial samples were chosen:

Normal epithelial cells

GSM4909255_N-N280-Epi

GSM4909256_N-PM0095-Epi

Tumor epithelial cells

GSM4909281_TN-MH0126

GSM4909282_TN-MH0135

This subset allows focused comparison of tumor vs normal epithelial cells while retaining biological significance.

Analysis Pipeline

The notebook covers:

Quality Control – filtering low-quality cells and genes

Normalization – scaling and transformation of raw counts

Feature Selection – identification of highly variable genes

Dimensionality Reduction – PCA, UMAP/t-SNE

Clustering – detection of cell populations

Differential Expression – comparison between normal and tumor epithelial cells

Visualization – expression heatmaps, violin plots, cluster maps

Machine Learning (optional) – predictive modeling based on gene expression
