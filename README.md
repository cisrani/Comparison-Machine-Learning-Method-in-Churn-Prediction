# Comparison-Machine-Learning-Method-in-Churn-Prediction
It is much more expensive to sign in a new client than keeping an existing one. It is advantageous for banks to know what leads a client towards the decision to leave the company. Churn prevention allows companies to develop loyalty programs and retention campaigns to 
keep as many customers as possible. I explored the following classification techniques and compared the accuracy and other metrics such as AUC score.
Models Explored:
1. Logistic Regression 
2. XG Boost


# About dataset:

RowNumber: corresponds to the record (row) number and has no effect on the output.

CustomerId :contains random values and has no effect on customer leaving the bank.

Surname: the surname of a customer has no impact on their decision to leave the bank.

CreditScore : can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.

Geography :a customer’s location can affect their decision to leave the bank.

Gender : it’s interesting to explore whether gender plays a role in a customer leaving the bank.

Age : this is certainly relevant, since older customers are less likely to leave their bank than younger ones.

Tenure : refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.

Balance : also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.

NumOfProducts: refers to the number of products that a customer has purchased through the bank.

HasCrCard: denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.

IsActiveMember : active customers are less likely to leave the bank.

EstimatedSalary : as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.

Exited : whether or not the customer left the bank.

Acknowledgements As we know, it is much more expensive to sign in a new client than keeping an existing one. It is advantageous for banks to know what leads a client towards the decision to leave the company. Churn prevention allows companies to develop loyalty programs and retention campaigns to keep as many customers as possible.

# All steps:
1. Data preprocessing : to check any missing values, correlated variable, and dummy encoding
2. EDA:  to develop hypothesis
3. Scaling data : it helps to improve accuracy 
4. Splitting data into data train and data test
6. Testing the accuracy on test data and plotting AUC
7. Comparing each model  


# Results :
Predicting bank's customer churn using XG Boost have higher accuracy than Logistic Regression. 

Accuracy score :
Logistic Regression = 0.812333
XG Boost = 0.857

AUC : 
Logistic Regression = 0.843
XG Boost = 0.763

