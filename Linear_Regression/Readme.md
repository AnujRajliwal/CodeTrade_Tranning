# California Housing Price Prediction using Linear Regression

## Project Overview

This project demonstrates the implementation and evaluation of Linear Regression using the California Housing Dataset. The objective is to predict median house values based on housing-related features and analyze model performance using different evaluation metrics and train-test split configurations.

The project covers the complete machine learning workflow, including data preprocessing, model training, prediction, performance evaluation, feature comparison, train-test split analysis, and metric verification.

---

## Dataset

**Dataset:** California Housing Dataset

The dataset contains information about housing districts in California, including demographic, geographic, and housing-related attributes.

### Target Variable

* `median_house_value`

### Features Used

* longitude
* latitude
* housing_median_age
* total_rooms
* total_bedrooms
* population
* households
* median_income
* ocean_proximity

---

## Project Tasks

### Task 1: Baseline Linear Regression Model

* Loaded and explored the dataset
* Handled missing values
* Split data into training and testing sets
* Trained a Linear Regression model
* Generated predictions
* Evaluated model performance using:

  * MSE
  * RMSE
  * MAE
  * R² Score
* Compared actual and predicted values
* Visualized predictions using a scatter plot

---

### Task 2: One-Feature vs Multi-Feature Comparison

Two Linear Regression models were developed:

#### Model A

Used only:

* median_income

#### Model B

Used:

* median_income
* housing_median_age
* total_rooms

Performance metrics compared:

* MSE
* RMSE
* MAE
* R² Score

The better model was selected using test-set performance.

---

### Task 3: Train-Test Split Analysis

The same Linear Regression model was tested using:

* 80/20 Split
* 70/30 Split
* 60/40 Split

For each split:

* Training MSE, RMSE, MAE, R²
* Testing MSE, RMSE, MAE, R²
* Train-Test Gap Analysis

The most reliable split was selected based on stability and test performance.

---

### Task 4: Metric Verification and Exploration

Model evaluation metrics were manually calculated and compared with sklearn outputs.

Metrics verified:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Error (MAE)
* R² Score

Additional metric:

* Median Absolute Error

An experiment was conducted by introducing artificial prediction errors to observe how evaluation metrics react to outliers and large prediction mistakes.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Evaluation Metrics

### Mean Squared Error (MSE)

Measures average squared prediction error.

### Root Mean Squared Error (RMSE)

Square root of MSE, easier to interpret because it uses the same unit as the target variable.

### Mean Absolute Error (MAE)

Average absolute prediction error.

### R² Score

Measures how well the model explains variation in the target variable.

### Median Absolute Error

A robust metric that is less sensitive to extreme outliers.

---

## Key Learnings

* Building a complete regression pipeline
* Data preprocessing and feature engineering
* Linear Regression implementation
* Model evaluation techniques
* Feature importance through model comparison
* Impact of train-test split selection
* Understanding evaluation metrics
* Sensitivity of metrics to large prediction errors

---

## Project Structure

```text
Linear_Regression_Project/
│
├── Linear_Regression_Project.ipynb
├── housing.csv
├── README.md
└── requirements.txt
```

---

## Installation

Install required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## Run the Project

Open Jupyter Notebook and run:

```bash
jupyter notebook
```

Then open:

```text
Linear_Regression_Project.ipynb
```

and execute all cells sequentially.

---

## Results

The project demonstrates how Linear Regression can be used for house price prediction and how model performance changes with feature selection and train-test split configurations.

The evaluation and metric verification tasks provide a deeper understanding of regression model assessment and error analysis.

---

## Author

**Anuj Rajliwal**

B.Tech (AI & DS) | Aspiring Data Analyst | Machine Learning Enthusiast

GitHub: https://github.com/AnujRajliwal
