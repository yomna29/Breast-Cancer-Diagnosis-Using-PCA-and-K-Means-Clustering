# Breast Cancer Diagnosis Using PCA and K-Means Clustering

## Overview
This project focuses on analyzing breast cancer data using unsupervised learning techniques. It applies Principal Component Analysis (PCA) for dimensionality reduction and K-Means clustering for grouping data points. Custom implementations of PCA and K-Means are compared with scikit-learn's implementations to evaluate performance.

## Features
- **Data Preprocessing**:
  - Data cleaning and scaling using `StandardScaler`.
  - Conversion of diagnosis labels to binary values.
- **Dimensionality Reduction**:
  - Custom PCA implementation for reducing data to 2D and 3D.
  - Comparison with scikit-learn's PCA.
- **Clustering**:
  - Custom K-Means implementation with configurable parameters.
  - Comparison with scikit-learn's K-Means clustering.
  - Elbow method for determining the optimal number of clusters.
- **Visualization**:
  - 2D and 3D scatter plots of PCA-transformed data.
  - Clustering results with centroids and cluster assignments.

## Requirements
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

## Usage
1. Clone the repository and navigate to the project directory.
2. Install the required libraries using:
   ```bash
   pip install -r requirements.txt
3.Run the notebook to execute the analysis pipeline:
  jupyter notebook srccode.ipynb
4. Visualize the clustering results and compare custom implementations with scikit-learn.
## File Structure
srccode.ipynb: Main notebook containing the complete analysis pipeline.
data.csv: Input dataset for the analysis.
## Results
PCA-transformed data visualized in 2D and 3D.

Clustering results with centroids and cluster assignments.

Comparison of custom and scikit-learn implementations of PCA and K-Means.

