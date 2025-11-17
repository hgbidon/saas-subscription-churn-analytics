# SaaS Subscription & Churn Analytics
A data-driven analysis of product usage, subscription behavior, and customer churn patterns using the SaaS Subscription & Churn Analytics dataset. Built in Databricks using Python, Pandas, and Seaborn.

## Project Overview
This project analyzes multiple SaaS datasets to understand how product usage, support interactions, and subscription attributes relate to customer churn. It focuses on identifying behavioral signals that differentiate churned vs. retained accounts.

## Goals
- Explore feature adoption and usage consistency.
- Quantify support friction and satisfaction levels.
- Evaluate subscription metadata (plan tier, billing frequency, MRR).
- Compare behavior between churned and retained accounts.
- Produce actionable insights aligned with SaaS retention strategy.

## Dataset Summary
The following tables from the Kaggle dataset were used:
- ravenstack_accounts.csv
- ravenstack_subscriptions.csv
- ravenstack_feature_usage.csv
- ravenstack_support_tickets.csv
- ravenstack_churn_events.csv

This enables a full-view analysis across usage, support, subscription history, and churn outcomes.

## Features Engineered
Key metrics created during analysis include:
- unique_features_used
- total_feature_usage
- total_errors
- MRR, ARR, subscription_days
- escalation_count, average_satisfaction
- is_churned churn flag

## Analyses Performed
### Feature Adoption
- Unique features used by churned vs. retained users
- Total usage volume comparisons
- Error-related friction patterns

### Support Ticket Analysis
- Escalation frequency vs. churn probability
- Satisfaction score trends
- Ticket volume and first-response-time analysis

### Subscription Insights
- Plan tier distribution of churned users
- Monthly vs. annual billing and its impact on churn
- Revenue implications of churn using MRR/ARR

### Product Usage Behavior
- Usage consistency patterns over time
- Drop-offs before churn
- Comparison of high-usage vs. low-usage customers

## Key Insights
- Retained accounts demonstrate broader feature adoption and higher overall interaction.
- Accounts with escalated support tickets show a significantly higher churn rate.
- Monthly billing plans exhibit higher churn risk than annual contracts.
- Downgrades frequently occur before churn and signal future risk.
- A small number of high-MRR accounts contribute disproportionately to revenue loss during churn.

## Visualizations
The Databricks notebook includes:
- Feature adoption comparisons
- Churn vs. retained boxplots
- Escalation rate analysis
- Churn by plan tier
- MRR-based churn visualizations

## Repository Structure
```sql
├── notebooks/
│ └── saas_churn_analytics.ipynb
├── README.md
```

## Future Enhancements
- Build a simple churn prediction model (logistic regression baseline)
- Cohort retention analysis
- Customer Lifetime Value (CLV) estimates
- Visual dashboard using Tableau or Power BI

## Author
Hana Gabrielle Bidon  
Data Analyst — SaaS Analytics, Product Insights, Marketing Analytics  
GitHub: https://github.com/hgbidon  
LinkedIn: https://linkedin.com/in/hgbidon
