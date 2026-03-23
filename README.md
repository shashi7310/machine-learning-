# PCA vs Raw Features: Does Dimensionality Reduction Improve Classification?

## Overview

This project presents a tutorial exploring whether dimensionality reduction using **Principal Component Analysis (PCA)** can improve classification performance compared with using the original raw features.

The tutorial demonstrates how PCA transforms high-dimensional data into a smaller set of informative components while preserving most of the important variation in the dataset. The analysis also compares the predictive performance of models trained using the original features and PCA-transformed features.

This work was developed as part of an MSc Machine Learning tutorial assignment.

---

## Objectives

The tutorial aims to:

- explain the concept of **dimensionality reduction**
- demonstrate how **Principal Component Analysis (PCA)** works
- visualize high-dimensional datasets using principal components
- investigate whether PCA improves classification performance
- compare models trained on **raw features vs PCA features**

---

## Dataset

The analysis uses the **Breast Cancer Wisconsin Diagnostic Dataset**, available through the Scikit-learn library.

Dataset characteristics:

- 569 samples
- 30 numerical features
- binary classification problem
- target classes:  
  - **Malignant tumour**
  - **Benign tumour**

Dataset source:  
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html

---

## Methodology

The tutorial follows these main steps:

1. Load and explore the dataset
2. Standardize the feature values
3. Train a baseline classifier using the original features
4. Apply **Principal Component Analysis**
5. Analyze explained variance and dimensionality reduction
6. Train a classifier using PCA-transformed features
7. Compare classification performance between both approaches
8. Visualize the results using multiple plots

---

## Visualizations Generated

The notebook generates several figures used in the tutorial report:

- Target class distribution
- PCA cumulative explained variance
- PCA 2-D visualization of the dataset
- Explained variance by components
- Accuracy comparison between raw features and PCA features
- PCA feature contribution heatmap
- Confusion matrix of classification results

These visualizations help illustrate how dimensionality reduction affects the structure of the dataset and the performance of classification models.
