# Loan_Predict

The goal is to develop an algorithm that can predict loan default status when provided with a new loan application. We will assess the algorithm's performance using the AUC (Area Under the Curve) metric.

We have utilized mock data for this analysis. Each row in the dataset represents an individual loan application, containing various details about the borrower, such as demographics, income, education, and more. Additionally, it includes a crucial feature: the "maxoverduedays" column, which denotes the number of days a loan is overdue. If "maxoverduedays" exceeds 90, we categorize the borrower as having defaulted on the loan.

Here's a brief data dictionary for some of the key attributes:

1. jobpos: Job position of the borrower.
2. xxx_lat: Latitude information related to xxx.
3. xxx_long: Longitude information related to xxx.
4. legal_xxx: Legal address information related to xxx.
5. avg: Average value.
6. std: Standard deviation.
7. cnt: Count.
8. xxx_nation: Attribute indicating the borrower's nationality.
9. xxx_area: Attribute indicating the borrower's geographical area.
    
We have employed the LGBMClassifier, a powerful machine learning model, for this predictive analysis.
