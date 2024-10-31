# Fraudulent Transaction

Case study addressed in the postgraduate course in Artificial Intelligence and Machine Learning.
This project aims to analyze transaction data organized in a dataset and classify whether the transaction in question is a fraud or not.

The dataset was generated with the help of chatgpt-4o and has the following structure:
- Credit card number
- Transaction amount
- Transaction location
- Type of merchant
- Time of transaction
- Day of week
- Expense category
- Cardholder age
- Cardholder gender
- Payment history
- Card limit
- Current balance
- Number of previous transactions
- Number of supplementary cards
- Average value of previous transactions
- Number of transactions in other countries
- Credit utilization
- Previous suspicious transactions
- Time since last transaction
- Class (fraud)

## Resolution

1. Identify the type of problem
    R: The problem is a binary classification problem, where we need to predict whether a transaction is fraudulent or not

2. Check which algorithms we can use for resolution
    R: Random forest, SVM, Naive Bayes, Neural networks and KNN

3. Check if there are values ​in the dataframe that could interfere with the result
    R: The data was generated through a chatgpt prompt, so we know that the structure already comes with well-filled data, only needing to categorize textual data, such as: Transaction Location, Card Owner's Gender, payment history, purchase category, day of the week the purchase occurred.

4. Evaluate the models and select the best one based on metrics such as: accuracy, confusion matrix and f1 score
