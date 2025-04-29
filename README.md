# Target_retail_online_Sales_Analysis
Target_retail_online_Sales_Analysis
README - SQL-based EDA on Target Retail Dataset

This README provides a summary of the Exploratory Data Analysis (EDA) conducted on the Target Retail dataset using SQL, as part of Task 6 at Elevate Labs.

Author: Nikhil Kumar Nigam
Contact: 9215949494 | nikhilnigam@engineer.com | Er.nikhil2007@gmail.com

1. Dataset Overview

The dataset consists of several relational tables, including:
- customers
- orders
- payments

These tables were queried using BigQuery SQL to extract business insights.

2. Key SQL-Based EDA Steps & Insights
a. Customer Data Structure

- Checked data types of columns in the 'customers' table.
- Noted that customer identifiers and locations are strings, while zip codes are integers.

b. Order Time Range

- Found first and last order dates: from 2016-09-04 to 2018-10-17.

c. Geographic Spread

- Orders came from 4119 cities across 27 states.

d. Yearly and Monthly Order Trends

- Orders increased over years, peaking in 2017.
- Monthly trends showed no strong seasonality but visible drops in December.

e. Order Time of Day Analysis

- Noon and night are peak hours for placing orders.

f. State-Wise Order Patterns

- Aggregated monthly orders per state.
- Counted unique customers per state.

g. Economic Impact Analysis

- Found a 137% increase in payment value from 2017 to 2018 (Jan–Aug).
- Calculated total and average order values per state.

h. Payment Analysis

- Tracked month-wise usage of payment types (Credit Card, UPI, etc.).
- Observed high use of installment-based payments.

3. Suggestions

- Use installment payment popularity in targeted marketing campaigns.
- Analyze state-specific trends for localized promotions.
- Track high-traffic times (noon/night) for server scaling or ads.
- Monitor end-of-year dips to introduce seasonal offers.

This README serves as a guide to understanding how SQL was used for EDA on the Target dataset and provides actionable insights for business decisions.
