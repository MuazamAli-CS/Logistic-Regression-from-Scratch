# Logistic Regression from Scratch

## Project Overview

This project implements Logistic Regression from scratch using Python, NumPy, and Pandas without using Scikit-learn.

The model uses the Banknote Authentication dataset to perform binary classification and predict whether a banknote belongs to class 0 or class 1.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Google Colab

## Dataset

The Banknote Authentication dataset contains 1,372 records and four input features:

- Variance
- Skewness
- Curtosis
- Entropy

The target column is `Class`, which contains two classes: 0 and 1.

## Implementation

The model was developed step by step:

1. Data loading and understanding
2. Feature selection
3. Train-test splitting
4. Feature standardization
5. Prediction using the sigmoid function
6. Binary cross-entropy cost function
7. Gradient descent optimization
8. Model training
9. Confusion matrix
10. Model evaluation

## Results

- **Test Accuracy:** 98.55%
- **Precision:** 97.06%
- **Recall:** 100.00%
- **F1-Score:** 98.51%
- **Correct Test Predictions:** 271 out of 275

## Key Learning Outcomes

- Understanding how Logistic Regression works
- Implementing sigmoid-based predictions
- Calculating binary cross-entropy
- Optimizing weights and bias using gradient descent
- Evaluating a binary classification model

## How to Run

1. Download the `Logistic Regression.ipynb` notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the downloaded notebook.
4. Run the notebook cells from top to bottom.

The notebook loads the dataset and implements the model without Scikit-learn.

## Project Purpose

This project was completed as a machine learning assignment to understand the mathematical and programming foundations of Logistic Regression.
