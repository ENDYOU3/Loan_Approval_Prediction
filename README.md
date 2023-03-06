# Loan Approval Prediction [Python]
## Objectives :
It is a classification Problem where we have to predict whether a loan would be approved or not.

## Hypothesis Generation :
### Dependent Variables:
-   **Salary**  :  Applicants with high incomes should have more chances of loan approval.
-   **Previous history**  :  Applicants who have repaid their previous debts should have higher chances of loan approval.
-   **Loan amount**  :  Loan approval should also depend on the loan amount. If the loan amount is less, the chances of loan approval should be high.
-   **Loan term**  :  A loan for a shorter term and a lower amount should have a better chance of approval.
-   **EMI**  :  The smaller the amount to be paid monthly to repay the loan, the higher the chances of loan approval.
-   **EMI per Income**  :  If the amount to be paid monthly to repay the loan per income is less than 30%, the chances of loan approval should be high.

## Dataset :
[Loan Prediction](https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/)

**Predict Loan Eligibility for Dream Housing Finance company** 

Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers.

## Implementation :
**Programming Language :** `python 3.10`

**Libraries :** `pandas`   `NumPy`   `scikit-learn`   `Matplotlib`   `seaborn`   

## Installation : 
### Run with Integrated development environment (IDE)
**Create environment and install package :** 
   -  Open file location on `terminal` or `cmd`
```bash
   cd "path"
```
   -  install `pipenv`
```bash
   pip install pipenv
```
   -  Activate a virtual environment
```bash
   pipenv shell
```
   -  Install all package in Pipfile
```bash
   pipenv install
```

