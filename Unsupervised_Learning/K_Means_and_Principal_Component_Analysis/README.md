# K-Means Clustering 

## Overview
This Jupyter notebook presents a comprehensive analysis using the K-Means clustering algorithm. K-Means is an unsupervised machine learning technique used to identify clusters within a dataset. Our analysis focuses on partitioning the dataset into distinct, non-overlapping subgroups or 'clusters'.

## Data Source
The dataset used is 'Palmer Penguins', which is publicly available on Kaggle. It was originally collected and provided by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER. The dataset includes three penguin species: Adelie, Chinstrap, and Gentoo.

## Features
The primary features considered for clustering include:
- bill Length (mm)
- bill Depth (mm)

## Implementation
The notebook covers the following key steps in K-Means clustering:
1. **Data Preprocessing**: Standardization and encoding of the dataset.
2. **Choosing Initial Centroids**: Arbitrarily setting the initial centroids for clustering.
3. **Defining Functions**: Implementation of functions for distance calculation, label assignment, and centroid updating.
4. **K-Means Algorithm**: Custom implementation of the K-Means clustering algorithm.
5. **Elbow Method**: Determining the optimal number of clusters using the Elbow Method.

## Results
The notebook concludes with visualizations comparing the original data labels with the clustering results from our K-Means implementation.

## Limitations and Considerations
- The need to predefine the number of clusters (k).
- Sensitivity to the initial placement of centroids.
- Assumption of spherical and evenly sized clusters, which may not always hold true.

## Conclusion
The K-Means algorithm, while efficient and effective for large datasets, has its limitations. It is essential to consider these along with the dataset's nature when interpreting the results.
