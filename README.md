I Have done the project for the uderstanding of ML concept that can apply to the real world Data Set 
So I have Selected some what Complex Data Related to Credit Card Fraud Detection 
### Aim:- Prediction of default payment in next month 
1) To Study the factor which affects the default payment next month 
2) Predict the default payment can occur or not based on the customer information 
3) To detect the number of default users 
4)To study which age group people more affecting to default payment 
5) To study the bill delay is significant for default payment in next month 
### Problem Statement: 
1) Indentify of default payment before occuring event alert the organization and they can prevent it 
2) Probability of default payment occur 
3) Indentify which age group people moniter closely 
4) Indentify bill delay poeple are contributed to default payment 

### Data Information:-
LIMIT_BAL:
Description: The credit limit for the account.
Data Type: Integer (int64)
Non-Null Count: 30000

SEX:
Description: Gender of the account holder.
Data Type: Integer (int64)
Non-Null Count: 30000
Values:
1: Male
2: Female

EDUCATION:
Description: Level of education of the account holder.
Data Type: Integer (int64)
Non-Null Count: 30000
Values:
1: Graduate School
2: University
3: High School
4: Others

MARRIAGE:
Description: Marital status of the account holder.
Data Type: Integer (int64)
Non-Null Count: 30000
Values:
1: Married
2: Single
3: Others

AGE:
Description: Age of the account holder.
Data Type: Integer (int64)
Non-Null Count: 30000

PAY_0 to PAY_6:
Description: Repayment status for the past 6 months.
Data Type: Integer (int64)
Non-Null Count: 30000
Values:
-1: Paid duly
1: Payment delay for one month
2: Payment delay for two months
... (and so on)

BILL_AMT1 to BILL_AMT6:
Description: Amount of bill statement for the past 6 months.
Data Type: Integer (int64)
Non-Null Count: 30000

PAY_AMT1 to PAY_AMT6:
Description: Amount of previous payment for the past 6 months.
Data Type: Integer (int64)
Non-Null Count: 30000

default payment next month:
Description: Whether the account holder will default the payment next month.
Data Type: Integer (int64)
Non-Null Count: 30000
Values:
0: Not default
1: Default

This Dataset contains 30000 entries with 24 columns, and each column represents different attributes and features related to credit card accounts and payment behavior.

