**Pesticide Clustering for Drug Discovery**

This project demonstrates unsupervised clustering of pesticides using molecular descriptor data and dimensionality reduction (PCA and UMAP) techniques in Python.


**Overview**

Goal: Explore chemical diversity and identify structure–activity clusters using K-Means, PCA, and UMAP methods.


**Techniques:**


1. Feature standardization

2. Principal Component Analysis (PCA)

3. Uniform Manifold Approximation and Projection (UMAP)

4. K-Means clustering

5. Cluster member export for SAR analysis

Relevance: Mirrors real pharma pipelines for compound grouping, diversity analysis, and lead selection.


**Workflow:**

a. Import and preprocess pesticide dataset (PubChem).

b. Dimensionality reduction via PCA and UMAP.

c. Elbow method to determine optimal number of clusters.

d. K-Means clustering on the reduced feature space.

e. Visualization of clusters in 2D space.

f. Export cluster members to text files.


**Files:**

pesticide_clustering.ipynb — Main analysis notebook
Predict missing values.ipynb — Notebook for predicting missing values/null using Random Forest Regression

pesticides_data.csv — downloaded dataset from PubChem
pesticides_cleaned.csv - Removed unwanted columns/properties (Some missing values in LogP)
pesticides_new.csv - No missing-values/nulls

cluster_summary.txt — Cluster member lists

pesticide_clusters_pca.png, pesticide_clusters_umap.png — Cluster visualizations


**Usage**

Install required packages (see below).

Run notebook.ipynb or adapt code for your dataset.

Inspect cluster results and exported files.


**Requirements**

Python 3.x
pandas
numpy
matplotlib
scikit-learn
umap-learn


This project is open for educational and scientific use. Dataset provided as example only.
