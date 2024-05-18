# Machine Learning Number Classification

This repository contains the final project for ECE 5450: Machine Learning, focusing on the classification of handwritten digits using the MNIST dataset. The project involves implementing various machine learning classifiers and comparing their performances.

## Project Overview

The primary goal of this project is to develop and compare Gaussian and Logistic Regression classifiers for both binary and multiclass classification problems using the MNIST dataset.

### Components

The project is divided into two main components:

1. **Binary Classification**:
    - Develop Gaussian and Logistic Regression classifiers to classify digit 0 from digit 1.
    - Implement both classifiers with identity covariance and common covariance.
    - Extend Logistic Regression with regularization and hyperparameter optimization.

2. **Multiclass Classification**:
    - Develop Gaussian and Logistic Regression classifiers for all digits (0-9).
    - Implement regularized versions and optimize hyperparameters for Logistic Regression.

## Files

### Jupyter Notebooks
- `Part1.ipynb`: Contains the implementation of the binary classification component.
- `Part2.ipynb`: Contains the implementation of the multiclass classification component.

### PDF Documentation
- `ML Final Project.pdf`: Detailed project instructions and requirements.

## Instructions

### Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/SamNicklez/machine-learning-number-classification.git
    cd machine-learning-number-classification
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Notebooks

1. **Binary Classification**:
    - Open `Part1.ipynb` in Jupyter Notebook or Jupyter Lab.
    - Run the notebook cells to load the MNIST dataset, implement the classifiers, and evaluate their performances.

2. **Multiclass Classification**:
    - Open `Part2.ipynb` in Jupyter Notebook or Jupyter Lab.
    - Run the notebook cells to load the MNIST dataset, implement the classifiers, and evaluate their performances.

### Project Structure

- **Data Loading**: Load and preprocess the MNIST dataset.
- **Binary Classification**:
    - `testLinearClassifier`: Function to test classifier performance.
    - `gaussianClassifierWithIdentityCovariance`: Gaussian classifier with identity covariance.
    - `gaussianClassifierWithCommonCovariance`: Gaussian classifier with common covariance.
    - `logisticRegression`: Logistic regression classifier.
    - `logisticRegressionWithRegularization`: Regularized logistic regression classifier.
    - `optimizeHyperparameters`: Function to optimize regularization parameter.
    - Comparison script to evaluate all classifiers.
- **Multiclass Classification**:
    - `gaussianMultiChannelClassifier`: Multiclass Gaussian classifier.
    - `logisticRegressionMultiClassClassifier`: Multiclass logistic regression classifier.
    - `logisticRegressionMultiClassClassifierWithRegularization`: Regularized multiclass logistic regression classifier.
    - `Optimize_MC_Hyperparameters`: Function to optimize regularization parameter for multiclass.
    - `testLinearMCClassifier`: Function to test multiclass classifier performance.
    - Comparison script to evaluate all multiclass classifiers.
