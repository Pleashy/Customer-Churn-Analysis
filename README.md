# Project Name: Telco Customer-Churn-Analysis
https://www.kaggle.com/datasets/blastchar/telco-customer-churn/download?datasetVersionNumber=1
----
# Project Objectives: Problem Statement
How many customers left ?
Whatis at risk ?
How much profit is at risk ?
Demographics of the customers?
Did charges contribute to why these customers left or did they leave because their charges expired?
If they left because their contract expired, what caan be done to retain them?
-----
# Data Sourcing
Data was downloaded from Kaggle
----
# Data Cleaning 
The headers had different data types, some headers started with small letters while others started with small letter; it was all changed to Proper data type. 
Underscores were added to the headers that had compound names for easy understanding and presentation.
No duplicates were found. 
The total charges had missing values ; the average of the total values were used to fill it up.
----
# Data Transformation
A conditional column was created afor senior_citizen column for a better analysis , instead of 1 and 0 to represent if you are a senior_citizen or not, it was changed to Yes to represent 1 and No to represent 0.
The employees Tenure was also grouped understanding and interpretation.
----
# Insights and Observations:
Out of 7043 customers, 1869 customers churned leaving 5174 customers which means 17.80% of the total customers churned.
These churned customers generated over $2,862,926.90 income for the organization.
Customers who were on month_to_month contract churned the most which means they did no renew their contract.
Churned customers that used their services for less than 10 years churned the most.
The number of customers that churned and that of the current customers who use Fibre_optic interenet services were almost the same and that is anything but good.
The Electronic_check method of payment seems stressfree as most churned customers used that payment.
----
# Recommendations:
A more effective customer retention strategy should be put in place; from the analysis it was seen that most customers who have being with the company for less than 10 year which comprises of those that are month_to_month contract churned the most. Contract renewal bonus, discounts on renewal or even a reduced on subsequent charges can be introduced.
A seamless and easy payment procedure should be put in place espeically the Electronic check method as it has the highest churn, people cannot be recieving debit and still be stressed.
Fibre Optic internet services needs to made better for the customers.
---
