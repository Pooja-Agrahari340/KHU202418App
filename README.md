# Credit card fraud Detection 

## Problem Statement:
. In this project, we build a machine learning model to predict fraudulent transactions based on various features of financial transactions.  
. Its primary goal is to develop a predictive model that can proactively distinguish between legitimate and fraudulent credit card transactions.
. The exploration of machine learning algorithms, including logistic regression, decision trees, random forests, aims to identify the most effective approach for fraud detection.

## Objective:

. Using a machine learning model, we aim to classify whether a transaction is fraudulent or not.

. Use feature analysis:The process typically involves preprocessing and exploring the dataset, which may include features such as transaction amount, location, time, and previous transaction history

. Evaluate the model's performance: After splitting the dataset into training and testing sets, various machine learning algorithms such as logistic regression, decision trees, random forests,XGBoost.

. Optimize the model: Achieve accuracy greatr than 75% through hypermeter tuning and model validation. 

## Dataset:
. The dataset used in this project is highly imbalanced 

.The dataset contains features related to transaction time, amount,and various anonymized features.

.Class: The target variable, where 1 indicates a fraudulent transaction and 0 indicates a legitimate transaction.

## Prerequisites:
Before setting up the project, make sure you have the following installed:
### Tools
. Python 3.7+

. google colab Used for code execution and visualization.

. Reguired python packeges listed in requirement.txt

### Libraries
You will need the following Python libraries: Pandas,numpy,matplotlib,seaborn,scikit-learn,xgboost and these libraries are lilisted in requirement.txt

Install the required python packages

. pip install -r requirements.txt

. Dataset https://drive.google.com/file/d/1oQFOXc_8FghLYz80uuoECtK7wWd5BXt7/view?usp=drive_link

# Results:
## Model Performance
. The XGBoost model achieved an accuracy of 99%, which demonstrates the model's high ability to distinguish between fraudulent and legitimate transactions. This performance is promising, especially given the imbalanced nature of the dataset where fraudulent transactions are much fewer than legitimate ones.

## Comparison with Other Models

. While XGBoost performed the best in terms of overall accuracy, other models such as Random Forest and Logistic Regression were also tested. These models gave slightly lower accuracy and precision scores, showing that tree-based models, like XGBoost, are more suited for this type of imbalanced classification problem.


 # Conclusion:
 ## Effective Fraud Detection

 . The project demonstrated that machine learning, particularly using algorithms like XGBoost, can effectively predict fraudulent credit card transactions. The high accuracy achieved shows the model's ability to classify transactions correctly, making it a valuable tool for fraud detection systems.

  # Acknowledgment:

  I would like to express my special thanks of  gratitude to upgrade team for providing the dataset, project structure and detailed step by step guidance .


