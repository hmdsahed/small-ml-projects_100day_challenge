# Day 1 - Iris Flower Classification

## Objective
Classify iris flower species using machine learning.

## Dataset
The Iris dataset contains flower measurements for:
- Setosa
- Versicolor
- Virginica

Features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Machine Learning Algorithm
- K-Nearest Neighbors (KNN)

## Exploratory Data Analysis (EDA)
Performed:
- Statistical summary
- Pairplot visualization
- Correlation heatmap
- Boxplot analysis

## Experiments

| Feature Pair | Accuracy |
|---|---|
| Petal Length + Petal Width | 100% |
| Sepal Width + Petal Length | 93.33% |
| Sepal Length + Sepal Width | 83.33% |

## Key Findings
- Petal-related features are the strongest indicators for flower classification.
- Petal length and petal width achieved perfect classification accuracy.

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn