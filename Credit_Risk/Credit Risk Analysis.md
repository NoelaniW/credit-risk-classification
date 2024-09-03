Credit Risk Analysis

The purpose of this analysis was to evaluate and predict loan risk (healthy loans versus high risk loans) using variables from lender history; such as loan size, interest rate, borrower income, borrower debt to income percentage, total debt, number of accounts and if borrower has any negative information on their account.
First we assigned the variables in to labels and features, then established training and test data sets. We then fit a logistic regression model using the training data and ran the model to determine the predicted risk and the actual risk for lender loans.


-The precision to recall score for lender_risk_1 is 1 to 1.
-The precision to recall score for lender_risk_2 is nearly 1 to 1 as well, varying by 0.01.
-The accuracy score for this model was 0.99.

This model was highly effective at determining loan risk for borrowers with 70% of borrowers in good standing.
