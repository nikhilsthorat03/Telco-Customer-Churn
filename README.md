# Telco-Customer-Churn

The data set that we will use is called telco.csv and it is a data from the Telecommuncations industry. 
The purpose of the project is to predict if the customer will stay with the company or they will leave the company. 
Various machine learning classification algorithms were used to perform these predictions and the end result was displayed using a Tableau Dashboard and a Webapp deployed using Herokup.

The dataset to be used in this session is a CSV file named telco.csv, which contains data on telecom customers churning and some of their key behaviors. It contains the following columns:

Features:

customerID: Unique identifier of a customer.
gender: Gender of customer.
SeniorCitizen: Binary variable indicating if customer is senior citizen.
Partner: Binary variable if customer has a partner.
Dependents: Binary variable if customer has dependent.
tenure: Number of weeks as a customer.
PhoneService: Whether customer has phone service.
MultipleLines: Whether customer has multiple lines.
InternetService: What type of internet service customer has ("DSL", "Fiber optic", "No").
OnlineSecurity: Whether customer has online security service.
OnlineBackup: Whether customer has online backup service.
DeviceProtection: Whether customer has device protection service.
TechSupport: Whether customer has tech support service.
StreamingTV: Whether customer has TV streaming service.
StreamingMovies: Whether customer has movies streaming service.
Contract: Customer Contract Type ('Month-to-month', 'One year', 'Two year').
PaperlessBilling: Whether paperless billing is enabled.
PaymentMethod: Payment method.
MonthlyCharges: Amount of monthly charges in $.
TotalCharges: Amount of total charges so far.
Target Variable:

Churn: Whether customer 'Stayed' or 'Churned'.

Performed various steps to increase the model accuracy and used classification machine learning algorithms to predict the results.

Results:
Logistic Regression model gave an accuracy of 80% on the test dataset.
