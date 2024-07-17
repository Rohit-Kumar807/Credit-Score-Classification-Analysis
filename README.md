**Credit Score Classification Analysis Using Power BI**

**About**

This project involves analyzing a dataset focused on credit score classification using Microsoft Power BI. The dataset includes various customer details and loan information. The tasks cover importing data, creating relationships, performing exploratory data analysis (EDA), and developing an interactive dashboard to visualize key insights.
Project Overview
This project aims to classify credit scores using data related to customer details and loan information. By utilizing Power BI, we create an interactive dashboard to visualize important KPIs and derive meaningful insights from the data.

**Dataset**

The data consists of two main tables:

**Customers_Details:**

Customer_ID: Unique identification of a person.

Name: The name of the customer.

Age: Age of the person.

SSN: Social security number of the person.

Occupation: Occupation of the person.

Annual_Income: Annual income of the person.

Monthly_Inhand_Salary: Monthly base salary of the person.

Num_Bank_Accounts: Number of bank accounts held by the person.

Num_Credit_Card: Number of credit cards held by the person.

Interest_Rate: Interest rate on credit cards.

Num_of_Loan: Number of loans taken from the bank.

Type_of_Loan: Types of loans taken by the person.

Num_Credit_Inquiries: Number of credit card inquiries.

Credit_Mix: Classification of the mix of credits.

Outstanding_Debt: Remaining debt to be paid (in USD).

Total_EMI_per_month: Monthly EMI payments (in USD).

Amount_invested_monthly: Monthly amount invested by the customer (in USD).

**Customers_Loan_Details:**

Customer_ID: Identification of a person.

ID: Unique identification of each month's transaction for each customer.

Month: Month of the year.

Monthly_Balance: Monthly balance amount of the customer (in USD).

Delay_from_due_date: Average number of days delayed from the payment date.

Num_of_Delayed_Payment: Average number of payments delayed by a person.

Credit_Utilization_Ratio: Utilization ratio of credit cards.

Payment_Behaviour: Payment behavior of the customer.

Credit_Score: Bracket of credit score (Poor, Standard, Good).

**Tasks**

*Import and Create Relationships:*

Import all tables into Power BI.
Establish relationships among the tables.

*Perform EDA:*

Clean and preprocess data to make it suitable for analysis.

*Create an Interactive Dashboard:*

Design an interactive dashboard with the following features:
Interactive filters and slicers.
Appropriate chart types.
Clear and concise data labels.
Proper alignment and spacing of visualizations.
Appropriate font size and color scheme.
Clear and concise titles for visualizations.
Appropriate background color to improve visibility.

*Total Loan Type:*

Create a new table “Total Loan type” having a single column that shows all types of loans.
Visualize the count of each loan type.

*Age Groups:*

Create different age groups (10-20, 21-30, 31-40, 41-50, 51-60).
Create a 100% stacked bar chart to show the count of customers in each age group based on their “Credit_Mix”.

*Amount Invested vs. EMI:*

Visualize the average amount invested monthly and average total EMI per month for different age groups.
Explain the insights obtained.

*Top 3 Occupations by Payment Behaviour:*

Find the top 3 occupations for each payment behavior based on monthly in-hand salary.
Create a visualization and table to show the insights.

*Bottom 3 Occupations by Payment Behaviour:*

Find the bottom 3 occupations for each payment behavior based on monthly in-hand salary.
Create a visualization and table to show the insights.

*Credit Mix Ratio:*

For each “Credit_Mix”, find the percentage and number of customers whose monthly in-hand salary and outstanding debt ratio is greater than 2.
Create a donut chart with proper detailing and labeling.

*Outstanding Debt vs. Annual Income:*

Create a scatter plot between outstanding debt and annual income based on credit mix.
Explain the insights obtained.

*Monthly Trends:*

For each month, find the sum of total EMI per month and sum of amount invested monthly.
Create a visualization showing the trend of investments and EMI.

*Top 5 Customers by Outstanding Debt:*

Find the top 5 customers having outstanding debt greater than or equal to incentive (calculated by subtracting monthly in-hand salary from annual income).

*Create a Dashboard:*

Design a dashboard with additional charts and visualizations.

**Usage**

*Importing Data and Creating Relationships:*

Follow the instructions in the import_relationships.pbix file to import the tables and establish relationships.

*Performing EDA:*

Use the EDA.pbix file to clean and preprocess the data, and perform exploratory data analysis.

*Creating the Dashboard:*

Open the dashboard.pbix file to see examples of interactive and dynamic dashboards.
Use slicers, filters, and appropriate chart types to visualize key insights.







































