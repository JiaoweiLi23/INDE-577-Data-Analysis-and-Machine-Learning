# K-Nearest Neighbors (KNN) 

## Introduction
This Jupyter notebook presents a comprehensive analysis using the K-Nearest Neighbors (KNN) algorithm, a fundamental approach in machine learning for classification and regression tasks. KNN is characterized as a non-parametric, lazy learning algorithm, making no explicit assumptions about the data's functional form and requiring no training phase. Our study focuses on applying KNN to predict the 10-year risk of coronary heart disease (CHD) using a dataset from a continuous cardiovascular study.

## Algorithm
The notebook explores the KNN algorithm, detailing its core concept, implementation, and impact of varying the number 'K' of nearest neighbors. Key aspects include:
- **Defining 'K'**: Selection of nearest neighbors.
- **Distance Measure**: Employing Euclidean distance to compute similarities.
- **Finding Nearest Neighbors**: Identifying 'K' closest samples in the training dataset.
- **Considerations**: Addressing the choice of 'K', distance metric, scaling, curse of dimensionality, and data quality.

## Dataset
We utilize the Framingham Heart Study dataset, available on Kaggle. It comprises over 4,000 entries with 15 different attributes, aiming to forecast the 10-year risk of CHD in patients.

## Implementation and Results
The notebook includes a custom implementation of the KNN algorithm. Key steps involve:
- Data preprocessing and scaling.
- Implementing the KNN algorithm from scratch.
- Evaluating the model's accuracy with K=5 and experimenting with different values of K to observe the impact on prediction accuracy.
The results indicate the importance of selecting an appropriate 'K' value and how it influences the model's performance.

## Visualization
A plot demonstrates how classification accuracy varies with different 'K' values, highlighting the trade-off between underfitting and overfitting.

## Advantages and Disadvantages
The notebook concludes with a discussion on the strengths and limitations of the KNN algorithm, including its simplicity, ease of implementation, and challenges with large datasets and high-dimensional data.

## Conclusion
The final section summarizes the practicality of KNN in machine learning, especially for smaller datasets, and underscores the importance of parameter selection, data scaling, and computational considerations.


