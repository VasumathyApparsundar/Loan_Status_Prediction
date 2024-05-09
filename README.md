# Loan Status Prediction

**Introduction**:

This dataset comprises detailed information about various loan applications, including applicant demographics, loan details such as amount, type, and interest rates, as well as bank account details and approval statuses. Each entry represents a unique loan application, providing valuable insights into the lending process and customer profiles.

**Data Description**:

1. **loan_application_id**: Unique identifier for each loan application.
2. **application_date**: Date when the loan application was submitted.
3. **credit_score**: The credit score of the applicant, representing their creditworthiness.
4. **loan_type**: Type of loan (e.g., Secured, Unsecured).
5. **loan_category**: Category of the loan (e.g., Home, Personal, Auto).
6. **interest_rate**: The interest rate associated with the loan.
7. **loan_amount**: The total amount of the loan requested by the applicant.
8. **loan_term**: The duration of the loan in months.
9. **asset_value**: Value of the asset (e.g., property) against which the loan is secured.
10. **interest_amount**: The total interest amount payable over the loan term.
11. **coapplicant_name**: Name of the co-applicant, if any.
12. **coapplicant_income**: Income of the co-applicant, if any.
13. **status**: Status of the loan application (e.g., Approved, Denied).
14. **loan_account_id**: Unique identifier for the approved loan account.
15. **loan_interest_rate**: The interest rate applied to the approved loan.
16. **loan_approved_date**: Date when the loan was approved.
17. **loan_amount_availed**: The actual amount availed by the applicant from the approved loan.
18. **total_loan_amount**: The total amount of the loan including interest.
19. **loan_amount_due**: Amount due on the loan.
20. **loan_status**: Status of the loan (e.g., Completed, In Progress).
21. **loan_amount_paid**: Amount already paid by the applicant towards the loan.
22. **loan_completion_date**: Date when the loan was fully paid or completed.
23. **Customer Name**: Name of the customer.
24. **customer_gender**: Gender of the customer.
25. **customer_age**: Age of the customer.
26. **customer_marital_status**: Marital status of the customer.
27. **customer_no_of_dependents**: Number of dependents of the customer.
28. **customer_education**: Educational qualification of the customer.
29. **customer_income**: Income of the customer.
30. **customer_occupation**: Occupation of the customer.
31. **customer_person_with_disability**: Whether the customer has a disability.
32. **customer_address**: Address of the customer.
33. **customer_date_of_joining**: Date when the customer joined.
34. **account_number**: Bank account number of the customer.
35. **account_type**: Type of bank account (e.g., Savings, Current).
36. **minimum_balance**: Minimum balance required for the bank account.
37. **account_balance**: Current balance in the bank account.
38. **account_interest_rate**: Interest rate associated with the bank account.
39. **has_debit**: Whether the account has a debit card.
40. **has_credit**: Whether the account has a credit card.
41. **has_chequebook**: Whether the account has a chequebook facility.
42. **has_netbanking**: Whether the account has net banking facility.
43. **account_status**: Status of the bank account (e.g., Active, Frozen).
44. **account_last_active_date**: Date when the account was last active.
45. **branch_name**: Name of the bank branch.
46. **Loan Approved?**: Whether the loan was approved or not.

**Target Variable**:

The target variable is **Loan Approved?**

**Problem Statment**:

The task is to develop a machine learning model that accurately predicts the approval status of loan applications based on various features such as applicant demographics, loan details, and bank account information. Given a dataset containing historical loan application records, the objective is to classify each application as either "Approved" or "Not Approved".

**Insights**:

1. **Loan Security:** Among the 1567 loans, the majority (795) are secured, indicating a preference for secured loans which are often associated with lower interest rates due to reduced risk for lenders.

2. **Loan Categories:** A significant proportion (556) of customers opted for Personal Loan category, suggesting a demand for loans tailored to personal needs such as education, medical expenses, or home renovations.

3. **Loan Approval Rate:** Out of all the loan applications, 982 were approved, indicating a relatively high approval rate. This could imply lenient approval criteria or a strong creditworthy applicant pool.

4. **Gender Distribution:** Male customers outnumber female and other gender categories, indicating a potential gender disparity in financial decision-making or access to financial products.

5. **Account Types:** The majority of customers (727) hold Savings accounts, highlighting the popularity of savings products for day-to-day banking needs, while a smaller proportion (337) have Current accounts, which are typically used for business transactions.

6. **Account Status:** A significant portion (752) of customer accounts are active, suggesting ongoing engagement with banking services and possibly indicating a healthy customer-bank relationship.

7. **Marital Status:** The majority (862) of customers are married, which may have implications for their financial goals, risk tolerance, and borrowing capacity.

8. **Customer Education:** Matriculate is the most common education level among customers, indicating that a substantial portion of the customer base may have completed high school education or equivalent.

9. **Loan Approval Insight:** The approval rate of 982 out of 1567 loans indicates that the majority of applicants were successful in obtaining loans, which could reflect well on the financial health and creditworthiness of the applicant pool.

10. **Occupation & Approval:** There's a relationship between customer occupation and loan approval. Certain occupations might be perceived as more stable or reliable, increasing the chances of loan approval.

11. **Income Impact:** Customer income significantly affects loan approval. Higher incomes are associated with a higher likelihood of loan approval, as indicated by the boxplot analysis.

12. **Account Balance Influence:** More substantial account balances correlate with higher loan approval rates. Customers with healthier account balances may be seen as less risky borrowers.

13. **Marital Status & Approval:** Married customers tend to have more approved loans compared to single or other marital status categories, suggesting marital status might play a role in loan approval decisions.

14. **Education Level & Approval:** Customers with a matriculate education level have more approved loans than others, indicating that education might influence loan approval outcomes.

15. **Credit Score Impact:** Credit score doesn't significantly affect the loan approval process. Other factors like income and account balance might carry more weight in decision-making.

16. **Asset Value & Approval:** Higher asset values increase the likelihood of loan approval. Valuable assets may serve as collateral or indicate financial stability, boosting approval chances.

17. **Income vs. Loan Amount:** Loans are more likely to be approved when the loan amount is lower relative to the customer's income. This suggests lenders prefer conservative borrowing relative to income levels.

18. **Account Balance vs. Income:** Loan approval rates are higher when both account balance and customer income are high. This indicates that a combination of financial stability and income strength positively influences loan approval decisions.

**Recommendations for Customers Applying for Loans:**

1. **Consider Collateral Options:** For customers seeking secured loans, exploring collateral options such as property or valuable assets can strengthen their loan applications and potentially secure more favorable loan terms, including lower interest rates and higher loan amounts. Customers should carefully assess their assets and consider leveraging them strategically to support their borrowing needs while minimizing risk.

2. **Maintain Healthy Account Balances**: Customers should prioritize building and maintaining healthy account balances, as this positively influences loan approval rates. By regularly saving and managing their finances responsibly, customers can demonstrate financial stability and improve their chances of loan approval.

**Recommendations for the Bank:**

1. **Diversify Loan Portfolio:** While secured loans are popular, consider offering a variety of loan products to cater to different customer needs and risk profiles. This could include unsecured loans or specialized loans targeting specific purposes like education or home improvement.

2. **Enhance Gender Sensitivity:** Implement measures to promote gender equality in financial services, such as targeted marketing campaigns, gender-neutral loan products, and diversity training for staff. This can help address any potential disparities in access to financial products and services.

**Machine Learning Outcomes:**



Based on the analysis using logistic regression and stratified k-fold classifier, we can draw the following conclusions:

1. **Model Performance:** The logistic regression model achieved an accuracy of approximately 72.61% and an F1-score of around 81.00%. Meanwhile, the stratified k-fold classifier yielded a slightly higher mean accuracy of about 74.67% and a mean F1-score of approximately 82.81%.

2. **Prediction Accuracy:** Both models demonstrated reasonable accuracy in predicting loan status, with the stratified k-fold classifier performing slightly better overall. This suggests that the models are capable of distinguishing between approved and rejected loan applications with a moderate level of accuracy.

3. **Model Robustness:** The use of stratified k-fold cross-validation helps to improve the robustness of the model evaluation by reducing the risk of overfitting and providing more reliable performance metrics. This approach ensures that the model's performance is consistent across different subsets of the data.

**Conclusion:**

In summary, the project demonstrates the feasibility of using logistic regression and stratified k-fold cross-validation for predicting loan status based on the available dataset. While the models exhibit reasonable performance, ongoing refinement and validation are essential for ensuring their effectiveness in real-world applications.


