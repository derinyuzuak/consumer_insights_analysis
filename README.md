# Consumer Insights Analysis

## Where Should We Focus to Drive Sustainable Customer Growth?

A consumer insights analysis of household purchase behavior designed to identify customer engagement patterns, areas of customer-value risk, and opportunities for targeted growth.

## Business Question

**Where should the business focus its growth efforts to drive sustainable customer value?**

## Executive Summary

Overall sales increased by **28.4%** between the first and second periods.

However, growth was not evenly distributed across households. The analysis identified **871 households with declining purchase frequency**, including **394 households where both purchase frequency and basket spend decreased**.

These 394 households generated approximately **284K in negative sales value change**. The decline was broad-based across core categories, with **Grocery representing the largest category-level sales loss at approximately 151K**.

The analysis therefore focuses on understanding customer-level risk and identifying targeted opportunities to rebuild customer engagement and value.

## Analytical Approach

The project follows a decision-oriented consumer insights framework:

**Data → Customer Behavior → Insight → Opportunity → Strategic Options**

Households were compared across two periods using:

- Purchase Frequency
- Basket Spend
- Sales Change

Households were then segmented according to whether purchase frequency and basket spend increased or decreased.

## Key Findings

### 1. Overall growth masks customer-level risk

Sales increased from approximately **3.53M to 4.53M** between the two periods.

### 2. Customer engagement is uneven

**871 households** reduced purchase frequency.

Among them, **394 households** experienced declines in both purchase frequency and basket spend.

### 3. Customer value is concentrated in a critical risk segment

The 394 households with declining frequency and basket spend generated approximately **284K in negative sales value change**.

### 4. Grocery represents the largest category-level loss

Within the critical segment, Grocery accounted for approximately **151K in sales loss**, followed by Drug GM, Meat, Meat-Pckgd, Produce and Kiosk-Gas.

### 5. Campaign analysis requires caution

Campaign exposure was explored as a potential context for the observed customer behavior. The analysis is observational and does not establish campaign effectiveness or causality.

## Strategic Opportunity

The analysis identifies an opportunity to move from broad customer engagement toward **more targeted customer recovery strategies**.

Potential directions include:

- Re-engaging households with declining purchase frequency
- Rebuilding basket value among households spending less per visit
- Prioritizing households experiencing both frequency and basket-value decline
- Investigating category-level drivers of disengagement
- Testing targeted interventions before scaling

## Data

This project uses the **dunnhumby Complete Journey** dataset, containing approximately two years of household-level transaction data for 2,500 frequent-shopper households.

The raw dataset is intentionally excluded from this repository.

## Tools

- Python
- Pandas
- Jupyter Notebook
- Git / GitHub

## Project Structure

```text
consumer_insights_analysis/
│
├── notebooks/
│   └── consumer_insights_analysis.ipynb
│
├── data/
│   └── raw/              # Excluded from GitHub
│
├── .gitignore
└── README.md

## Project Goal

The objective is not only to analyze transaction data, but to translate customer behavior into business insights, strategic opportunities, and decision-oriented recommendations.
