# Bank Deposit Optimization Project

## Introduction
This repository holds detailed documentation and code that demonstrates our approach to strategically optimizing discount allocations to enhance customer retention and maximize revenue in a subscription-based business model.

## Team Members
- Frankle Muchahary
- Roe Djer Tan
- Ritwik Roy Choudhary
- Shreyan Datta Chakraborty

## [MiniProject2-SFRRAnalytics.ipynb](./MiniProject2-SFRRAnalytics.ipynb)
This Jupyter notebook contains the practical implementation of the analyses described in the PDF. It includes:
- Code for performing EDA to understand the impact of discounts on customer lifetime.
- Transformations to linearize the relationship between discount rates and lifetime increases for more accurate modeling.
- Regression models built for each customer tier (High, Mid, Low) to forecast the effects of discounts.
- A linear optimization model using Gurobi that calculates the most revenue-efficient way to allocate discounts across different customer segments.
- Display of final solutions and quantitative analysis comparing scenarios with and without optimization.

- ## [BAN5763_OptimizationExercise_SFRRAnalytics.pdf](./BAN5763_OptimizationExercise_SFRRAnalytics.pdf)
This document from Team SFRR Analytics presents a comprehensive optimization exercise aimed at enhancing revenue through strategic discounting for a subscription-based business. The report is structured as follows:

- Project Objective: Develop a discounting model to extend customer retention and increase revenue, categorizing customers into high, medium, and low-value tiers.
- Exploratory Data Analysis (EDA): Initial analysis to understand the relationship between discounts and customer lifetime extensions across different tiers.
- Methodology:
  - Predictive Modeling: Build regression models for each customer tier to predict the impact of discounts on customer lifetime extension.
  - Optimization Modeling: Use linear optimization to determine the best distribution of discounts that maximizes revenue while adhering to the Chief Marketing Officer's constraint of limiting discounts to 20% of the customer base.
- Results and Recommendations: Outline the optimal discount distribution strategy and its expected impact on revenue.

## Final Solutions: Revenue Impact
- Distribution of Customers by Tier & Discount Depth:
  - High: 0% Discount = 40,000
  - Mid: 0% Discount = 10,000, 20% Discount = 15,000
  - Low: 0% Discount = 10,000
- Total Revenue Generated With Optimization: $57,360,857
- Total Revenue Generated Without Optimization: $51,000,000
- Incremental Revenue Generated: $6,360,857
