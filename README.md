# Clustering Performance Comparison using Wine Dataset

This project presents a comparative performance study of several clustering algorithms applied to the Wine dataset from the UCI repository. The study evaluates different preprocessing techniques and cluster counts using multiple evaluation metrics.

## Overview
This project implements a clustering performance analysis on the Wine dataset. We compare three clustering algorithms:
- **KMeans**
- **Hierarchical Clustering (Agglomerative)**
- **MeanShift**

For each algorithm, the analysis is performed using various preprocessing methods and different cluster counts (where applicable). The performance is evaluated using:
- **Silhouette Score**
- **Calinski-Harabasz Index**
- **Davies-Bouldin Index**

## Dataset
The project uses the Wine dataset, which can be loaded directly using scikit-learn's `load_wine()` function. The dataset comprises various chemical attributes of wines and is well-suited for clustering analysis.

## Preprocessing Techniques
We evaluate six different data preprocessing methods:
- **None**: Original data without preprocessing.
- **Normalization**: Using MinMaxScaler.
- **Transform**: Using RobustScaler.
- **PCA**: Reduce dimensions to 2 using PCA after standard scaling.
- **T+N**: RobustScaler followed by MinMaxScaler.
- **T+N+PCA**: Combination of transformation, normalization, and PCA (2 components).

- ![image](https://github.com/user-attachments/assets/17f1d4a2-ee7c-4f99-be24-705ea4f3bfd5)

