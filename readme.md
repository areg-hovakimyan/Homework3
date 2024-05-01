# Customer Retention Strategy

## Overview
This repository contains analysis and prediction models for customer retention. The focus is on using survival analysis to estimate customer churn probabilities and to determine a budget for retention strategies.

## Data
The data includes customer demographics, service usage behavior, tenure, churn status, and the calculated Customer Lifetime Value (CLV).

## Model
We use Accelerated Failure Time (AFT) models, including Weibull, Log-Normal, and Log-Logistic models to predict the time until a customer churns. We then identify at-risk customers based on their survival probabilities within a year.

## Retention Budget Calculation
Based on the survival analysis, we estimate the annual retention budget. This budget is calculated as a percentage of the CLV of at-risk customers, which are those with a high probability of churning within the next year.
