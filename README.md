# HelpHunch: Clustering of Countries

## Overview

This project aims to categorize countries based on socio-economic and health factors, utilizing unsupervised learning techniques. The primary objective is to identify countries in need of the most help by analyzing clusters formed through KMeans, Hierarchical, and DBSCAN clustering.

## Dataset

The project utilizes a dataset containing socio-economic and health-related indicators for various countries. The dataset includes features such as child mortality, inflation, life expectancy, income, health index, and GDP.


## Clustering Techniques

### 1. KMeans Clustering

- KMeans is employed to divide the dataset into K clusters, where K is a pre-specified number of clusters.
- Features are selected using Principal Component Analysis (PCA) to identify those with the highest variability.
- The Elbow Method is used to determine the optimal number of clusters.

### 2. Hierarchical Clustering

- Hierarchical clustering is performed using the Agglomerative approach.
- The number of clusters is determined by examining a dendrogram generated through Ward's method.

### 3. DBSCAN Clustering

- DBSCAN (Density-Based Spatial Clustering of Applications with Noise) is used for density-based clustering.
- The epsilon (ε) and min_samples parameters are determined to identify core, border, and noise points.

## Evaluation Metrics

- Silhouette Score and Davies Bouldin Score are employed to evaluate the performance of each clustering technique.

## Conclusion

The project concludes by selecting KMeans clustering as the final model based on the highest Silhouette Score and lowest Davies Bouldin Score. The clusters are interpreted to identify countries in different developmental categories, ranging from underdeveloped to developed. Practical insights and recommendations are derived based on the clustering results.


