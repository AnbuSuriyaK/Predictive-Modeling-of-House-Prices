# 🏠 Predictive Modeling of House Prices - Ames, Iowa

This project focuses on predicting house prices in Ames, Iowa using machine learning techniques. It involves data preprocessing, feature engineering, model building, and performance evaluation to deliver accurate price predictions and valuable insights into real estate trends.

## 📊 Project Overview

Key steps in the pipeline:

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Model Selection & Hyperparameter Tuning  
- Evaluation & Insights

## 📁 Dataset

The dataset includes 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa.

> Dataset Source: [Ames Housing Dataset on Kaggle](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)

## 🔍 EDA Highlights

- Analyzed correlations between price and factors like overall quality, square footage, year built, and location  
- Handled missing values, encoded categorical variables, and transformed skewed features  
- Visualized distributions and relationships using **Matplotlib** and **Seaborn**

## 🧠 Models Used

- **Decision Tree Regressor**  
- **Random Forest Regressor**  
- **Gradient Boosting Regressor**  
- **XGBoost Regressor**

> Best Results:  
> ✅ **Gradient Boosting** achieved **RMSE: 0.11** and **Explained Variance: 0.90**

## 🛠️ Tools & Libraries

- **Python** (Pandas, NumPy, Scikit-learn, XGBoost)  
- **Matplotlib**, **Seaborn** for visualization  
- **Jupyter Notebook**  
- **GridSearchCV** for hyperparameter tuning

## 📈 Key Insights

- Home quality, living area, and neighborhood significantly influence sale prices  
- Proper handling of missing values and feature transformations dramatically improve model accuracy  
- Gradient Boosting outperformed other models in both RMSE and variance explained


