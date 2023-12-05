
# Principal Component Analysis (PCA) 

## Overview
This Jupyter notebook implements Principal Component Analysis (PCA), a powerful technique for dimensionality reduction in data science and machine learning. PCA simplifies high-dimensional datasets by transforming them into a set of orthogonal components that capture the most variance.

## Dataset Description
The dataset used in this analysis is from the Framingham Heart Study, aimed at predicting the 10-year risk of coronary heart disease (CHD) in patients. It includes over 4,000 entries with 15 attributes, such as age, gender, cholesterol levels, and blood pressure.

## Algorithm

### 1. Data Preprocessing
- **Standardization**: The dataset was standardized to have a mean of 0 and a standard deviation of 1, ensuring that PCA is not affected by the scale of the data.

### 2. PCA Steps
- **Covariance Matrix Computation**: Calculation of the covariance matrix to understand how variables in the data are related.
- **Eigenvalue and Eigenvector Calculation**: Determination of eigenvalues and eigenvectors from the covariance matrix.
- **Component Selection and Transformation**: Selection of principal components based on explained variance and transformation of the dataset.

### 3. Visualization
- **Scree Plot**: Display of the explained variance ratio for each principal component to understand their contributions.
- **2D Scatter Plot**: Visualization of the data in the first two principal components.

### 4. Using Built-in PCA Function
- Demonstration of PCA implementation using the built-in function in the scikit-learn package.

## Limitations and Considerations
- PCA assumes linear relationships in the data and may not capture complex, non-linear interactions.
- The interpretation of principal components can be less intuitive than the original features.

## Conclusion
PCA serves as a valuable tool for data simplification, particularly in high-dimensional datasets, facilitating more efficient data analysis and visualization. It's essential, however, to apply PCA with an understanding of its assumptions and limitations.
