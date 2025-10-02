Risky Customer Identification & Financial Behavior Analysis
1. Project Overview
This project is designed to identify and analyze risky customers for a bank, specifically those who are likely to default on their financial obligations. By leveraging data analysis and business intelligence, the project aims to uncover patterns in customer behavior, enabling the bank to mitigate financial risks, reduce potential losses, and make more informed lending decisions.

The core of this analysis involves Exploratory Data Analysis (EDA) to understand the relationships between various customer attributes and their financial health, culminating in a comprehensive dashboard built with Power BI.

2. Tech Stack & Tools
Database: MySQL

Backend & Analysis: Python

Data Processing: Data Cleaning, Data Preprocessing, EDA

Data Visualization & Reporting: Power BI

3. Project Workflow
Data Extraction: Customer data was extracted from the bank's MySQL database.

Data Cleaning and Preprocessing: The raw data was cleaned to handle missing values, correct inconsistencies, and format it for analysis. This step was crucial for ensuring the accuracy of the insights.

Exploratory Data Analysis (EDA): In-depth EDA was performed using Python to explore relationships between different variables, identify correlations, and uncover initial insights into customer behavior.

Insight Generation & Visualization: The findings from the EDA were used to build an interactive and insightful dashboard in Power BI, providing a clear visual representation of customer risk profiles and financial patterns.

4. Key Findings & Analysis Summary
The analysis revealed several key correlations and patterns in customer financial behavior:

Deposits and Savings Behavior
A high correlation between Bank Deposits and Saving Accounts was observed. This suggests two possibilities:

These metrics measure overlapping financial behavior (e.g., the total funds a customer keeps with the bank).

Customers who are active depositors also tend to be diligent in maintaining or growing their savings balances, indicating good financial health.

Income, Age, and Wealth Accumulation
Moderate correlations were found between Age and Estimated Income with various account balances (Superannuation, Savings, Checking). This reflects a common financial lifecycle trend:

As individuals get older and their income increases, they tend to accumulate more savings and retirement funds.

This demographic may also carry higher, yet manageable, credit card balances or loans as their purchasing power grows.

Low Correlation with Properties Owned
Interestingly, property ownership showed a weak correlation with the banking variables analyzed. This could be due to external factors not captured in the dataset, such as:

Geographic location and real estate market conditions.

Inheritance or family-owned properties.

Investment properties versus primary residences.

Business vs. Personal Banking
A moderate link between Business Lending and personal Bank Loans suggests that some customers manage both personal and business debts through the bank. However, business lending was relatively uncorrelated with other deposit or property-related metrics, indicating it may serve a distinct customer segment with different financial needs.


5. Conclusion:
This project successfully demonstrates how a combination of data analysis and visualization can be used to identify high-risk customers. The insights derived from the EDA and presented in the Power BI dashboard provide the bank with a powerful tool to proactively manage credit risk and improve overall portfolio health.
