# House Price Prediction using Regression Algorithms

## Overview

This project focuses on predicting house prices using multiple regression algorithms. The objective is to analyze housing data, perform preprocessing, explore relationships among variables, and compare the performance of different machine learning models for continuous value prediction.

The study utilizes the King County House Price dataset and evaluates model performance using standard regression metrics.

---

## Dataset

**Dataset:** KC House Data

The dataset contains various housing attributes, including:

* Bedrooms
* Bathrooms
* Living Area
* Floors
* Waterfront
* View
* Condition
* Grade
* Year Built
* Year Renovated
* Lot Area
* House Price

---

## Project Objectives

* Load and understand the dataset
* Identify missing values
* Perform data preprocessing
* Handle outliers
* Scale numerical features
* Conduct Exploratory Data Analysis (EDA)
* Implement regression algorithms
* Evaluate model performance
* Compare models and identify the best-performing approach

---

## Data Preprocessing

The following preprocessing techniques were applied:

* Missing value inspection
* Duplicate removal
* Outlier detection using the IQR method
* Feature scaling using StandardScaler
* Train-test splitting

---

## Exploratory Data Analysis

EDA techniques used in this project include:

### Histogram

Used to understand feature distributions.

### Scatter Plot

Used to analyze relationships between independent variables and house prices.

### Boxplot

Used to detect outliers and observe data spread.

### Correlation Analysis

Used to identify strong positive and negative relationships among features.

---

## Regression Models

### Linear Regression

Linear Regression models the relationship between independent variables and the target variable through a linear equation.

It serves as a baseline regression model and performs well when relationships are approximately linear.

### Decision Tree Regressor

Decision Tree Regressor splits data into multiple decision nodes and predicts values based on learned patterns.

It captures non-linear relationships and complex interactions between variables.

### Random Forest Regressor

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

It generally performs better for housing datasets due to its ability to learn complex patterns.

---

## Evaluation Metrics

Model performance was assessed using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

Higher R² values indicate better predictive capability, while lower MAE and MSE values indicate smaller prediction errors.

---

## Key Insights

* Living area exhibits a strong positive relationship with house price.
* Houses with higher grades tend to have significantly greater market values.
* Random Forest Regressor achieved the highest predictive performance among the evaluated models.
* Linear Regression provides a useful baseline but may not capture complex relationships effectively.
* Ensemble methods improve generalization and prediction accuracy.

---

## Results

The regression models were compared based on MAE, MSE, and R² Score.

The model with the highest R² Score and lowest error values was selected as the best-performing model.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Repository Structure

```text
House-Price-Prediction/
│
├── kc_house_data.csv
├── House_Price_Regression_Assignment.ipynb
├── README.md
└── requirements.txt
```

---

## Conclusion

This project demonstrates the application of regression algorithms for house price prediction. Through preprocessing, exploratory analysis, and model comparison, Random Forest Regressor emerged as the most effective model for predicting housing prices in the dataset.

---

## Author

Mohamed Shihad
