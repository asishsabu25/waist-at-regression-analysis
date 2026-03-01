# 📊 Adipose Tissue Prediction using Regression Analysis

📌 Project Overview
This project analyses the relationship between **Waist Circumference** and **Adipose Tissue (AT)** using statistical and machine learning regression techniques.  

The objective is to build predictive models to estimate adipose tissue levels based on waist measurements and compare multiple regression approaches to identify the best-performing model.

🎯 Objectives
- Perform Exploratory Data Analysis (EDA)
- Evaluate the correlation between Waist and AT
- Build multiple regression models
- Apply transformation techniques to improve accuracy
- Validate regression assumptions using residual diagnostics
- Select the best model based on performance metrics

- 📂 Dataset
| Variable | Description |
|----------|-------------|
| Waist    | Waist Circumference (Independent Variable) |
| AT       | Adipose Tissue (Dependent Variable) |

🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Scikit-learn
- Scipy

- 🔎 Exploratory Data Analysis (EDA)
- Histogram and Boxplot for distribution analysis
- Scatter plot to visualize Waist vs AT relationship
- Correlation analysis
- Outlier detection

Models Implemented

 1️⃣ Simple Linear Regression
AT = β₀ + β₁(Waist)

 2️⃣ Log Transformation Model
AT = β₀ + β₁ log(Waist)

 3️⃣ Exponential Model
log(AT) = β₀ + β₁(Waist)

 4️⃣ Quadratic Regression
AT = β₀ + β₁(Waist) + β₂(Waist²)

 5️⃣ Scikit-learn Linear Regression

 
Model Evaluation Metrics
- R² Score
- Adjusted R²
- RMSE (Root Mean Square Error)


- Residual Analysis
- Q-Q Plot
 Residual Diagnostics
- Residual vs Fitted Plot
- Histogram of Residuals
- Normal Q-Q Plot
- Homoscedasticity validation

- Final Model Selection Criteria
- Highest R²
- Lowest RMSE
- Statistically significant coefficients (p < 0.05)
- Random residual distribution


waist-at-regression-analysis/
│
├── data/
│ └── wc-at.csv
│
├── src/
│ └── regression_analysis.py
│
├── visuals/
│ ├── scatter_plot.png
│ ├── residual_plot.png
│ └── qq_plot.png
│
└── README.md

Key Learnings

Data visualisation improves understanding before modelling

Transformations enhance regression performance

Residual diagnostics validate model assumptions

Polynomial regression captures non-linear relationships

Author

Asish Sabu
Data Analyst | Regression Modelling | Statistical Analysis

