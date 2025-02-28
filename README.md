Sales and Demand Forecasting System

Project Overview

This project aims to develop a Sales and Demand Forecasting System using machine learning techniques. The model predicts future sales based on historical data, helping businesses optimize inventory management, marketing strategies, and sales planning.

Dataset

Source: Kaggle

Preprocessing:

Handled missing values using KNN Imputer.

Removed duplicates and fixed incorrect labels in the Item_Fat_Content column.

Dropped irrelevant columns to improve model efficiency.

Exploratory Data Analysis (EDA)

Checked outliers and analyzed data distributions.

Applied feature encoding using OneHotEncoder and LabelEncoder with ColumnTransformer.

Performed feature selection using VarianceThreshold to retain the most relevant features.

Model Training & Optimization

Experimented with ensemble models:

Gradient Boosting

XGBoost

Hyperparameter tuning applied on Gradient Boosting to find the best model.

Model Evaluation

Metrics used:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

Final Results:

Training Data

MAE: 752.65

MSE: 1,097,758

R² Score: 0.6288

Test Data

MAE: 758.07

MSE: 1,139,572

R² Score: 0.5931

Technologies Used

Programming Language: Python

Libraries & Tools:

Pandas, NumPy (Data Processing)

Seaborn, Matplotlib (Data Visualization)

Scikit-Learn (Machine Learning)

XGBoost (Feature Selection & Model Training)

Repository

Check out the full project on GitHub: Sales and Demand Forecasting
