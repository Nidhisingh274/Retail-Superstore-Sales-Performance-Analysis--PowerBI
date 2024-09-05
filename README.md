# Retail Superstore Sales Performance Analysis

## Table of Contents
- [Overview](#overview)
- [Tools Used](#tools-used)
- [Data Understanding](#data-understanding)
- [Data Dictionary](#data-dictionary)
- [Data Preparation and Transformation](#data-preparation-and-transformation)
- [Data Modeling](#data-modeling)
- [Dashboard and Visualization](#dashboard-and-visualization)
- [Insights](#insights)
- [Recommendations](#recommendations)

## Overview
The superstore is a large retail business offering a diverse range of products including groceries, electronics, home goods, and clothing. This project aims to design a dashboard that allows for the analysis and interpretation of sales data, ultimately supporting the store manager in strategic planning and decision-making.

## Tools Used
- **Power BI**: For data visualization and dashboard creation.
- **Microsoft Excel**: For data storage and initial exploration.
- **DAX**: For creating calculated measures and columns.

## Data Understanding
- **Source file type**: Microsoft Excel Macro-Enabled Worksheet (.xlsm)
- **Columns provided** :  Order ID, Order Date, Ship Date, Ship Mode, Address, Region, Customer ID, Customer Name, Segment, Product ID, Category, Sub-Category, Product Name, Quantity, Discount, Buy Price, Price Per Each.
- **Data Dimensions**: 9994  rows and 17 columns. 

## Data Dictionary
- **Order ID**
- **Order Date**
- **Ship Date**
- **Ship Mode**
- **Customer ID**
- **Customer Name**
- **Segment**
- **Address**
- **Region**
- **Product ID**
- **Category**
- **Sub-Category**
- **Product Name**
- **Quantity**

## Data Preparation and Transformation
- **Data Cleaning**: Removed null values, adjusted data types, and standardized values.
- **Data Modeling**: Created a star schema with one fact table (Orders) and three dimension tables (Customer, Product, and Order Details).
- **DAX Calculations**: Created custom columns and measures including `Total Sales`, `Discounted Sales`, `Cart Value`, `Sales YTD`, and `Yearly Growth`.

## Dashboard and Visualization
The dashboard provides key insights into:
- **Overall Sales Performance**
- **Yearly Sales Growth**
- **Regional Sales Distribution**
- **Delivery Efficiency**
- **Product Category Insights**

## Insights
1. **Total Sales**: $2.33M with $922.94K being discounted sales.
2. **Yearly Growth**: Minimal growth (0-2%) year-over-year.
3. **Regional Performance**: California leads with $471.81K in sales.
4. **Delivery Times**: Standard Class has the longest delivery time of 5.01 days.
5. **Product Categories**: Office Supplies is the top-performing category.

## Recommendations
- **Boost Sales Growth**: Implement marketing strategies to enhance sales momentum.
- **Optimize Delivery Times**: Focus on reducing the delivery times for Standard Class.
- **Focus on Key Categories**: Strengthen sales in top-performing categories while improving the performance of weaker categories.

![Dashboard](https://github.com/user-attachments/assets/9f60874c-c28e-4c5f-9c0a-0bd016e914e2)

## Conclusion
This project provides valuable insights into the sales performance of the superstore, highlighting areas of strength and opportunities for improvement. The dashboard is a powerful tool for strategic decision-making and operational efficiency.
