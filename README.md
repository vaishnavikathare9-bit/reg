# Salary Prediction using Simple Linear Regression

A machine learning project demonstrating end-to-end data processing, model training, evaluation, and visualization for salary prediction based on years of experience using **Simple Linear Regression**.

---

## 📌 Project Overview

This repository contains an end-to-end implementation of a supervised machine learning workflow using Python and `scikit-learn`. The model analyzes the relationship between an employee's years of professional experience and their salary to predict future earnings.

---

## 🛠️ Machine Learning Pipeline

1. **Data Ingestion & Inspection:** Loading raw dataset, inspecting shape and data types.
2. **Data Cleaning & Preprocessing:** Handling duplicate entries, checking for missing values, and removing redundant index columns[cite: 10].
3. **Exploratory Data Analysis (EDA):** Visualizing feature correlations using scatter plots[cite: 10].
4. **Data Splitting:** Splitting data into training (80%) and testing (20%) sets[cite: 10].
5. **Model Building & Training:** Initializing and fitting a `LinearRegression` model from `scikit-learn`[cite: 10].
6. **Evaluation & Visualization:** Assessing performance on unseen test data and plotting the regression fit line[cite: 10].

---

## 📁 Repository Structure

```text
.
├── SML/
│   └── Regression/
│       └── Salary_dataset.csv     # Dataset containing Experience vs Salary
├── notebook.ipynb                 # Jupyter Notebook with full implementation
└── README.md                      # Project documentation
