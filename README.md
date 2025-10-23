
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
- Dataset has  8523 records and 12 features , 6 related to the item features and 5 related to the outlet features 
- Data Dictionary
<img width="710" height="620" alt="data dictionery" src="https://github.com/user-attachments/assets/81a1ed5a-42cb-4252-bc4c-4b1b80aa921e" />

## 🔍 Key Features

- Data cleaning and preprocessing pipeline

- Exploratory Data Analysis (EDA) with visual insights

- Feature engineering for improved model accuracy

- Model training, tuning, and evaluation

## 📈 Model Results

Regression Metrics

------------------------------------------------------------
- MAE = 765.671
- MSE = 1,213,934.180
- RMSE = 1,101.787
- R^2 = 0.560
  -
RandomForest model
------------------------------------------------------------
- MAE = 734.606
- MSE = 1,118,768.607
- RMSE = 1,057.719
- R^2 = 0.594

- Hyperparameter tuning reduced overfitting and improved generalization performance.
 

## 🖼️ Visuals
Generated interpretable insights for business decision-making
---
### Count plot for Item Type
-fruits and vegetables generate the highest sales 2.82 millions (%15.2) followed by 'snack foods' 2.7 millions(%14.7)
-High sales indicate high demand


<img width="616" height="556" alt="ff'" src="https://github.com/user-attachments/assets/75fc5cb4-df97-49a5-ba80-da2762fb2d80" />

### Scatter Plot for Price VS Sales

Moderate Positive Correlation (r = 0.57):

There is a moderate positive relationship between item price and total sales.

This means higher-priced items tend to have higher sales, but it’s not a perfect trend as other factors also influence sales.

Some high-priced items achieve very high sales, showing strong market demand for premium products in some categories.

<img width="558" height="393" alt="item mrp" src="https://github.com/user-attachments/assets/c93fad37-c2da-4997-a701-b0f716c35aa3" />

### Pie Chart For Outlet Size
This pie chart shows the proportion of total sales coming from outlets of different sizes: Small, Medium, and High.

Medium-sized outlets contribute the largest share of sales, making up 52.7% of the total.

Small outlets account for about 32.2% of sales.

High-sized outlets contribute the smallest portion, with only 15.1% of the total sales.

<img width="409" height="411" alt="outlet size" src="https://github.com/user-attachments/assets/01bffbbf-1d46-4859-a056-2a27c0596327" />


## 📈 Feature Importance & Coefficients Visualization

To understand which variables most influence product sales, feature importance and coefficients were visualized from the models.
<img width="643" height="470" alt="LR" src="https://github.com/user-attachments/assets/dc631fd5-4cc1-4680-8673-21c45b4e4cce" />

The plot above displays the top coefficients from the **Linear Regression** model.  
These coefficients represent how much each feature affects the predicted sales —  
positive values **increase** the prediction, while negative ones **decrease** it.


<img width="896" height="547" alt="importance" src="https://github.com/user-attachments/assets/42db8321-87fc-450d-a373-ac27b961fb86" />

The chart above highlights the most influential features identified by the **Random Forest Regressor**.  
Feature importance measures how much each variable contributed to reducing prediction error during training.


# 📌 Recommendations:
- Optimize Pricing Strategy by Analyze price sensitivity of different types. we might find some products can bear higher prices without reducing demand. i believe this will lead to obvious increase in Sales
- Don't assume cheap means better-selling — some higher-priced items perform very well.

-Explore what drives sales in the higher price bands: branding, packaging, outlet location, promotions?

-Use this insight to optimize pricing strategy — you may be able to increase prices without hurting sales, depending on the product type.
-Consider strategies like improving inventory, marketing, and customer experience tailored to medium outlets.this will lead to huge increase in Sales

# For further information
For any additional questions, please contact farah.saleem1991@outlook.com
