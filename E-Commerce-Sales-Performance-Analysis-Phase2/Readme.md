# E-Commerce Order Delay Prediction & Analysis

## 📌 Project Overview

This project focuses on analyzing e-commerce order delivery performance and building machine learning models to predict whether an order will be delayed.

The project combines Data Analytics, SQL, Machine Learning, Model Evaluation, Hyperparameter Tuning, and Explainable AI (SHAP) to generate business insights and improve delivery operations.

---

## 🎯 Business Problem

Late deliveries negatively impact customer satisfaction, increase support costs, and reduce customer trust.

The objective of this project is to:

* Analyze order delivery patterns
* Identify factors affecting delivery delays
* Predict delayed orders before delivery
* Explain model predictions using SHAP
* Provide actionable business recommendations

---

## 📊 Dataset

**Dataset:** Brazilian E-Commerce Public Dataset by Olist

The project uses multiple relational datasets:

* Orders Dataset
* Customers Dataset
* Order Items Dataset
* Products Dataset
* Payments Dataset

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* SHAP
* SQLite3

### Machine Learning Techniques

* Logistic Regression
* XGBoost Classifier
* Cross Validation
* Hyperparameter Tuning (GridSearchCV)

---

# Phase 2 Tasks

## Task 1: Data Audit, Cleaning & EDA

### Activities Performed

* Loaded and inspected datasets
* Checked missing values
* Checked duplicate records
* Converted date columns to datetime format
* Merged multiple datasets
* Created engineered features

### New Features Created

* delivery_time
* delay_days
* is_delayed
* purchase_weekday
* purchase_month

### Visualizations

* Delivery Time Distribution
* Delayed vs On-Time Orders
* Payment Type vs Delay
* State vs Delay
* Monthly Delay Trend
* Delivery Time by Weekday
* Order Value vs Delay

### Key Insights

* Delivery delays vary across states.
* Certain payment methods show higher delays.
* Monthly trends indicate seasonal delivery patterns.
* Most orders are delivered within a predictable time range.

---

## Task 2: SQL Analysis

SQLite was used to perform business analysis on the cleaned dataset.

### SQL Concepts Used

* SELECT
* WHERE
* GROUP BY
* ORDER BY
* Aggregate Functions
* Subqueries

### Business Questions Answered

* Total Orders
* Delayed Orders
* Average Delay
* Orders by Payment Type
* Delay by Payment Type
* Top Delayed States
* Monthly Delay Trends
* Delayed Orders by State
* Highest Order Value
* Orders Above Average Value

---

## Task 3: Logistic Regression Model

A baseline classification model was developed to predict delayed orders.

### Target Variable

* is_delayed

  * 1 = Delayed
  * 0 = On-Time

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

### Key Learning

Recall was identified as the most important metric because failing to detect delayed orders can negatively affect customer satisfaction.

---

## Task 4: XGBoost Pipeline

A machine learning pipeline was created using:

### ColumnTransformer

* StandardScaler for numerical features
* OneHotEncoder for categorical features

### Model

* XGBoost Classifier

### Features Used

#### Numerical Features

* payment_value
* freight_value

#### Categorical Features

* payment_type
* customer_state
* purchase_weekday
* purchase_month

### Benefits

* Automated preprocessing
* Reduced data leakage
* Improved model performance

---

## Task 5: Cross Validation, Hyperparameter Tuning & SHAP

### Cross Validation

Used Stratified K-Fold Cross Validation to evaluate model stability.

### Hyperparameter Tuning

Used GridSearchCV to optimize:

* n_estimators
* max_depth
* learning_rate

### SHAP Explainability

SHAP was used to:

* Identify important features
* Explain model decisions
* Visualize feature impact
* Interpret individual predictions

---

## 📈 Model Evaluation

Models Compared:

1. Logistic Regression
2. XGBoost
3. Tuned XGBoost

Metrics Used:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

---

## 💡 Business Recommendations

* Monitor high-risk orders proactively.
* Improve logistics performance in high-delay regions.
* Optimize delivery processes during peak months.
* Investigate payment methods associated with higher delays.
* Use predictive models to notify customers about potential delays.

---

## 📂 Project Structure

```text
Ecommerce_Order_Delay_Prediction/
│
├── datasets/
│
├── notebooks/
│   └── Phase2_Mini_Project.ipynb
│
├── outputs/
│   ├── charts/
│   ├── reports/
│   └── model_results/
│
├── README.md
├── requirements.txt
└── cleaned_order_delay_dataset.csv
```

---

## 🚀 Future Improvements

* Deploy model using Streamlit
* Create interactive dashboards with Power BI
* Integrate real-time delivery prediction
* Build customer delay alert system

---

## 👨‍💻 Author

**Anuj Rajliwal**

B.Tech (Artificial Intelligence & Data Science)

Aspiring Data Analyst | Machine Learning Enthusiast

GitHub: https://github.com/AnujRajliwal
