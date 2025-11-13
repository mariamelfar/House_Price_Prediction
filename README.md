# House Price Prediction 🏠

Predicting house prices based on demographic, geographic, and housing features using cleaned and processed data.

---

## 📊 Project Overview

This project focuses on exploring, cleaning, and modeling a housing dataset to predict prices. From raw data preprocessing to feature engineering and model evaluation, the goal was to create a robust predictive pipeline.

**Key questions explored:**

* Which features most influence house prices?
* How can raw housing data be cleaned and transformed for modeling?
* How accurate is the model in predicting real-world prices?

---

## 🧠 Key Steps

### **Data Cleaning & Preparation**

* Removed duplicates and handled missing values (e.g., `total_bedrooms`).
* Standardized column formats and data types.
* Scaled numerical features using **StandardScaler**.
* Split data into **train (80%)** and **test (20%)** sets.

### **Feature Engineering**

Created new features to improve predictive performance:

* **total_rooms_per_household** — ratio of rooms per household.
* **population_per_household** — household population density.

### **Modeling & Evaluation**

* **Algorithm:** Linear Regression
* **Metrics:**

  * MSE (Mean Squared Error)
  * RMSE (Root Mean Squared Error)
  * R² Score
* Visualized **Actual vs Predicted Prices** for performance insight.

---

## 🧩 Tools & Libraries

* **Python 3.x**
* **Pandas**
* **NumPy**
* **Matplotlib & Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**

---

## 📁 Files

* **House_Price_Prediction_Mariam.ipynb** — Jupyter Notebook containing full data cleaning, preprocessing, and modeling pipeline.
* **housing.csv** — Original California Housing dataset (uploaded in Colab or local environment).

---

## 🚀 Results Summary

* **Original dataset:** California Housing Prices CSV
* **After preprocessing:**

  * Train: `(X_train, y_train)`
  * Test: `(X_test, y_test)`

**Outcome:** A cleaned and feature-engineered dataset ready for EDA, trend visualization, and predictive modeling of house prices.

---

## 👩‍💻 Author

**Mariam Elfar**
*Mechatronics Engineering Student | Data Enthusiast | Researcher*
Focused on transforming raw housing data into meaningful insights and predictive models.
