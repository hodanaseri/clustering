# Clustering and Dimensionality Reduction

## Overview

This project explores clustering techniques on both synthetic and real-world datasets. The main objectives are:

1. **Random Clustering:** Perform random clustering on 1500 to 2500 samples within a two-dimensional coordinate plane using different values of k.
2. **Breast Cancer Dataset Analysis:**
   - Interpret the structure and features of the Breast Cancer dataset.
   - Apply k-means clustering to the dataset after removing labels.
   - Perform dimensionality reduction using PCA (Principal Component Analysis) and then apply k-means clustering again.
   - Determine the optimal value of k through iterative trials.

## Clustering on Random Data

### Steps

1. **Generate Random Data:** Create random samples in a two-dimensional plane, with a sample size ranging between 1500 to 2500.
2. **Clustering:** Apply k-means clustering for at least four different values of k.
3. **Visualization:** Display the clustering results in a suitable graphical form (e.g., scatter plots).

### Requirements

- Python 3.x
- NumPy
- Matplotlib
- scikit-learn



# Breast Cancer Dataset Analysis

1. **Data Interpretation:**
   - Explore the overall structure and characteristics of the Breast Cancer dataset.
   - Provide an interpretation of the dataset’s features and the distribution of values.

2. **K-means Clustering:**
   - Remove labels from the dataset.
   - Apply k-means clustering with various k values.
   - Report the clustering results and identify the most suitable value of k.

3. **Dimensionality Reduction with PCA:**
   - Apply PCA to the dataset for dimensionality reduction.
   - Run k-means clustering on the reduced dataset.
   - Report and compare results, determining the optimal value of k.
