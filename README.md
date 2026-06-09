# Phonepe-Transaction-Analysis-PowerBi
Developed an interactive Power BI dashboard to analyze PhonePe transactions, payment success rates, failure reasons, loan performance, insurance transactions, money transfers, and recharge services using Power Query, DAX, and data visualization techniques.
## Project Overview

This Power BI dashboard provides an interactive analysis of PhonePe Data Analysis Dashboard. This project covers all the essential  data analysis aspects such as transaction tracking, failed payment monitoring, and visualizing multiple services like Insurance, Loans, Money Transfers, and Recharge & Bills. 

## 1. Understanding the Project Structure
Our PhonePe Data Analysis Project revolves around creating a 5-page Power BI dashboard that displays various transaction and service metrics. The primary goal is to track the following key services:

- Insurance Payments
- Loans
- Money Transfers
- Recharge and Bills
  
Each of these services will have dedicated data visualizations, and the homepage of the dashboard will provide an overview of all the metrics for a quick summary.
## 2. Dataset Overview
The dataset that contains detailed transaction information, including:

- User Details: User ID, Name, Age, Join Date
- Transaction Information: Transaction ID, Amount, Service Type, Payment Status, Date, and more
- Service Breakdown: Details about each service, such as UPI payments, insurance premiums, loan types, and recharge types.

## 1. Creating the Homepage
The homepage will summarize the entire project. Key metrics to be displayed include:

- Total Transaction Amount: The total amount transacted via PhonePe.
- Failed Payments: A visualization that tracks failed transactions and identifies the reasons (e.g., server errors, insufficient balance).
- Date Range: A slicer that allows users to select different time periods to analyze transactions.
For each service, you will show the total transaction amounts and the number of successful payments.

## 2. Service-Specific Dashboards
Next, I’ll create individual tabs for each service. The details of each service, such as insurance, loans, and money transfers, will be displayed in separate pages.Insurance

For insurance, you’ll break down transactions into categories like term life insurance, car insurance, health insurance, etc.
Similarly, for loans, you’ll analyze loan types, such as auto loans and personal loans.
Each page will contain the following visualizations:
- Amount vs. Month: A graph showing the total amount transacted each month.
- Service vs. Amount: A bar chart displaying the contribution of each service to the total transaction amount.
- Payment Status: A pie chart illustrating the payment status (successful vs. failed payments).

## 3. Failed Payment Analysis
A crucial part of the project is monitoring failed payments. In this section, you’ll analyze why certain transactions failed. This will be displayed in a pie chart showing the reasons for failure (e.g., server error, wrong payment details, insufficient balance). Tracking failed payments is essential for businesses to identify issues and take corrective actions.
## 4. Creating Interactivity
One of the highlights of this project is the interactivity. By using Power BI’s slicers, you can make the dashboard interactive. For example, users can select different date ranges, and the data displayed will automatically update based on the selection. This feature makes the dashboard more dynamic and useful for decision-makers.

## 5. Visual Customization
In Power BI, you can customize the appearance of your dashboard. For this project, you’ll use PhonePe’s purple color theme to keep the dashboard visually aligned with the brand. You can also adjust font styles, add shadows, and customize the visual appearance of the slicers and charts to make the dashboard user-friendly and visually appealing.

## 7. Final Touches: Linking the Pages
Once I have created all the pages for each service (home,  insurance, loans, money transfer, recharge & bills), the next step is to link these pages together for easy navigation. This can be done by creating buttons in Power BI, which will allow users to switch between different sections of the dashboard seamlessly.



## Tools Used

- Power BI
- Power Query
- DAX
- Microsoft Excel

## Dashboard Pages
- Total Amount
- Successful Transactions
- Failed Transactions
- Failed Payment Analysis
- Monthly Transaction Trends

### 2. Insurance Analysis
- Insurance Premium Analysis
- Payment Status
- Failed Payment Reasons
- Monthly Premium Trends

### 3. Loan Analysis
- Loan Amount Analysis
- Loan Category Performance
- Payment Status
- Monthly Loan Trends

### 4. Money Transfer Analysis
- Money Transfer Amount
- Transaction Count
- UPI Transfer Insights
- Monthly Transfer Trends

### 5. Recharge & Bills Analysis
- Recharge Amount Analysis
- Utility Bill Payments
- Payment Status
- Monthly Trends

## Key Insights

- Monitored successful and failed transactions.
- Identified major payment failure reasons.
- Compared performance across services.
- Analyzed monthly transaction patterns.
- Created interactive visualizations for business decision-making.

## Dashboard Preview

### Home Dashboard

![Home Dashboard](Images/Home_Dashboard.png)

### Insurance Analysis

![Insurance Analysis](Images/Insurance_Analysis.png)

### Loan Analysis

![Loan Analysis](Images/Loan_Analysis.png)

### Money Transfer Analysis

![Money Transfer Analysis](Images/Money_Transfer_Analysis.png)

### Recharge & Bills Analysis

![Recharge Bills Analysis](Images/Recharge_Bills_Analysis.png)

## Author

Madhuri Shivsharan

Aspiring Data Analyst skilled in Power BI, SQL, Excel, and Data Visualization.
