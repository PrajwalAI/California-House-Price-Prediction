🏡 California House Price Prediction
A regression-based machine learning project that predicts median house prices in California based on features like income, location, and housing characteristics. This project demonstrates end-to-end data analysis, preprocessing, feature engineering, model training, and evaluation.

📊 Dataset
Source: California Housing Dataset

Total Rows: 20,640

Features:

longitude, latitude, housing_median_age, total_rooms, total_bedrooms,

population, households, median_income, ocean_proximity,

median_house_value (target)

🔧 Tools & Libraries
Python

Pandas, NumPy

Seaborn, Matplotlib

Scikit-learn

Statsmodels

🔍 Project Workflow
1. 📌 Exploratory Data Analysis (EDA)
Visualized distributions and relationships using scatter plots, box plots, and heatmaps.

Identified multicollinearity and skewed features.

2. 🧹 Data Preprocessing
Handled missing values and outliers.

Feature transformations (log, polynomial).

Encoded ocean_proximity and scaled numerical features.

3. 🏗️ Feature Engineering
Derived new variables such as:

Bedrooms per household

Rooms per person

Population per household

4. 🤖 Modeling & Evaluation
Trained the following models:

Linear Regression

Ridge Regression

Support Vector Regressor (SVR)

Gradient Boosting Regressor

Stacked Ensemble

Evaluation Metric: Root Mean Squared Error (RMSE)

Used cross-validation to compare performance.

✅ Results

XGBoost	83.310808
Random Forest	80.119297
Support Vector Machines	72.637929
Linear Regression	60.102913

Winner: XGBoost
