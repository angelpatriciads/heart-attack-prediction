# Credit Submission Detectors using Machine Learning

#### -- Project Status: Completed

## Project Objective
Credit scoring which helps in evaluating the repayment ability of potential borrowers is one of the most important issues for lending or loan business. At this time, the development of Machine Learning is very rapid and its use can be implemented in various ways, one of which is in lending or loan business. In this study, researchers used the Decision Tree model to determine debtors who did not repay their loans. This study will compare the performance of the three models including Decision Tree, Logistic Regression, and Support Vector Machine. The results show that the Decision Tree model works much better.

### Methods Used
* Machine Learning
* Logistic Regression
* Support Vector Machines
* Decision Tree

### Language
* Python

### Module
* skicit-learn
* matplotlib
* pandas
* numpy
* seaborn

## Conclusion
Based on the Classification Report, the highest F1-score was obtained in the decision tree model of 0.94 or 94%, the result of which is close to 1, indicating that the model performance is very good. This model uses parameters in the form of 'criterion':'gini','max_depth': 8,'max_features': 'log2','splitter': 'best'.
The interpretation of the results obtained by researchers has the conclusion that to find out whether a debtor is eligible to receive credit or not by taking into account the amount of annual income, loan class, interest rate, percent of income, home ownership
mortgage/rent, history of default. In the application that is formed, when it is submitted, it will appear approved or rejected according to the eligibility level of the recipient of the credit customer.

## Getting Started
1. You can access the raw data [here](https://github.com/angelpatriciads/credit-cark-risk-classification/blob/main/credit_risk_dataset.csv) within this repo.
2. All of the scripts are being kept [here](https://github.com/angelpatriciads/credit-cark-risk-classification/blob/main/credit_risk_classification.ipynb).
