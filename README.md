# Loan-Default-Prediction

### **Problem Statement Analysis**
Loan default occurs when a borrower fails to pay back a debt according to the initial arrangement. In the case of most consumer loans, this means that successive payments have been missed over the course of weeks or months. Fortunately, lenders and loan servicers usually allow a grace period before penalizing the borrower after missing one payment. The period between missing a loan payment and having the loan default is known as delinquency. The delinquency period gives the debtor time to avoid default by contacting their loan servicer or making up missed payments.
Defaulting on a loan will cause a substantial and lasting drop in the debtor's credit score, as well as extremely high interest rates on any future loan. For loans secured with collateral, defaulting will likely result in the pledged asset being seized by the bank. The most popular types of consumer loans that are backed by collateral are mortgages, auto loans and secured personal loans. For unsecured debts like credit cards and student loans, the consequences of default vary in severity according to the type of loan. In the most extreme cases, debt collection agencies can garnish wages to pay back the outstanding debt.
###The loan is one of the most important products of the banking. All the banks are trying to figure out effective business strategies to persuade customers to apply their loans. However, **there are some customers behave negatively after their application are approved**.


### Our Model Summary:
* Developed an XGBoost binary classifier to predict whether a customer will default on a loan and achieved the AUPRC scores of 92% and 88% on test data respectively.
* Basic data inspection by Exploratory Data Analysis using Matplotlib and Seaborn giving an in-depth intuition to the important features of our dataset.
* Missing value imputation using KNN-Imputer, implemented SMOTE boosting, and carried out hyperparameter tuning using Bayesian optimization.
* Obtained Model Reason Codes (MRCs) by leveraging the concept of SHAP plots to cater to customer grievances and analyzed the Gains table to decide rejection cutoff.
