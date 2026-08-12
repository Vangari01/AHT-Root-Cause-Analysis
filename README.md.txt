# AHT Root Cause Analysis

## Business Problem

Average Handle Time (AHT) is an important customer service
performance metric. This project analyzes customer chat data
to identify factors associated with higher AHT.

## Objective

Identify key factors associated with high Average Handle Time
and recommend actionable opportunities for improvement.

## Dataset

The project uses a synthetic customer-service dataset
containing 10,000 chat records.

## Tools

- Python
- Pandas
- Jupyter Notebook
- Tableau
- Excel
- PowerPoint

## Analysis

The analysis examined the relationship between AHT and:

- Chat Category
- Repeat Messages
- Navigation Time
- Agent Response Time
- Customer Response Time
- Applications Used
- Escalation
- Technical Error
- Shift

## Key Findings

- Fraud chats had the highest average AHT among the categories analyzed.
- Higher repeat-message counts were associated with higher AHT.
- Higher navigation time was associated with higher AHT.
- Higher agent response time was associated with higher AHT.
- Higher customer response time was associated with higher AHT.
- Escalated chats had higher average AHT than non-escalated chats.
- Shift differences were relatively small.

## Recommendations

- Simplify application navigation.
- Improve agent response efficiency.
- Reduce repeated customer communication.
- Review escalation drivers.
- Prioritize high-AHT chat categories for workflow review.

## Dashboard

The Tableau dashboard provides interactive KPI monitoring
and analysis of AHT across chat categories and operational factors.

## Project Structure

data/  
notebooks/  
tableau/  
presentation/  
images/  

## Note

This project uses synthetic data for portfolio and analytics
practice purposes. Findings should be validated against actual
operational data before business decisions are made.