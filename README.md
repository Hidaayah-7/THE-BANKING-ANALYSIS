THE-BANKING-ANALYSIS
A data driven view of banking activity and customer’s engagement
## Project Topic: THE-BANKING-ANALYSIS

## Project Overview
This report presents a comprehensive, data-driven analysis of banking activity, customer behavior, and loan performance using data provided by The Data Immersed (TDI) warehouse. Using Power BI for data preparation, transformation, and visualization, the objective is to uncover patterns and generate actionable insights to support strategic decisions. The focus lies on understanding customer demographics, loan approval trends, credit utilization behavior, and identifying areas for operational improvement.

### Data Source:
A CSV File gotten from The Data Immersed (TDI) Warehouse
- <a href="https://github.com/Hidaayah-7/THE-BANKING-ANALYSIS/blob/main/Comprehensive_Banking_Database%20cleaned.xlsx">Dataset</a>

### Tool Used
Microsoft Power BI 
- for Data Collection 
- for Data Cleaning and Preparation
- Analysis
- Report Creation (Dashboard)

### Data Cleaning and Preparation
At the initial stage of the Data Cleaning and Preparation, I performed the following actions;
1. Data Loading and Inspection into Ms Power BI Power Query
2. Duplicate removal
3. Removing Leading and Trailing Spaces
4. Changing Data Type
5. Spliting and Merging of Columns
6. Deleting Unneccesary Columns
7. Helping Columns Created

 ### Exploratory Data Analysis
This Exploratory Data Analysis (EDA) report aims to provide an in-depth examination of The Banking Dataset to understand the loan approval patterns, relationships, and characteristic of the data

#### Key Performance Indicators (KPIs)

Performance based on key metrics:
-	Total Customer: we have the total count of applicant as 5000
-	Total Transaction Amount (Month): The bank recorded total transaction amount of $12. 54Million.
-	Total Loan Amount (Month): The bank issued total loan of $127.51 Million.
-	Late Payments (Month):  The percentage of late payment this month is 49.48%  
-	Total Credit (Month): The Total credit this month is $27.75 million 
-	Feedback Performance: the total rate of feedback received is -0.03


### Analysis:  <a href="https://github.com/Hidaayah-7/THE-BANKING-ANALYSIS/commit/e5bc36baeb1de03b53eaa3a969768dabf846bcbd">[View Here]</a>



### Dashboard

![Banking Report](https://github.com/Hidaayah-7/THE-BANKING-ANALYSIS/blob/main/midas%20dashboard.png)



![Banking Report](https://github.com/Hidaayah-7/THE-BANKING-ANALYSIS/blob/main/midas%20dashboard.png)
<img width="945" height="526" alt="Screenshot 2025-11-04 050944" src="https://github.com/user-attachments/assets/57e1a0ac-7385-46e1-b03f-c6d5d0d3ea09" />
<img width="952" height="531" alt="Screenshot 2025-11-04 050706" src="https://github.com/user-attachments/assets/7ce040c8-2273-4a5f-887c-48c2b3b08909" />

### CUSTOMER ANALYSIS REPORT:

- Top 12 Customer Loan and Due Payment History
  
	Daniel Hernandez is the customer with the highest loan amount of $49,980.2 having an on-time payment history, followed by Elizabeth Carter with the loan of $49,985.82 having an on-time payment history and lastly Steve Torres with the loan amount of $49,915.49 having a late payment history.
The data shows the correlation between the loan due date and the date the loan was paid.


- Customer Distribution by gender
  
Male amount to 32.68%
Female has the total of 34.54%
Other has 32.78%
There is an even distribution across all genders



- Customer’s Loan Type and Loan Status

Approved and closed for mortgage has the highest count of 591 and 592 respectively, followed by approved and rejected for persona with the count of 553 and 576 respectively and lastly approved and closed of auto having the count of 566 and 554 respectively.



- Top 5 Cities with Highest Approval Rate
  
  Denver has the highest loan approval rate and loan amount of (0.40 and $3.6 million), followed by Washington (0.42 and $3.1 million), Memphis (0.40 and $3.3 million), New York (0.40 and $3.1 million), and Kansas City (0.40 and $2.9 million). This concentration suggests these regions have a strong demand for loans or effective marketing efforts targeting these areas.



### Loan Analysis Report:

- Credit Utilization by loan status
Low credit card utilization has the highest loan status while high credit card utilization has the least, which denotes a good financial management.

 

- Loan Application Status

Total loan application of 5000 was received, 1710 was approved, 1630 was rejected and 1660 was closed.



- Loan Approval Trend across the Months

 The highest loan approval was recorded in March (0.367) while the lowest loan approval was recorded in May (0.324), there is a fall in a wave-like pattern indicating a repeating cycle every few months.



- Loan Approval Predictor
  
A Loan Approval Predictor featuring credit limit, age, loan amount to compute the possible outcome of the customer 



- Percentage Credit Utilization of Debt Risk Level
  
  Very high debt risk level has a total of 53% followed by medium 21.97%, high 16.95% and lastly low 8.0% which implies that over half of the credit users fall into a critical risk category.



  - Percentage credit utilization across cities

	San Jose has the value of 127, San Francisco has the value of 98, Washington has the value of 76, followed by Tucson 75 and lastly Seattle 67.72

### METRICS OBSERVATION

1.	High Loan Volume & Utilization: The bank issued loans totaling $127.51 million this month, reflecting high customer demand. Also, Credit card utilization is directly related to loan approval; customers with lower utilization have better approval chances.
2.	Late Payments Are High: 49.48% of loan payments were late. This signals potential credit risk and inefficiencies in payment tracking or reminders.
3.	Gender and Demographic Patterns: Gender distribution is fairly even across all customers, suggesting inclusive banking practices. Also, key cities like Denver, Washington, and Memphis lead in loan approvals, indicating regional opportunities.
4.	Debt Risk Levels: Over 53% of credit users fall under "very high" debt risk, suggesting the need for credit counseling or revised credit limits.
5.	Loan Approval Trends: Approval rates fluctuate monthly, peaking in March (36.7%) and dipping in May (32.4%), suggesting seasonal patterns or policy shifts.
6.	Predictive Features Identified: Age, credit limit, and loan amount were found to be strong predictors of loan approval likelihood.




### RECOMMENDATIONS

I recommend that The Data Immersed (TDI) should:
1.	Introduce SMS/email notifications for upcoming due dates to reduce late payments.
2.	Tighten loan eligibility for customers with high credit utilization or poor repayment history.
3.	Focus marketing and lending campaigns in high-performing cities such as Denver and Washington to drive further loan growth.
4.	Offer credit education to customers with very high debt risk to improve repayment behavior and financial literacy.
5.	Leverage the predictor variables (age, credit limit, loan amount) to enhance loan approval efficiency and fairness.


 #### Conclusion:
 
This report provides a data-backed overview of customer lending behavior and operational efficiency within the bank. With nearly half of payments made late and a large percentage of customers falling into high debt risk categories, the bank must adopt proactive strategies to manage credit risk and optimize loan approvals. Data insights from Power BI have highlighted key performance metrics and regional strengths, empowering leadership with a clearer understanding of where to act and invest for growth and stability.




