
# Bank Analytics-Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/974cb6c7-411f-45d1-980b-b879fdc19b18/ReportSectiondca79156267064f8f717?experience=power-bi

## Problem Statement

The bank aims to optimize its lending operations and improve overall portfolio performance by leveraging insights from historical loan data. The available data includes information on loan verification status, loan status, loan term, loan grade, issue year, and employment length. Additionally, client-specific details such as annual income, loan amount, interest rate, funded amount, total payment, installments, and remaining balance are provided.

The bank seeks to address the following key challenges:

Risk Management:
Identify high-risk loan categories based on verification status, loan grade, and other relevant factors.
Develop strategies to minimize default rates and mitigate risks associated with specific loan attributes.

Operational Efficiency:
Optimize loan approval processes by understanding the performance of loans with different verification statuses, terms, and grades.
Streamline operations to improve overall efficiency and reduce the time taken for loan approval and processing.

Market Adaptation:
Stay competitive in the market by understanding trends in loan terms, grades, and issue years.
Adapt lending strategies to align with market demands and Clients preferences.

Data-Driven Decision-Making:
Promote a data-driven culture within the bank by providing actionable insights to decision-makers.
Implement visualizations and analytics tools that empower stakeholders to make informed decisions regarding loan portfolios.


### Steps Taken

The goal is to leverage the available data to gain a deeper understanding of the bank's lending landscape, optimize processes, and enhance client satisfaction. By addressing these challenges, the bank aims to improve overall portfolio performance, reduce risks, and stay responsive to market dynamics.

Step 1:
Reviewed the data schema and understand the meaning of each variable.
Check for missing values, outliers, and data distributions.
Understand the relationships between different variables.

Step 2:
Generate summary statistics for key variables to gain insights into the overall distribution and central tendencies.

Step 3:
Analyze loan performance based on verification status, loan grade, and other relevant attributes.

Step 4:
Analyze client-specific data to 
Identify patterns in annual income, loan amount, and interest rate for clients.

Step 5:
Analyze trends in loan terms, grades, and issue years using visualizations.
Consider adapting the loan portfolio to align with the preferences of Clients in the current market.

Step 6:
Created a  dashboard  to present key insights to decision-makers.

Step 7:
Prepare comprehensive reports summarizing key insights and proposed strategies.

## Snapshots

1. Datasheet1
![Screenshot (51)](https://github.com/GBsuraj/Project/assets/99246520/77aa5ec6-7668-46c4-ad52-bd457997dc97)

2. Datasheet2
![Screenshot (52)](https://github.com/GBsuraj/Project/assets/99246520/017b59bc-77f8-4b5f-b857-f44b97d87a1e)

3. Connecting datasheets/Data Modelling
![Screenshot (53)](https://github.com/GBsuraj/Project/assets/99246520/41c63075-e32c-4c55-9d03-1c771a7134c6)

4. Dashboard | Loan Overview
![Screenshot (54)](https://github.com/GBsuraj/Project/assets/99246520/56c827b2-9f39-4326-a162-bd6df64ce581)

5 Dashboard | Client details
![Screenshot (55)](https://github.com/GBsuraj/Project/assets/99246520/393994cd-bef7-4170-a34b-e3522b45475d)

## Key Insights

A Two page report was created on Power BI Desktop & it was then published to Power BI Service.
Following inferences can be drawn from the dashboard;

### Verification Status:
About 45.38% of the total loan amount has been verified (202M), suggesting a rigorous verification process for nearly half of the loans.
31.98% of loans are not verified (142M), which could indicate a streamlined process for certain types of loans or customer segments.

### Loan Status:
A significant portion of loans, 80.35%, are fully paid, which is a positive indicator of the bank's loan recovery performance.
Charged-off loans constitute 15.29% of the loan amount, which may be a concern as these are debts that the bank has deemed unlikely to be collected.
Current loans are at 4.36%, indicating active repayment.

### Term:

Loans with a term of 36 months have a significantly higher total loan amount (273,409,900)than those with a term of 60 months(
162,902,725), which may imply a preference or better qualification criteria for shorter-term loans.

### Grade:
The highest sum of loan amounts is allocated to Grade B (134M), followed closely by Grades C (89M) and A (87M). Lower grades (E, F, G) receive significantly less funding, likely reflecting a risk-based pricing and loan approval strategy.

### Year:

There is a clear upward trend in the amount of loans provided each year from 2007 to 2011, with 2011 showing a significant jump to $261 million. This indicates growth in the loan business or an expansion of the bank's lending activities.

### Employment Length:
Employees with 2 years and 3 years of employment length have made the highest total payments (49M and 48M respectively), which could indicate a strong financial behavior in individuals with a stable but not necessarily long employment history.
The trend shows decreasing total payments as the employment length increases beyond 3 years.

### Client Income and Loan Amount Relationship:

There is a wide range of annual incomes among clients, from 
4000 to 6000000. However, the loan amounts do not seem to be directly proportional to the annual income. For example, clients with an annual income of 
200000 have taken loans ranging from
3,000 to 5,000, which are relatively small compared to their income.

### Total Payments and Installments:

Some clients have made total payments that are higher than their respective loan amounts, which suggests that these loans might include interest and other fees.
clients having over 250 installments, indicating potentially longer loan terms or smaller periodic payments.

### Revolving Balance:

The revolving balances vary widely among clients, with some having zero revolving balance and others having balances exceeding 85,000. Higher revolving balances could be indicative of clients who utilize a significant portion of their available credit, which may be a signal of higher credit utilization or potential risk.

### Outliers and Anomalies:

There are some noticeable outliers, such as a client with an 85,000 revolving balance but only a
5,000 loan amount, which could signal high reliance on revolving credit facilities outside of this loan.
Another client with an 18,000 annual income has an
8,500 loan amount, which is a relatively high loan compared to their income.
