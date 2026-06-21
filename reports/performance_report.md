# Performance Report

## Overview

This project focused on evaluating and optimizing machine learning models using the Netflix dataset. The target variable was the content type (Movie or TV Show). The dataset was preprocessed, encoded, and divided into training and testing sets using an 80/20 split.

## Models Evaluated

Two baseline classification models were trained and tested:

1. Logistic Regression
2. Decision Tree Classifier

The performance of both models was evaluated using Accuracy, Precision, Recall, and F1-Score.

## Metric Selection

The following metrics were selected because this is a classification problem:

* **Accuracy:** Measures the overall percentage of correct predictions.
* **Precision:** Measures how many predicted positive instances were actually correct.
* **Recall:** Measures how many actual positive instances were correctly identified.
* **F1-Score:** Provides a balance between Precision and Recall.

These metrics provide a comprehensive evaluation of classification model performance.

## Baseline Model Comparison

The Logistic Regression and Decision Tree models were trained on the same dataset and compared using the selected evaluation metrics.

The model with the better overall performance was selected for further optimization.

## Hyperparameter Tuning

GridSearchCV was applied to the best-performing baseline model to identify the optimal parameter combination.

The following parameters were tuned:

* max_depth
* min_samples_split

The tuned model achieved improved performance compared to the baseline model.

## Key Findings

* Both models successfully classified Netflix content into Movies and TV Shows.
* Decision Tree provided strong classification performance.
* Hyperparameter tuning improved the model's predictive capability.
* Proper model evaluation is essential for selecting the most effective machine learning solution.

## Conclusion
This project demonstrated the complete workflow of model evaluation and optimization. By comparing baseline models and applying hyperparameter tuning, the final model achieved better performance and provided a deeper understanding of machine learning evaluation techniques.

