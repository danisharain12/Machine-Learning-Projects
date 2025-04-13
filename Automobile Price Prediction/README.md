# Automobile Price Prediction Using Machine Learning

**This project is part of the Data Science & AI Bootcamp by Atomcamp. The objective was to predict the price of a car based on its technical specifications, design, and other categorical attributes. 
The project includes data cleaning, feature engineering, exploratory data analysis, model building, evaluation, and model comparison.**

## Dataset
- Source: 1985 Ward's Automotive Yearbook
- Records: ~30,000 rows (after cleaning)

## Tools & Libraries
- Python (Pandas, NumPy)
- Seaborn & Matplotlib
- Scikit-learn (Pipelines, Regressors, Metrics)
- Missingno (for missing data visualization)

## Features:
- Specifications (engine size, horsepower, body style, etc.)
- Insurance risk ratings
- Normalized loss data

## Objective
- To build machine learning models that can accurately predict the price of a car based on its features.

## Project Workflow
- Data Cleaning
- Handled anomalies like '?' and replaced with NaN
- Converted data types
- Removed or imputed missing values (MCAR-based handling)
- Handled outliers using IQR-based method

## Exploratory Data Analysis
- Univariate, Bivariate & Multivariate Analysis
- Visualizations using Seaborn & Matplotlib
- Price distributions, most common car makes, and performance engine types

## Feature Selection
- Used correlation analysis to identify highly correlated features
- Removed redundant or low-importance features to improve model performance
- Modeling Built 3 separate regression pipelines with preprocessing:

🔹 Linear Regression

🔸 Decision Tree Regressor

🌟 Random Forest Regressor

## Model Evaluation Metrics used:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- Adjusted R² Score

## Model Performance
- Model	Test R²	Test RMSE	Test MAE
- Linear Regression	0.9154	2292.35	1565.81
- Decision Tree Regressor	0.9714	1332.74	857.26
- Random Forest Regressor	0.9810	1086.50	703.47
`Best Model: Random Forest Regressor — due to its high accuracy and minimal overfitting.`

## Key Insights
- Toyota is the most common make (~24% of data)
- Sedans dominate as the most common body type
- Engine size, horsepower, and curb weight are most strongly correlated with price
- Rear-wheel drive and diesel engines tend to be found in higher-priced cars

## Future Improvements
- Hyperparameter tuning with cross-validation
- Model deployment with Streamlit or Flask
- Integration with real-time vehicle databases

## Contact
Want to collaborate or discuss data projects?
📧 danisharain253@gmail.com

**Author**
- Danish Karim
