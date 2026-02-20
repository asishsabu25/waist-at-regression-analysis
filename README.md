# waist-at-regression-analysis

Regression analysis project predicting Adipose Tissue using Waist measurements.Adipose Tissue Prediction using Regression Analysis

📌 Project Overview

This project analyzes the relationship between Waist Circumference and Adipose Tissue (AT) using statistical and machine learning regression techniques.

The objective is to develop predictive models capable of estimating adipose tissue levels based on waist measurements and compare multiple regression approaches to identify the best-performing model.

🎯 Business / Analytical Objective
Analyze correlation between Waist and AT
Build regression models to predict AT
Apply transformations to improve model accuracy
Validate model assumptions using residual diagnostics
Select the best model based on statistical performance

📂 Dataset Information
Variable
Description
Waist
Waist Circumference (Independent Variable)
AT
Adipose Tissue Measurement (Dependent Variable)
🛠️ Tools & Technologies Used
Python
Pandas
NumPy
Matplotlib
Statsmodels
Scikit-learn
Scipy
🔎 Exploratory Data Analysis (EDA)
Distribution analysis using histograms
Outlier detection using boxplots
Scatter plot visualization for relationship assessment
Correlation analysis
📈 Models Implemented
Simple Linear Regression
AT = β₀ + β₁(Waist)
Log Transformation Model
AT = β₀ + β₁ log(Waist)
Exponential Model
log(AT) = β₀ + β₁(Waist)
Quadratic (Polynomial) Regression
AT = β₀ + β₁(Waist) + β₂(Waist²)
Scikit-learn Linear Regression
📊 Model Evaluation Metrics
R² Score
Adjusted R²
Root Mean Square Error (RMSE)
Residual Analysis
Q-Q Plot (Normality Check)
🧪 Residual Diagnostics
Residual vs Fitted Plot
Histogram of Residuals
Q-Q Plot for Normal Distribution
Homoscedasticity validation
🏆 Final Model Selection
The best model was selected based on:
Highest R² value
Lowest RMSE
Statistical significance (p-value < 0.05)
Random residual distribution
