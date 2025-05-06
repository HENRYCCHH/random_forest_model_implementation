
# Random Forest from Scratch & Bagging Analysis

## Overview
This project presents an implementation of the Random Forest algorithm built entirely from scratch in Python. It not only constructs the ensemble by bootstrapping decision trees but also investigates the behavior and properties of bagging (bootstrap aggregating) to understand its impact on model stability, variance reduction, and overall predictive performance.

This project aims to:
- **Implement the core components** of a Random Forest without relying on libraries like scikit-learn.
- **Analyze the bagging mechanism** and its effects on the variance, bias, and robustness of the model.
- **Visualize and interpret** the behavior of individual trees within the ensemble and their aggregated predictions.

## Implementation Details
- **Decision Tree Construction:**  
  A decision tree algorithm is implemented from the ground up, including splitting criteria, tree growth, and pruning techniques.
  
- **Bagging (Bootstrap Aggregating):**  
  Multiple bootstrap samples are generated from the training dataset. Each sample is used to train an individual decision tree, ensuring diversity in the ensemble.
  
- **Random Forest Aggregation:**  
  The final prediction is made by aggregating the outputs of all decision trees (majority voting for classification or averaging for regression). This helps to reduce overfitting and improves generalization.

- **Investigation and Analysis:**  
  Detailed experiments are conducted to study:
  - The reduction in variance due to bagging.
  - The stability and consistency of the model with increasing ensemble size.
  - How individual trees contribute to the overall prediction.
  
- **Visualization and Metrics:**  
  Graphs and statistical metrics are provided to illustrate the behavior of the bagging process, such as error rates, variance trends, and feature importance.

## Features
- **From-Scratch Implementation:**  
  No high-level machine learning libraries were used for the core algorithm, ensuring a deep understanding of the Random Forest mechanics.
  
- **Bootstrap Sampling:**  
  Custom code for generating bootstrap samples and training multiple trees independently.
  
- **Random Feature Selection:**  
  Implemented to enhance model diversity and prevent overfitting.
  
- **Comprehensive Analysis:**  
  The project includes an investigation into the ensemble’s behavior, discussing key properties like bias, variance, and the impact of ensemble size.
  
- **Visualization Tools:**  
  Uses Python libraries (e.g., matplotlib, seaborn) to visualize training progress, error metrics, and the decision boundaries of individual trees and the aggregated model.

## Requirements
- **Python 3.x**
- **Jupyter Notebook** (to run and interact with the notebook)
- **Libraries:**  
  - numpy
  - pandas
  - matplotlib
  - seaborn


