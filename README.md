# Bank-Customer-Churn-Analysis-Predictive-Modeling-Customer-Segmentation
This project focuses on analyzing customer churn in a European bank using a dataset of 10,000 customers. The goal is to understand what drives customers to leave and to build models that can predict churn.

Overview

Customer churn is a key problem in the banking sector. Retaining customers is usually cheaper than acquiring new ones, so identifying at-risk customers is valuable.

In this project, I explored customer data, compared churners vs non-churners, and built machine learning models to predict churn.

# Main Questions
- Which features are most associated with customers who churn?
- Can we predict churn using the available data?
 -What does the customer base look like in terms of demographics?
 - Are there differences between customers in France, Germany, and Spain?
- Can we group customers into meaningful segments?
- 
# Dataset
The dataset includes 10,000 customers with the following features:

- CustomerId: Unique ID
- Surname: Last name
- CreditScore: Credit score
- Geography: Country (France, Spain, Germany)
- Gender: Male or Female
- Age: Customer age
- Tenure: Years with the bank
- Balance: Account balance
- NumOfProducts: Number of products used
- HasCrCard: Has credit card (1 or 0)
- IsActiveMember: Active status (1 or 0)
- EstimatedSalary: Annual salary
- Exited: Churn (1 = left, 0 = stayed)

# Project Structure
bank-churn-project/

data/
  raw/
    Bank_Churn.csv
  processed/

notebooks/
  01_eda.ipynb
  02_feature_engineering.ipynb
  03_modeling.ipynb
  04_segmentation.ipynb

outputs/
  figures/
  models/
  reports/

requirements.txt
README.md
.gitignore
