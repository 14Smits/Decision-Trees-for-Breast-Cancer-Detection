# Breast Cancer Prediction using Machine Learning

This repository contains Python code for predicting breast cancer using machine learning models. We explore the use of Decision Trees, Random Forests, and XGBoost classifiers to predict whether a tumor is benign (non-cancerous) or malignant (cancerous) based on various features.

## Dataset

The dataset used in this project is sourced from the Wisconsin Breast Cancer Diagnostic dataset, available through the UCI Machine Learning Repository. It includes features extracted from digitized images of breast mass and target labels indicating the diagnosis.

### Features

The features include measurements such as radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension across three different categories of breast cells.

## Models Implemented

### 1. Decision Tree Classifier

- Optimized parameters (`min_samples_split` and `max_depth`) to balance model complexity and accuracy.
- Achieved an accuracy of approximately 94.74% on the validation set.

### 2. Random Forest Classifier

- Implemented ensemble learning using a Random Forest to improve generalization performance.
- Tuned parameters (`min_samples_split`, `max_depth`, `n_estimators`) to achieve an accuracy of approximately 95.61% on the validation set.

### 3. XGBoost Classifier

- Utilized XGBoost, a powerful gradient boosting technique, to further enhance predictive accuracy.
- Employed early stopping to prevent overfitting and achieved an accuracy of approximately 96.49% on the validation set.

## Visualization

- Visualized decision trees to interpret their splits and decision-making criteria.
- Plotted the structure of the XGBoost model to understand its hierarchical composition.

## Conclusion

This project demonstrates the application of machine learning techniques for breast cancer prediction, highlighting the strengths and weaknesses of different models. The results showcase the potential of machine learning in medical diagnostics, particularly in identifying patterns from complex datasets.

### How to Use

- Clone the repository and install the necessary libraries (`pandas`, `scikit-learn`, `xgboost`, `matplotlib`).
- Run the Jupyter notebook or Python scripts to train and evaluate the models.
- Explore different parameters and model configurations to further optimize performance.
