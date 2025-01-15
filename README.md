# Credit card fraud Detection 

## Problem Statement
. In this project, we build a machine learning model to predict fraudulent transactions based on various features of financial transactions.  
. Its primary goal is to develop a predictive model that can proactively distinguish between legitimate and fraudulent credit card transactions.
. The exploration of machine learning algorithms, including logistic regression, decision trees, random forests, aims to identify the most effective approach for fraud detection.

## Objective

. Using a machine learning model, we aim to classify whether a transaction is fraudulent or not.

. Use feature analysis:The process typically involves preprocessing and exploring the dataset, which may include features such as transaction amount, location, time, and previous transaction history

Evaluate the model's performance: After splitting the dataset into training and testing sets, various machine learning algorithms such as logistic regression, decision trees, random forests,XGBoost.

Optimize the model: Achieve accuracy greatr than 75% through hypermeter tuning and model validation. 

## Dataset
. The dataset used in this project is highly imbalanced 

.The dataset contains features related to transaction time, amount,and various anonymized features.

.Class: The target variable, where 1 indicates a fraudulent transaction and 0 indicates a legitimate transaction.

## Prerequisites
Before setting up the project, make sure you have the following installed:
### Tools:
. Python 3.7+

.   google colab Used for code execution and visualization.

### Libraries:
You will need the following Python libraries: Pandas,numpy,matplotlib,seaborn,scikit-learn,xgboost and these libraries are lilisted in requirement.txt

Install the required python packages

. pip install -r requirements.txt

. Dataset 

# Results:

 The XGBoost model achieved an accuracy of 99% with a significant improvement in detecting fraudulent tranction ,although precision for the minority class was lower.

 # Conclusion
  The project successfully demonstrated how to handle imbalanced data and build a robust machine learning model for predicting fraudent credit card tranction 
  
  .The model performs well but can be improved by handling class imbalance and further tuning.


  # Acknowledgment 

  I would like to express my special thanks of  gratitude to upgrade team for providing the dataset and project structure.


