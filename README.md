# Coffee Sales Analysis & Dashboard

## Overview

This project analyzes coffee order data using Microsoft Excel to understand sales performance across products, countries, time periods, and customers.

The project covers data preparation, data transformation, sales calculation, data analysis, and interactive dashboard development.

## Data Preparation

The project uses three related datasets:

- Orders
- Customers
- Products

Customer ID and Product ID were used to connect information across the datasets.

## Data Transformation

Excel formulas were used to enrich and transform the Orders dataset:

- XLOOKUP — retrieved customer information such as customer name, email, country, and loyalty card.
- INDEX + MATCH — retrieved product information such as coffee type, roast type, size, and unit price.
- IF — converted abbreviated coffee and roast codes into readable categories.
- Sales Calculation — calculated sales based on Quantity × Unit Price.

## Data Analysis

The analysis includes:

- Sales by coffee type and month
- Sales by country
- Top 5 customers by sales
- Sales trends over time

## Dashboard

An interactive Excel sales dashboard was developed to present the analysis clearly.

The dashboard includes:

- Sales by Country
- Total Sales Over Time
- Top 5 Customers
- Order Date filter
- Roast Type Name filter
- Size filter
- Loyalty Card filter

These interactive filters allow users to explore sales performance based on different order dates, roast types, coffee sizes, and loyalty card status.
## Files

### `rawCoffeeShopData.xlsx`

Contains the original coffee order data before transformation and analysis.

### `final of coffeeOrdersData.xlsx`

Contains the processed dataset, Excel formulas, analysis, and interactive dashboard.

## Tools

- Microsoft Excel
- XLOOKUP
- INDEX + MATCH
- IF
- PivotTable
- PivotChart
- Slicers
- Timeline

## Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Lookup
- Data Analysis
- Sales Analysis
- Data Visualization
- Dashboard Development

## Project Workflow

Raw Data  
↓  
Data Preparation  
↓  
Data Lookup & Transformation  
↓  
Sales Calculation  
↓  
Data Analysis  
↓  
Interactive Dashboard
