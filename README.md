# Breast Cancer Detection
## Overview:
This repository contains the code and documentation for my Breast Cancer Detection project. The aim of this project was to develop a robust classification system that can accurately detect breast cancer from a given set of features. I explored various machine learning models and evaluated their performance using different feature selection techniques.

## Dataset:
The dataset used in this project contains a collection of features extracted from breast cancer samples. The dataset is divided into a training set and a test set to effectively train and evaluate the models.

## Models Explored:
- Logistic Regression
- Decision Tree Classifier
- Gaussian Naive Bayes
- K Nearest Neighbours
- Neural Network
- Random Forest Classifier
- XGBoost

## Feature Selection Techniques:
Three different feature selection approaches were considered:
- **No Feature Selection:** In this approach, no feature selection was applied, and all features were used directly to train the models.
- **Variance Thresholding:** Features with low variance were removed, as they were unlikely to contribute significantly to the model's performance.
- **Manual Feature Selection:** I manually selected a subset of features based on domain knowledge and previous research, aiming to include only the most relevant features for the breast cancer detection task.

## Evaluation Metrics:
The performance of each model was evaluated using the following metrics:
- **Accuracy:** The proportion of correctly classified instances out of the total instances.
- **F1 Score:** The harmonic mean of precision and recall, providing a balance between the two metrics.
- **Precision:** The proportion of true positive predictions out of the total positive predictions.
- **Recall:** The proportion of true positive predictions out of all actual positive samples.
- **Balanced Accuracy:** The average of sensitivity (recall) and specificity, providing a balanced view of the model's performance.

## Conclusion:
Based on the results, we can draw insights into the performance of each model and the impact of different feature selection techniques. Further analysis and experimentation could be conducted to fine-tune the models and potentially enhance the overall performance.
