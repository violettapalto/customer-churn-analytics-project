# Customer Churn Analysis and Prediction

## Project Overview
This project analyzes customer churn for a telecommunications service provider. The goal is to understand the factors that lead customers to cancel their service and build a machine learning model capable of predicting churn.

The analysis follows a complete data science workflow including data cleaning, exploratory analysis, feature engineering, and predictive modeling.

## Dataset
The project uses the **Telco Customer Churn dataset**, a public dataset originally released by IBM and commonly used for churn prediction and customer analytics projects.

The dataset contains customer demographic information, subscription services, billing data, and churn labels.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

### 1. Data Cleaning
- Loaded the raw dataset
- Handled data type inconsistencies
- Checked for missing values and duplicates
- Exported a cleaned dataset for further analysis

### 2. Exploratory Data Analysis
Explored relationships between customer characteristics and churn.

Key visualizations included:
- Churn distribution
- Tenure vs churn
- Contract type vs churn
- Monthly charges vs churn
- Correlation analysis

### 3. Feature Engineering
- Encoded categorical variables
- Converted binary variables into numerical form
- Prepared the dataset for machine learning models

### 4. Predictive Modeling
Built machine learning models to predict customer churn.

Models implemented:
- Logistic Regression
- Random Forest

Evaluation metrics included:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Key Insights
Several important factors influence churn behavior:

- Customers with **month-to-month contracts churn significantly more often**
- **Shorter tenure customers are more likely to leave**
- **Higher monthly charges increase churn probability**
- Customers without additional services such as **tech support or security services churn more frequently**

## Project Structure
data/
raw/
processed/

notebooks/
01_data_cleaning.ipynb
02_exploratory_analysis.ipynb
03_feature_engineering.ipynb
04_modeling.ipynb

sql/
exploratory_queries.sql

## Conclusion
This project demonstrates how data analysis and machine learning can be used to identify patterns in customer churn and help businesses proactively identify customers at risk of leaving.