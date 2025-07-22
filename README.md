# Heart Disease ML Pipeline

This project presents a full machine learning pipeline for both **classification** and **regression** tasks using the **Heart Disease dataset**.

## Objectives
- Predict **Heart Disease (Classification)**
- Estimate **Cholesterol levels (Regression)**

## ML Tasks Covered

- Data Cleaning & Preprocessing
- Feature Engineering (scaling, encoding)
-  Model Training:
  - Linear Regression
  - Ridge & Lasso Regression
  - SGD Regressor / Classifier
  - Logistic Regression
- Learning Curve Visualization
- Hyperparameter Tuning
- Model Evaluation
- Feature Importance

## Algorithms & Tools

| Task           | Algorithms                              |
|----------------|------------------------------------------|
| Regression     | Linear, Ridge, Lasso, SGDRegressor       |
| Classification | Logistic Regression, SGDClassifier       |

## Metrics

- **Regression**: RMSE, R²
- **Classification**: Accuracy, F1 Score
- **Training Time**
- **Feature Importance**: via coefficients

## Results Summary

### Regression
- Ridge, SGD, and Linear Regression showed similar RMSE due to limited features.

### Classification
- Logistic Regression outperformed SGD on accuracy & stability.

## Libraries Used
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
