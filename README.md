Naive Bayes Classifier on Iris Dataset
Overview

This project implements the Naive Bayes Classifier using the Iris dataset from Scikit-learn.
Naive Bayes is a probabilistic classification algorithm based on Bayes' Theorem, assuming features are independent.
It is simple, fast, and works well on both small datasets and text classification tasks.

📂 Dataset

Source: Iris dataset (built into Scikit-learn)

Classes:

Setosa (0)

Versicolor (1)

Virginica (2)

Features:

Sepal Length

Sepal Width

Petal Length

Petal Width

🛠️ Implementation Steps

Import dataset from sklearn.datasets

Create DataFrame using pandas

Split dataset into train (80%) and test (20%) sets

Train a Gaussian Naive Bayes (GaussianNB) model

Predict flower class on test data

Evaluate with Accuracy, Confusion Matrix, and Classification Report

📊 Results

Accuracy: ~96%

Confusion Matrix:
Most flowers were correctly classified, with very few misclassifications.

Example Output:

Accuracy: 0.9666
Confusion Matrix:
[[10  0  0]
 [ 0 10  1]
 [ 0  0  9]]

📌 Why Naive Bayes?

Simple & computationally efficient

Works well when features are conditionally independent

Performs strongly even with small datasets like Iris
