# Mini-project-Loan-eligibility
Here is information and the link for the dataset: https://www.kaggle.com/datasets/devzohaib/eligibility-prediction-for-loan

Same rules as for the FIFA project.

Hints - aka we have not learned the points below yet, but we will:

For the EDA: to analyse relationships between a continuous feature and the categorical target variable (Loan_Status), create bar plots where you compare the averages for each category.
Example - ApplicantIncome vs Loan_Status: create a bar plot where you will have two bars: one for Loan_Status = YES, with the average income for people who got the loan; and another bar for Loan_Status = NO, with the average income for people who did not get the loan. (here we might expect to see that  the YES bar would be higher, since we'd expect that people with higher income might have better chances of getting a loan)

For the EDA: to analyse relationships between a categorical feature and the categorical target variable (Loan_Status), create contingency tables https://www.geeksforgeeks.org/contingency-table-in-python/.
The dataset is imbalanced, so make sure you analyse and interpret the confusion matrix. Also, if you have the time, take a look at this https://medium.com/thecyphy/handling-imbalanced-datasets-with-imblearn-library-df5e58b968f4
