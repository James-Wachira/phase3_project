# phase3_project

# SyriaTel Customer Churn Prediction

## Overview
This project uses machine learning to predict customer churn for SyriaTel, a telecommunications company. Churn refers to customers who leave the service, and predicting this allows SyriaTel to intervene and retain customers, reducing lost revenue.

## Business Problem
SyriaTel wants to proactively identify which customers are at risk of churning. Using customer data, this project builds a classification model to predict churn and provides actionable insights to reduce it.

## Objectives
1. Identify key features that predict customer churn.
2. Build and evaluate classification models to predict churn.
3. Provide business recommendations to reduce customer churn.

## Dataset
The dataset contains customer information including service usage patterns, account information, and churn labels.

## Methodology
1. **Data Exploration and Cleaning**
   - Checked for nulls and summarized features
   - Converted categorical variables and dropped irrelevant columns
2. **Univariate, Bivariate, and Multivariate Analysis**
   - Explored churn distribution and relationships between features
3. **Preprocessing**
   - Encoded binary features
   - Scaled numerical data
   - Split dataset into training and testing sets
4. **Modeling**
   - Built a baseline Logistic Regression model
   - Tuned a Decision Tree Classifier with GridSearchCV
5. **Evaluation**
   - Evaluated using accuracy, precision, recall, F1-score
   - Visualized feature importance

## Models
- **Logistic Regression:** Used as a baseline model. Achieved ~80% precision and recall.
- **Decision Tree Classifier (Tuned):** Performed better, especially on recall, identifying more churn cases.

## Key Findings
- **Customer service calls** and **international plan** are strong indicators of churn.
- Customers with more calls to customer service or with an international plan are more likely to churn.

## Recommendations
1. Monitor and engage with customers making frequent service calls.
2. Review and improve international plan offerings.
3. Provide tailored incentives for high-minute users.

## Conclusion
A tuned Decision Tree model successfully predicts customer churn and offers actionable insights. SyriaTel can leverage these predictions to reduce churn and increase customer retention.

## How to Run
1. Clone the repository or download the notebook.
2. Place `bigml_data.csv` in the same directory.
3. Run all cells in the notebook to reproduce analysis and results.

## Visualization Highlights
- Churn distribution and customer behavior comparison
- Boxplots and barplots to interpret feature influence
- Feature importance ranked from the final model

---

**Author**: Wachira James Mwangi  
**Project Phase**: Phase 3 – Classification
