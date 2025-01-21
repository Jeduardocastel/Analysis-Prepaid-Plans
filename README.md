# Revenue Analysis of Megaline Prepaid Plans 💲📱

## Project Overview
As a Data Analyst for Megaline, a telecommunications operator, your task is to determine which of their two prepaid plans, Surf and Ultimate, generates more revenue. This analysis will help the marketing team optimize their advertising budget.

The project focuses on statistical hypothesis testing to analyze customer behavior and revenue patterns. The dataset contains information on 500 customers, including their demographics, usage of calls, SMS, and internet, and subscription plans for the year 2018.

## Dataset Description
The project uses five tables:

* users: Customer details (e.g., age, city, subscription date, and tariff plan).
* calls: Data on call durations and dates.
* messages: SMS activity logs.
* internet: Records of data usage in megabytes.
* plans: Information about the Surf and Ultimate plans, including costs and limits.

## Key Objectives
Analyze customer behavior and usage trends for calls, SMS, and internet.
Compare the average revenue generated by each plan.
Use statistical tests to validate which plan contributes more to the company's revenue.

## Tariff Plans Overview
* Surf
Monthly fee: $20
Includes: 500 minutes, 50 SMS, 15 GB data
Over-limit charges: $0.03/min, $0.03/SMS, $10/GB

* Ultimate
Monthly fee: $70
Includes: 3000 minutes, 1000 SMS, 30 GB data
Over-limit charges: $0.01/min, $0.01/SMS, $7/GB
Note: Calls are rounded up to the next minute, and monthly data usage is rounded up to the next GB.

## Tools and Methods
Python: Data cleaning, analysis, and visualization.
Statistical Hypothesis Testing: Evaluate revenue differences between plans.
Libraries: Pandas, Matplotlib, SciPy.
