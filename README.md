# Deep-Dive-EDA-Telco-Customer-Churn

The Dataset Used in this project is taken from Kaggle. Exploratory data analysis consists of analyzing the main characteristics of a data set usually by means of visualization methods and summary statistics. The objective is to understand the data, discover patterns and anomalies, and check assumptions before performing further evaluations. 

Each row represents a customer, each column contains customer’s attributes described on the column Metadata. The raw data contains 7043 rows (customers) and 21 columns (features). The “Churn” column is our target.

The main Idea of this project is to deep dive some factors that affect customers churn the most.

At first, we do data cleaning such missing value and duplicated rows handling. Next we do basic Statistical Summary. 

## Feature Overview

- CustomerID: A unique ID that identifies each customer.

- Gender: The customer’s gender: Male, Female

- Age: The customer’s current age, in years, at the time the fiscal quarter ended.

- Senior Citizen: Indicates if the customer is 65 or older: Yes, No

- Married (Partner): Indicates if the customer is married: Yes, No

- Dependents: Indicates if the customer lives with any dependents: Yes, No. Dependents could be children, parents, grandparents, etc.

- Number of Dependents: Indicates the number of dependents that live with the customer.

- Phone Service: Indicates if the customer subscribes to home phone service with the company: Yes, No

- Multiple Lines: Indicates if the customer subscribes to multiple telephone lines with the company: Yes, No

- Internet Service: Indicates if the customer subscribes to Internet service with the company: No, DSL, Fiber Optic, Cable.

- Online Security: Indicates if the customer subscribes to an additional online security service provided by the company: Yes, No

- Online Backup: Indicates if the customer subscribes to an additional online backup service provided by the company: Yes, No

- Device Protection Plan: Indicates if the customer subscribes to an additional device protection plan for their Internet equipment provided by the company: Yes, No

- Premium Tech Support: Indicates if the customer subscribes to an additional technical support plan from the company with reduced wait times: Yes, No

- Streaming TV: Indicates if the customer uses their Internet service to stream television programing from a third party provider: Yes, No. The company does not charge an additional fee for this service.

- Streaming Movies: Indicates if the customer uses their Internet service to stream movies from a third party provider: Yes, No. The company does not charge an additional fee for this service.

- Contract: Indicates the customer’s current contract type: Month-to-Month, One Year, Two Year.

- Paperless Billing: Indicates if the customer has chosen paperless billing: Yes, No

- Payment Method: Indicates how the customer pays their bill: Bank Withdrawal, Credit Card, Mailed Check

- Monthly Charge: Indicates the customer’s current total monthly charge for all their services from the company.

- Total Charges: Indicates the customer’s total charges, calculated to the end of the quarter specified above.

- Tenure: Indicates the total amount of months that the customer has been with the company.

- Churn: Yes = the customer left the company this quarter. No = the customer remained with the company. Directly related to Churn Value.


