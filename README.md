# 📊 Insurance Cost Prediction using Machine Learning

## Overview
This project focuses on predicting individual medical insurance costs based on personal and lifestyle attributes. The goal is to understand the factors affecting medical expenses and build machine learning models to estimate insurance charges.

---

## Problem Statement
Healthcare costs vary significantly depending on individual characteristics such as age, BMI, smoking status, and region.  

The objective of this project is to:
- Analyze the relationship between these variables and medical charges
- Build predictive models to estimate insurance costs
- Identify key factors that drive higher medical expenses

---

## Dataset
- **Source:** Insurance dataset (CSV file)
- **Number of observations:** 1,338 individuals
- **Features include:**
  - Age
  - Sex
  - BMI (Body Mass Index)
  - Number of children
  - Smoker status
  - Region
  - Charges (target variable)

---

## Exploratory Data Analysis (EDA)
- Checked for missing values (none found)
- Visualized relationships between variables (e.g., BMI vs charges)
- Identified outliers using boxplots and IQR method
- Analyzed distribution of key variables

### Example Insights
- Smoking status has a strong impact on insurance charges
- Higher BMI tends to increase medical costs
- Significant variability exists in charges across individuals

---

## Data Preprocessing
- Outlier detection using IQR
- Feature selection
- Data scaling using **StandardScaler**
- Train-test split for model evaluation

---

## Models Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

## Model Evaluation
The models were evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Results
- The model captures the general trend in medical costs
- Smoking status and BMI are among the most influential features
- Outliers have a noticeable impact on predictions

---

## Key Insights
- 🚬 Smokers have significantly higher insurance costs
- ⚖️ BMI is positively correlated with medical expenses
- 📊 Outliers can distort model performance
- 🧠 Proper preprocessing improves model accuracy

---

## Tools & Libraries
- Python
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
