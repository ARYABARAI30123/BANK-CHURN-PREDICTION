# BANK-CHURN-PREDICTION
## Bank Churn Prediction is a project aimed at predicting customer churn in a bank. Churn prediction is a critical task for businesses, especially in the banking sector, as it helps in retaining customers and improving customer satisfaction. This project utilizes machine learning algorithms to analyze customer data and predict whether a customer is likely to leave the bank.

# Introduction
### Customer churn, also known as customer attrition, occurs when customers stop doing business with a company. In the banking industry, understanding and predicting churn is crucial for customer retention and business growth. This project aims to predict bank churn using machine learning techniques, allowing banks to take proactive measures to retain customers.

# Dataset
### The dataset used for this project contains various features such as customer ID, credit score, age, tenure, balance, number of products, etc. These features are used to train machine learning models to predict churn.

## LINK FOR THE DATASET IS: https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction

# Dependencies
### Python 3.x
### Pandas
### NumPy
### Scikit-Learn
### Matplotlib
### Seaborn
### jOblib

# Features
## Credit Score: Credit score of the customer
### Age: Age of the customer
### Tenure: Number of years the customer has been with the bank
### Balance: Account balance of the customer
### NumOfProducts: Number of bank products the customer is using
### HasCrCard: Whether the customer has a credit card (1 for yes, 0 for no)
### IsActiveMember: Whether the customer is an active member (1 for yes, 0 for no)
### EstimatedSalary: Estimated salary of the customer
### Exited: Whether the customer exited the bank (1 for yes, 0 for no, i.e., churned or not churned)

# Visualizations
### ![Screenshot 2023-10-29 115620](https://github.com/ARYABARAI30123/BAK-CHURN-PREDICTION/assets/139233575/f3dece7b-7e67-480c-830e-f619008907b1)
### 1.Age :- Slightly Tail-Heavy:Age has a few people who are significantly older than the rest in the dataset.
### 2.CreditScore - Mostly Above 600:The majority of clients have a credit score above 600.
### 3.Balance - Fairly Normal Distribution: ignoring the first group of data, the remaining balances follow a shape similar to a bell curve, which is  typical of many natural phenomena.
### 4.EstimatedSalary :: Salaries are fairly evenly distributed across the dataset

### ![Screenshot 2023-10-29 114558](https://github.com/ARYABARAI30123/BAK-CHURN-PREDICTION/assets/139233575/3d537a46-5097-46f5-8781-261c3bdefed7)
### There is no significant intercorrelation between our features.

### ![Screenshot 2023-10-29 120038](https://github.com/ARYABARAI30123/BAK-CHURN-PREDICTION/assets/139233575/5f208da7-93d1-41be-9f45-118a74eb1fb9)
### The dataset is imbalanced because a large majority (80%) of clients are retained, making the 'Churned' class a minority.






# Model
###  The project uses a machine learning model, such as a Logistic Regression,Gaussian Navies Bayes, and KNN, to predict customer churn based on the provided features.

# Evaluation
### The model is evaluated using metrics such as accuracy, precision, recall, and F1-score.

# MODEL DEPLOYMENT
### Model is being deployed using streamlit.











