# Default-of-Credit-Card-Clients-Python-Machine-Learning-Project
Credit card companies make money by collecting interest on loans. When a customer is unable to pay, then the loan defaults. Defaults cause credit card companies to lose money by either writing the balance off completely, or by selling the balance to a collection agency for pennies on the dollar. Therefore, determining if a customer will default in the next month can allow a bank to implement loss mitigation strategies before an account defaults.

This project will investigate whether customer account information can be used to build machine learning models to successfully predict whether or not a customer will default on their next month's payment. This is a supervised learning problem; the data set has two different labels ((1=yes will default next month, 0=no will not default next month). 

I will use Python to evaluate the performance of six machine learning model frameworks to understand if the dataset has the ability to accurately predict whether a customer will default on their account in the next month.   The six models used are Logistic Regression, KNN classifier, Bagging classifier, AdaBoost classifier, XGBoost classifier, and Random forest classifier. The hyperparameters will be be optimized and model performance will be evaluated using a confusion matrix, classification report (Precision, Recall, and F1), and Area under the Receiver operating characteristic curve (AUCROC). 


Here is the attribute information for the 25 variables:

ID: ID of each client  
LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit)  
For reference, 1 USD = 28.66 NT dollar on 10/10/2020.  
SEX: Gender (1=male, 2=female)  
EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)  
MARRIAGE: Marital status (1=married, 2=single, 3=others)  
AGE: Age in years  
PAY_0: Repayment status in September, 2005 (-2 means no account usage, -1 means balance paid in full, 0 means at least the minimum payment was made, 1 means payment delay for one month, 2 means payment delay for two months, … 8 means payment delay for eight months, 9=payment delay for nine months and above)  
PAY_2: Repayment status in August, 2005 (scale same as above)  
PAY_3: Repayment status in July, 2005 (scale same as above)  
PAY_4: Repayment status in June, 2005 (scale same as above)  
PAY_5: Repayment status in May, 2005 (scale same as above)  
PAY_6: Repayment status in April, 2005 (scale same as above)  
BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)  
BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)  
BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)  
BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)  
BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)  
BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)  
PAY_AMT1: Amount of previous payment in September, 2005 (NT dollar)  
PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar)  
PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar)  
PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar)  
PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar)  
PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar)  
default.payment.next.month: Default payment (1=yes, 0=no)  

