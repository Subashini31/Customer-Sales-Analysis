# Customer-Sales-Analysis
End-to-end analysis of customer sales data including EDA, time-series trends, feature engineering, and high-value customer prediction.
# 📊 Customer Sales Analysis & High-Value Prediction

## 📌 Project Overview

This project focuses on analyzing customer purchase behavior using Pandas and building a basic machine learning pipeline to identify high-value customers.

The workflow includes data cleaning, feature engineering, exploratory data analysis (EDA), visualization, and preprocessing for machine learning.

---

## 🎯 Objectives

* Understand customer purchasing patterns
* Identify top-performing cities and products
* Analyze sales trends over time
* Detect high-value customers
* Prepare data for machine learning

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Dataset Features

* Customer_ID
* Gender
* Age
* City
* Product
* Price
* Quantity
* Purchase_Date
* Total (engineered)
* Age_Group (engineered)
* Month (engineered)
* High_Value (target variable)

---

## 🧹 Data Cleaning

* Handled missing values using median (Age) and mean (Price)
* Detected outliers using IQR method
* Replaced extreme values with median
* Converted date column to datetime format

---

## ⚙️ Feature Engineering

* Created **Total = Price × Quantity**
* Created **Age Groups** using binning
* Extracted **Month** from purchase date
* Created **High_Value flag** based on spending threshold

---

## 📊 Exploratory Data Analysis

### ✔️ Analysis Performed

* Gender-wise average spending
* City-wise revenue analysis
* Product performance (sales & quantity)
* Top customers by spending
* Most popular product
* Customer segmentation (Age > 30)

---

## 📈 Time Series Analysis

* Daily sales trend
* Monthly spending trends
* Cumulative revenue growth
* Peak sales day identification

---

## 🔄 Advanced Analysis

* Pivot Table (City vs Product revenue)
* Heatmap visualization for comparison
* Revenue distribution insights

---

## 🤖 Machine Learning Preprocessing

### ✔️ Steps Performed

* Removed irrelevant columns (Customer_ID, Purchase_Date)
* Applied One-Hot Encoding to categorical variables
* Normalized numerical features (Price, Total)
* Split dataset into features (X) and target (y)

---

## 🔍 Feature Importance

* Total spending is a key indicator of high-value customers
* Product and pricing also influence customer behavior

---

## 📊 Visualizations

* Histogram (Age distribution)
* Line plot (daily/monthly trends)
* Cumulative revenue graph
* Heatmap (City vs Product)

---

## 💡 Key Insights

* Chennai generates higher revenue due to more transactions
* Bangalore shows higher average spending (premium customers)
* Sales trends show peaks and fluctuations over time
* Certain products dominate in specific cities

---

## ⚠️ Important Consideration

* Potential data leakage identified when using Total to predict High_Value
* Alternative approach suggested by excluding derived features

---

## 🚀 Conclusion

This project demonstrates end-to-end data analysis and preprocessing skills, including data cleaning, visualization, feature engineering, and preparation for machine learning.

---

## 📎 Future Improvements

* Apply advanced ML models (XGBoost, LightGBM)
* Perform feature selection and tuning
* Deploy model using Streamlit
* Build interactive dashboard

---
