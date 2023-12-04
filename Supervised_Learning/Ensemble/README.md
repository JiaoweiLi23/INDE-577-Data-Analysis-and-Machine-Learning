
# Ensemble Methods

This Jupyter notebook explores the use of ensemble methods in machine learning, with a focus on Bagging and Random Forests. The analysis is conducted on the 'Palmer Penguins' dataset, available on Kaggle. 

## Dataset

The 'Palmer Penguins' dataset includes various measurements of penguin species. In our study, we focus on the Gentoo species, using 'Sex' as the dependent variable and two features: 'culmen_length_mm' and 'culmen_depth_mm'.

## Ensemble Methods Covered

1. **Bagging**: A technique that involves training the same model on different subsets of the training data and aggregating the outputs.
2. **Random Forests**: An extension of Bagging applied to Decision Trees, creating a 'forest' of trees whose predictions are combined for the final output.

## Analysis Overview

- Data preprocessing and exploratory analysis.
- Implementation of Decision Tree, Bagging, and Random Forest classifiers.
- Evaluation of classifiers using metrics like precision, recall, f1-score, and confusion matrices.
- Visualization of decision regions for each classifier.
- Comparison of the classifiers based on performance, variance and bias, overfitting, and computational complexity.

## Conclusion
- Ensemble methods, particularly Random Forests, tend to outperform single Decision Trees in terms of accuracy.
- Bagging and Random Forests show better resistance to overfitting compared to single Decision Trees.
- There's a trade-off between model complexity and interpretability when moving from Decision Trees to Random Forests.


