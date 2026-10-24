# Logistic Regression – Module 3

## 📌 Overview

This project implements Logistic Regression using Python and Scikit-learn.

The task focuses on understanding the sigmoid function, logistic regression, model training, prediction, and model evaluation.

This project was completed as part of internship training.

---

## 🎯 Objectives

- Understand the concept of Logistic Regression
- Implement the Sigmoid Function
- Visualize the Sigmoid Function
- Train a Logistic Regression model
- Generate predictions
- Evaluate model performance
- Understand model coefficients and intercept

---

## 🛠️ Technologies Used

- Python
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📚 Concepts Covered

### 1. Sigmoid Function

The sigmoid function is used in Logistic Regression to convert values into probabilities between 0 and 1.

The function used in this project is:

```python
def sigmoid(z):
    g = 1 / (1 + np.exp(-z))
    return g
