# Random Forest Classifier Implementation

This repository contains an implementation of a Random Forest classifier both using built-in functions from scikit-learn and from scratch in Python.

## Dataset

The code uses the "full_data.csv" dataset located in the "/kaggle/input/full-filled-brain-stroke-dataset/" directory. This dataset contains information about patients, including their gender, age, hypertension status, heart disease status, marital status, work type, residence type, average glucose level, BMI, smoking status, and stroke occurrence.

## Implementation

### Using Built-in Functions
- The built-in implementation uses the RandomForestClassifier class from scikit-learn to train a Random Forest model.
- It splits the dataset into training and testing sets, fits the model on the training data, and evaluates its performance using accuracy score.

### From Scratch
- The custom implementation includes classes for Random Forest classifier and Decision Tree classifier.
- The Randomforestclassifier class contains methods for fitting the model, making predictions, and calculating feature importances.
- The DecisionTreeClassifier class is used to build decision trees and calculate feature importances.
- The code follows a similar workflow to the built-in implementation but implements the algorithms from scratch.
