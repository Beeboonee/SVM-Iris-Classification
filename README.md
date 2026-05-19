# SVM Iris Classification

This project applies Support Vector Machine (SVM) classification on the Iris dataset.

## Project Overview

The goal of this notebook is to classify Iris flower species based on their measurements using a Support Vector Machine model.

## Steps Covered

- Load the Iris dataset
- Explore the data using visualization
- Split the data into training and testing sets
- Train an SVM classifier
- Evaluate the model using confusion matrix and classification report
- Improve the model using GridSearchCV

## Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## Model

The project uses `SVC` from Scikit-learn and applies GridSearchCV to tune the hyperparameters `C`, `gamma`, and `kernel`.

## Result

The SVM model performs well on the Iris dataset, and GridSearchCV helps find the best parameters for better classification accuracy.
