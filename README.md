# CryptoClustering
Module 19 Joe Almendarez

This repository contains a Jupyter Notebook that performs clustering analysis on cryptocurrency market data. The notebook uses various data preprocessing and machine learning techniques to group cryptocurrencies into clusters based on their market behavior.

## Overview

The notebook follows these main steps:

1. **Data Preprocessing**:
   - Load and clean the cryptocurrency market data from a CSV file.
   - Scale the data to ensure all features contribute equally to the analysis.

2. **Principal Component Analysis (PCA)**:
   - Reduce the dimensionality of the data using PCA to simplify the clustering process while retaining most of the important information.

3. **K-Means Clustering**:
   - Determine the optimal number of clusters using the Elbow method.
   - Apply the K-Means algorithm to the scaled and PCA-transformed data to group the cryptocurrencies into clusters.

4. **Visualization**:
   - Visualize the clusters using scatter plots to analyze the grouping of cryptocurrencies.
