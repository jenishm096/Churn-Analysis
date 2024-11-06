# **Churn Analysis with Telco Data**

## **Project Overview**
This project aims to predict customer churn for a telecommunications company using historical customer data. The goal is to identify the factors contributing to churn and develop a logistic regression model to predict the likelihood of a customer leaving. The analysis is complemented by an interactive Power BI dashboard for data visualization and actionable insights.

## **Tools and Technologies**
- **Python** (for data cleaning, exploratory data analysis, and model development)
  - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`
- **Power BI** (for building an interactive dashboard)
- **Scikit-learn** (for machine learning model development)

## **Steps and Methodology**

### **1. Data Cleaning and Preprocessing**
- Loaded raw telco data into a Pandas DataFrame.
- Handled missing values, outliers, and data inconsistencies.
- Transformed categorical variables into numerical representations using techniques such as label encoding and one-hot encoding.

### **2. Exploratory Data Analysis (EDA)**
- Conducted a thorough EDA to uncover insights about customer behavior, including:
  - Distribution of churn across different customer segments (e.g., contract type, payment method).
  - Correlations between features and churn probability.
  - Data visualizations such as histograms, bar plots, and heatmaps to better understand relationships.

### **3. Logistic Regression Model Development**
- Split the data into training and test sets for model validation.
- Trained a logistic regression model using scikit-learn, optimizing performance through cross-validation.
- Applied feature selection techniques to reduce the number of features and improve model interpretability.
- Evaluated the model using performance metrics such as accuracy, precision, recall, and AUC-ROC.

### **4. Power BI Dashboard**
- Developed a Power BI dashboard to visualize churn data, model predictions, and key customer insights.
- Included visualizations to track churn rates, identify at-risk customers, and highlight areas for improvement in customer retention strategies.

## **Installation**

### **Python Dependencies**
To replicate the analysis, clone the repository and install the necessary dependencies:


### **Contribution**
Feel free to fork the repository and contribute to improving the analysis, model, or dashboard. Suggestions for further model improvements and additional features are welcome.
