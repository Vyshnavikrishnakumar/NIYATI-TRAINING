# Customer Churn Analysis Project

## Overview

This project focuses on **customer churn analysis** for the banking industry, aiming to remove customers who have exited their accounts. The goal is to improve retention rates and develop better customer relationship management strategies.

## Objective
The primary objective is to identify and remove customers who have exited their bank accounts to ensure an up-to-date customer database.

## Business Goals
- **Improve Retention**: Identify customers at risk of churning and implement targeted retention strategies.
- **Reduce Churn**: Lower the churn rate using insights from data analysis.
- **Enhance CRM**: Maintain accurate customer records to personalize and improve customer relationships.

## Key Metrics
- **Number of Active Customers**: Track the number of active versus churned customers.
- **Churn Rate**: Monitor the percentage of customers who exited their accounts.
- **Prediction Accuracy**: Evaluate model accuracy for identifying churned customers.

## Data Cleaning
- Handled missing values using `dropna()`.
- Removed duplicate entries using `drop_duplicates()`.
- Cleaned data was saved to a CSV file for further analysis.

## Data Analysis
- Generated descriptive statistics to understand customer demographics and behavior.
- Visualized the correlation between numeric variables and churn rate using a heatmap.
- Compared the age distribution between churned and active customers using a boxplot.

## Libraries and Tools
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computing.
- **Seaborn**: Statistical data visualization.
- **Matplotlib**: Plotting graphs and charts.
- **Scikit-learn**: Machine learning for predictive modeling.

## Data Visualization
- Heatmap for correlation analysis of customer attributes.
- Boxplot to compare age distribution by churn status.

## Model Development
- A **Logistic Regression** model was built to predict customer churn.
- The dataset was split into training and test sets to evaluate the model’s performance.
- Key evaluation metrics include confusion matrix and classification report.

## How to Run
1. Install the required dependencies:
    ```
    pip install pandas numpy seaborn matplotlib scikit-learn
    ```
2. Run the analysis script using:
    ```python
    python churn_analysis.py
    ```

## Conclusion
This analysis provides insights into customer churn behavior, helping the bank to take proactive measures to retain customers and improve the overall customer relationship experience.

