# HomeCreditDefaultRiskPrediction

## Background
In this project, I predict the applicants who default on loan repayment using Machine Learning.

Defaulting on a loan happens when repayments aren't made for a certain period of time. This incurs significant loss to the lenders. This in turn impacts the company’s financials.

In order to solve this business problem for HomeCredit group, a financial institution, I attempted to build machine learning models to identify mortgage defaulters and help the company reduce the losses from these defaulted loans. 
This helps bank to provide loans to clients capable of repayment and saves lot of money and thereby become more profitable.


## Data overview
The data was obtained from: https://www.kaggle.com/competitions/home-credit-default-risk/data. It contains data for previous loan applications. The target variable defines whether
the loan was repaid or not.

## Methods Used
* Logistic Regression
* Random Forest
* Gradient Boosting

## Results
Gradient Boostting model provided the best result predicting 129 as defaulters accurately, with Recall score 5%, AUC 0.767. This model saved $126M by identifying defaulters accurately and not lending them loans.

## Future Goals:
Refine models performance by getting more information about the clients by which the Credit company can save more money.
