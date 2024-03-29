**Project**
- This project aimed to identify the factors contributing to customer churn in financial institutions, specifically within the credit card system, using machine learning models. 
- After thorough analysis, the Light GBM model stood out as the top-performing classifier, achieving the highest recall and F1 scores.
- The analysis identified six critical features that significantly influence churn, offering valuable insights for institutions to strategically address and improve customer retention.


**Dataset**

- The credit card churn dataset consists of 10,000 customers and 18 features, including age, salary, marital_status, credit card limit, and credit card category, among others.
- With only 16.07% of customers having churned, the dataset presents a class imbalance challenge.


Data source: https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers?datasetId=982921&sortBy=voteCount&select=BankChurners.csv

The features in the data set are as follows:
- CLIENTNUM - Client number. Unique identifier for the customer holding the account.
- Attrition_Flag - Internal event (customer activity) variable - if the account is closed then 1 else 0.
- Customer_Age - Demographic variable - Customer's Age in Years.
- Gender - Demographic variable - M=Male, F=Female.
- Dependent_count - Demographic variable - Number of dependents.
- Education_Level - Demographic variable - Educational Qualification of the account holder (example: high school).
- Marital_Status - Demographic variable - Married, Single, Divorced, Unknown.
- Income_Category - Demographic variable - Annual Income Category of the account holder.
- Card_Category - Product Variable - Type of Card (Blue, Silver, Gold, Platinum).
- Months_on_book - Period of relationship with bank.
- Total_Relationship_Count - Total no. of products held by the customer.
- Months_Inactive_12_mon - No. of months inactive in the last 12 months.
- Contacts_Count_12_mon - No. of Contacts in the last 12 months.
- Credit_Limit - Credit Limit on the Credit Card.
- Total_Revolving_Bal - Total Revolving Balance on the Credit Card.
- Avg_Open_To_Buy - Open to Buy Credit Line (Average of last 12 months).
- Total_Amt_Chng_Q4_Q1 - Open to Buy Credit Line (Average of last 12 months).
- Total_Trans_Amt - Total Transaction Amount (Last 12 months).
- Total_Trans_Ct - Total Transaction Count (Last 12 months).
- Total_Ct_Chng_Q4_Q1 - Change in Transaction Count (Q4 over Q1).
- Avg_Utilization_Ratio - Average Card Utilization Ratio.

