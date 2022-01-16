# Deloitte_Hackathon_predict_Loan_Defaulter
## PROBLEM STATEMENT
- Aim of the problem is to predict loan status based on certain features.

- Dataset Description Train.csv - 67463 rows x 35 columns (Includes target column as Loan Status)

Attributes:

- ID: unique ID of representative
- Loan Amount: loan amount applied
- Funded Amount:loan amount funded
- Funded Amount Investor: loan amount approved by the investors
- Term: term of loan (in months)
- Batch Enrolled: batch numbers to representatives
- Interest Rate: interest rate (%) on loan
- Grade: grade by the bank
- Sub Grade: sub-grade by the bank
- Employment Duration: duration
- Home Ownership: Owner ship of home
- Verification Status: Income verification by the bank
- Payment Plan: if any payment plan has started against loan
- Loan Title: loan title provided
- Debit to Income: ratio of representative's total monthly debt repayment divided by self reported monthly income excluding mortgage
- Delinquency - two years: number of 30+ days delinquency in past 2 years
- Inquires - six months: total number of inquiries in last 6 months
- Open Account: number of open credit line in representative's credit line 19. Public Record: number of derogatory public records
- Revolving Balance: total credit revolving balance
- Revolving Utilities: amount of credit a representative is using relative to revolving_balance
- Total Accounts: total number of credit lines available in representatives credit line
- Initial List Status: unique listing status of the loan - W(Waiting), F(Forwarded)
- Total Received Interest: total interest received till date
- Total Received Late Fee: total late fee received till date
- Recoveries: post charge off gross recovery
- Collection Recovery Fee: post charge off collection fee
- Collection 12 months Medical: total collections in last 12 months excluding medical collections
- Application Type: indicates when the representative is an individual or joint
- Last week Pay: indicates how long (in weeks) a representative has paid EMI after batch enrolled
- Accounts Delinquent: number of accounts on which the representative is delinquent
- Total Collection Amount: total collection amount ever owed
- Total Current Balance: total current balance from all accounts
- Total Revolving Credit Limit: total revolving credit limit
- Loan Status: 1 = Defaulter, 0 = Non Defaulters

Test.csv - 28913 rows x 34 columns(Includes target column as Loan Status) Sample Submission.csv - Please check the Evaluation section for more details on how to generate a valid submission.

The challenge is to predict the Loan Status

Knowledge and Skills Big dataset, underfitting vs overfitting Optimising log_loss to generalise well on unseen data

- Data source: https://www.kaggle.com/ankitkalauni/bank-loan-defaulter-prediction-hackathon
