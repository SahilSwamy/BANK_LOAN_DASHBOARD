Bank Loan Analysis Dashboard

📊 Project Overview
This interactive Power BI dashboard provides a comprehensive analysis of bank loan data to monitor lending health and portfolio performance. It is designed to track key performance indicators (KPIs) like total applications, funded amounts, and the distinction between "Good" and "Bad" loans to assist in data-driven risk management.

🛠 Tech Stack
The dashboard was built using the following tools and technologies:
Power BI Desktop: The primary platform for data visualization and report design.
Power Query: Used for data cleaning, transformation, and ETL processes to ensure data integrity.
DAX (Data Analysis Expressions): Implemented to create complex calculated measures, such as Good/Bad loan percentages and quarterly growth metrics.
Data Modeling: Established a robust schema to link various loan categories and temporal data for seamless filtering.

📂 Data Source
The dataset used for this analysis was sourced from a private cloud storage (Google Drive). It contains detailed records of loan applications, including:
Loan Status: Categorized into 'Fully Paid', 'Current', and 'Charged Off'.
Financials: Loan amounts, interest rates, and total payments received.
Demographics: Purpose of loan (Car, Education, Small Business, etc.) and time-based parameters.

💡 Features & Highlights
1. Business Problem
The bank needed a centralized way to track the quality of their lending portfolio. Without a clear view of "Good Loans" (performing) vs. "Bad Loans" (non-performing), it was difficult to assess risk and quarterly performance trends.

2. Goal of the Dashboard
To provide stakeholders with a high-level summary and granular breakdown of loan distributions, helping them understand where the capital is being deployed and the associated risk levels.

3. Walkthrough of Key Visuals
KPI Scorecards: Instant visibility into Total Amount Received ($473M), Total Funded Amount ($436M), and the Average Interest Rate (0.12).
Loan Issued by Quarter: A comparison bar chart showing the volume of loans vs. the performance (Good vs. Bad) across the fiscal year.
Loan Issued Categories (Donut Chart): A quick visual split showing that 86% of the portfolio consists of Good Loans, while 14% are Bad Loans.
Total Payment by Quarter: Visualizes the cash flow and payment recovery trends over time.

4. Business Impact & Insights
Healthy Portfolio: The dashboard reveals a strong 86% Good Loan rate, indicating a generally healthy lending strategy.
Quarterly Growth: There is a clear upward trend in loan applications and funding from Q1 to Q4, suggesting seasonal growth or expansion in marketing efforts.
Risk Identification: By identifying that $37M is tied up in "Bad Loans," the bank can investigate specific "Purposes" (e.g., Small Business or Medical) that might have higher default rates.

🚀 How to View
Download the .pbix file from this repository.
Open it using Power BI Desktop.
Interact with the Purpose slicer on the left to filter the entire report by specific loan types.

SnapShot:- https://github.com/SahilSwamy/BANK_LOAN_DASHBOARD/blob/main/BANK%20REPORT%20SS.png
