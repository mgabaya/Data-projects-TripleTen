# Sprint 8: Bank Machine Learning Project

## Project description
Beta Bank customers are leaving: little by little, chipping away every month. The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones.

We need to predict whether a customer will leave the bank soon. You have the data on clients’ past behavior and termination of contracts with the bank.

**GOAL:** Build a model with the maximum possible F1 score. To pass the project, you need an F1 score of at least 0.59. Check the F1 for the test set. Additionally, measure the AUC-ROC metric and compare it with the F1.

## Data description
Churn.csv file

**Features**

RowNumber — data string index <br/>
CustomerId — unique customer identifier<br/>
Surname — surname<br/>
CreditScore — credit score<br/>
Geography — country of residence<br/>
Gender — gender<br/>
Age — age<br/>
Tenure — period of maturation for a customer’s fixed deposit (years)<br/>
Balance — account balance<br/>
NumOfProducts — number of banking products used by the customer<br/>
HasCrCard — customer has a credit card<br/>
IsActiveMember — customer’s activeness<br/>
EstimatedSalary — estimated salary<br/>

**Target**

Exited — сustomer has left
