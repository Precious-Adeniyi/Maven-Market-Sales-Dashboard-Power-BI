# 📊 Maven Market Sales Dashboard – Power BI

## Overview
An end-to-end business intelligence dashboard built in Power BI for Maven Market,
a multi-national grocery chain operating across the USA, Mexico, and Canada.
Covers transaction data from 1997–1998.

## Dashboard Highlights
- **18,325** current month transactions (goal: 17,339 | +5.69%)
- **$71.68K** current month profit (goal: $67.87K | +5.61%)
- **496** current month returns (goal: 482 | +2.9%)

## Key Features
- KPI cards with goal tracking and sparklines
- Weekly revenue trending bar chart
- Brand-level breakdown: transactions, profit, profit margin & return rate
- Geographic revenue map across North America
- Revenue vs. Target gauge chart
- Country-level treemap (USA, Mexico, Canada)

## Data Model
Star schema with the following tables:
- `Transaction_data` & `Return_Data` — fact tables
- `Customers`, `Products`, `Stores`, `Regions`, `Calendar` — dimension tables
- `Key Measures` — DAX measure table

## Tools Used
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query (ETL)

## Screenshots
### Dashboard
Maven-Market Sales Dashboard

### Data Model
Maven-Market Sales Data Model
