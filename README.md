# Laptop Price Predictor 💻

A supervised machine learning model built with Python to predict real-world laptop retail prices in Indian Rupees (INR) based on physical and hardware specifications.

## 📊 Project Overview
This project utilizes a real-world dataset of over 1,300 laptop configurations. It performs key data preprocessing steps—such as text stripping, type casting, and regex feature extraction—before fitting a Linear Regression model to identify core pricing factors.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-learn (Linear Regression)
* **Development Environment:** Jupyter Notebook (`.ipynb`)

## 📈 Model Insights & Core Metrics
* **Baseline Accuracy (R-squared Score):** 59.46%
* **Mean Absolute Error (MAE):** ~₹28,568.58
* **Key Finding:** CPU clock speed and laptop weight emerged as the highest impacting coefficients influencing overall retail value.
