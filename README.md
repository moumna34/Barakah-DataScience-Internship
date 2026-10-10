# Barakah-DataScience-Internship
# Applied Data Science Project: Titanic Survival Prediction

## Overview
This repository contains an end-to-end Data Science project completed during the Barakah TechLabs Internship. It covers Exploratory Data Analysis (EDA), Feature Engineering, and Machine Learning Classification.

## Project Tasks Executed
* **Task 1: Comprehensive EDA:** Imputed missing values, handled outliers, and analyzed demographic distributions.
* **Task 2: Feature Engineering & Selection:** Extracted passenger titles, created family size metrics, and mapped feature correlations.
* **Task 6: Classification Modeling:** Trained and evaluated Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting models.

## Model Performance Comparison
| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Gradient Boosting** | **82.68%** | **0.81** | **0.74** | **0.77** | **0.88** |
| Random Forest | 81.01% | 0.79 | 0.73 | 0.76 | 0.87 |
| Logistic Regression | 80.45% | 0.77 | 0.74 | 0.75 | 0.86 |
| Decision Tree | 78.21% | 0.77 | 0.68 | 0.72 | 0.82 |

## Key Business & Technical Takeaways
1. **Title Extraction:** Standardizing passenger titles provided a stronger predictive signal than raw passenger demographics alone.
2. **Best Classifier:** Gradient Boosting yielded the highest overall ROC-AUC (0.88) and accuracy (82.68%), outperforming baseline models.
