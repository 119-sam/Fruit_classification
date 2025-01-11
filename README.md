# Fruit Classification: Apple vs Orange

This project focuses on classifying fruits (apples and oranges) using the **K-Nearest Neighbors (KNN)** algorithm. We create a synthetic dataset, apply KNN with multiple values of \(K\), predict new data points, and analyze the performance using a **confusion matrix**.

---

## Project Overview

### Problem Statement
The goal is to classify fruits (apple or orange) based on their features (e.g., weight and size). The dataset is initially small, but we augment it by creating new data points from existing ones. We then:
1. Split the dataset into training and testing sets.
2. Apply the KNN algorithm with \(K=3\), \(K=5\), and \(K=7\).
3. Predict new data points.
4. Visualize the results using confusion matrices.

---

## Features Used
Each fruit is represented by the following features:
- **Weight (g)**: Numeric values for fruit weight.
- **Size**: A scale representing the size of the fruit's.

The target variable is the **fruit type**, which is either:
- `Apple`
- `Orange`

---

## Steps in the Project

### 1. **Dataset Creation**
- A synthetic dataset is generated with 50 samples where we already had 40 samles, including features (weight and color intensity) and labels (apple or orange).
- The dataset is augmented by creating new data points based on slight variations of existing ones.

### 2. **Data Splitting**
The dataset is split into two parts:
- **Training Set** (70%): Used to train the KNN model.
- **Testing Set** (30%): Used for final evaluation.

### 3. **KNN Algorithm**
- The KNN algorithm is applied with \(K=3\), \(K=5\), and \(K=7\).
- Predictions are made for the validation and testing sets.

### 4. **New Data Point Prediction**
- The trained KNN model predicts the class of a new, unseen data point.

### 5. **Confusion Matrix**
- Confusion matrices are generated for each value of \(K\) to evaluate model performance.
- Accuracy, precision, recall, and F1-score are derived from the confusion matrices.

---

## Requirements

The following Python libraries are required:
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`

Install them using:
```bash
pip install numpy pandas scikit-learn matplotlib

