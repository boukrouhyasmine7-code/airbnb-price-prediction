# Airbnb Price Prediction Challenge

This repository contains a machine learning workflow built to predict the nightly prices of Airbnb listings across multiple major US cities. The project tackles data cleaning, complex parsing of text-based structural attributes, target encoding for geographical variance, and tree-based regression modeling.

---

##  Project Overview
* **Objective:** Predict `log_price` (the natural log of an Airbnb listing's nightly price) based on its characteristics.
* **Problem Type:** Supervised Regression
* **Dataset Scope:** ~22k listings across 6 major US cities (New York City, Los Angeles, San Francisco, Washington D.C., Chicago, and Boston).
* **Target Variable:** `log_price` ∈ [2.3, 7.6], with a mean of approximately 4.78 (~$119/night in raw pricing).

---

##  Repository Structure
```text
├── airbnb_train.csv         # Training dataset with target labels
├── airbnb_test.csv          # Testing dataset for predictions
├── airbnb_prediction.ipynb  # Jupyter Notebook containing full EDA and Model Pipeline
└── README.md                # Project documentation
