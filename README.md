
<img width="1200" height="635" alt="data-science2" src="https://github.com/user-attachments/assets/a0de091f-5942-4a02-a92f-c6ed20f6a601" />

# Prediction of Product Sales 
## 📋 Overview

This project focuses on predicting product sales using machine learning techniques. The goal is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales, optimize inventory, and improve decision-making based on data-driven insights.

  - From the product side, factors such as fat content, item type, visibilit, and product weight are analyzed to understand their influence on sales.
  - From the outlet side, attributes like outlet size, location, and type are considered to capture differences in consumer behavior across different store settings.
By combining these two dimensions, the project provides insights into what drives higher sales and offers a tool to forecast sales more accurately

## 🎯 Objectives

- Analyze sales data to identify trends and key factors influencing sales.

- Build and evaluate predictive models to forecast future product sales.

- Provide actionable insights through visualizations and performance metrics.

---
## 🧰 Tech Stack

Languages: Python

Libraries: pandas, NumPy, scikit-learn, matplotlib, seaborn.

Modeling Techniques: Linear Regression, Random Forest.

Tools:  Google Colab, GitHub.

---

## 📊 Data Information
- Data Source: [Download Dataset](https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view) )
- Dataset has  8523 records and 12 features , 6 relted to the item features and 5 related to the outlet features 
- Data Dictionary
<img width="710" height="620" alt="data dictionery" src="https://github.com/user-attachments/assets/81a1ed5a-42cb-4252-bc4c-4b1b80aa921e" />

## 🔍 Key Features

- Data cleaning and preprocessing pipeline

- Exploratory Data Analysis (EDA) with visual insights

- Feature engineering for improved model accuracy

- Model training, tuning, and evaluation

## 📈 Results

**Model Results**

Regression Metrics: Test Data
------------------------------------------------------------
- MAE = 765.671
- MSE = 1,213,934.180
- RMSE = 1,101.787
- R^2 = 0.560
RandomForest model
------------------------------------------------------------
- MAE = 734.606
- MSE = 1,118,768.607
- RMSE = 1,057.719
- R^2 = 0.594

- Hyperparameter tuning reduced overfitting and improved generalization performance.
  
**Identified key predictors of product sales** 
- The OutletType is the most significant factor influencing sales performance
- Item Type Fruits and Vegetables gerates the highest Sales

## 🖼️ Visuals






## 📈 Feature Importance & Coefficients Visualization

To understand which variables most influence product sales, feature importance and coefficients were visualized from the models.
<img width="643" height="470" alt="LR" src="https://github.com/user-attachments/assets/dc631fd5-4cc1-4680-8673-21c45b4e4cce" />

The plot above displays the top coefficients from the **Linear Regression** model.  
These coefficients represent how much each feature affects the predicted sales —  
positive values **increase** the prediction, while negative ones **decrease** it.


<img width="896" height="547" alt="importance" src="https://github.com/user-attachments/assets/42db8321-87fc-450d-a373-ac27b961fb86" />

The chart above highlights the most influential features identified by the **Random Forest Regressor**.  
Feature importance measures how much each variable contributed to reducing prediction error during training.

















Generated interpretable insights for business decision-making
## To prepare this data, the data was cleaned, and the following processes were performed:

### Exploratory Data Analysis
    - During the exploratory data analysis, a boxplot and histogram was visualized for each numeric datatype column. 
    - Also, a countplot was visualized for each categorical column. 
    - This gave a good baseline for all of the numeric and categorical columns for univariate EDA.
    
   ![hist item weight](https://github.com/user-attachments/assets/489c2548-4500-46a1-b57e-a6d48b3ea12e)


    for example the item wight 12.5 is the most frequent weight for the items
---

# Model

## linear regression model
Regression Metrics: Test Data
------------------------------------------------------------
- MAE = 765.671
- MSE = 1,213,934.180
- RMSE = 1,101.787
- R^2 = 0.560
## RandomForest model
Regression Metrics: Test Data
------------------------------------------------------------
- MAE = 734.606
- MSE = 1,118,768.607
- RMSE = 1,057.719
- R^2 = 0.594

# Recommendations:



# Limitations & Next Steps

# For further information
For any additional questions, please contact farah.saleem1991@outlook.com
