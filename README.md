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





