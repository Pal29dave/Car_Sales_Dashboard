# Car_Sales_Dashboard
📌 Project Overview

This project involves the comprehensive analysis of automotive sales data to uncover key performance indicators (KPIs) and market trends. Using a dataset of 23,907 transactional records, I developed a dynamic Tableau Dashboard to visualize sales performance across different time frames, regions, and car models.

The goal of this analysis is to provide stakeholders with actionable insights regarding Weekly Sales Trends, Year-to-Date (YTD) performance, and manufacturer market share.

📂 Dataset Description

The dataset consists of historical sales transactions with the following characteristics:

Volume: 23,907 Rows

Dimensions: 16 Columns

Data Source: Car Sales.csv (Raw transactional data)

Key Features

Category

Columns

Transaction Info

Date, Price, Car_id

Customer Profile

Customer Name, Gender, Annual Income, Phone Number

Vehicle Specs

Company, Model, Engine, Transmission, Color, Body Style

Dealer Info

Dealer Name, Dealer Number, Dealer Region

🛠 Tools & Technologies

Tableau Desktop: Used for data visualization, calculated fields, and dashboard interactivity.

Microsoft Excel: Used for initial data inspection and preliminary cleaning.

Data Processing: Data cleaning and transformation to ensure accuracy in YTD calculations.

🔄 Project Steps

Data Loading: Imported the raw CSV dataset into Tableau.

Data Cleaning:

Validated data types (converting dates, ensuring numerical consistency for prices).

Checked for and handled missing values in the Customer Name and Region columns.

Data Modeling:

Created Calculated Fields for Time Intelligence (YTD Sales, YoY Growth).

Grouped car models by Body Style for categorical analysis.

Dashboard Design:

Designed a grid layout focusing on high-level KPIs at the top and granular details at the bottom.

Implemented filters for Dealer Region, Company, and Time Period.

📊 Dashboard Contents

The Tableau dashboard includes the following visualizations:

YTD Key Metrics: A scorecard displaying Total Sales, Average Price, and Cars Sold.

Weekly Sales Trend: A line chart visualizing the fluctuation of sales over weeks to identify seasonality.

Sales by Body Style: A donut chart showing the distribution of sales (SUV vs. Sedan vs. Hatchback).

Company-Wise Performance: A horizontal bar chart ranking manufacturers by revenue.

Regional Map: A geospatial view of sales distribution across dealer regions.

📈 Key Insights & Results

Based on the analysis of the 23,907 records, the following insights were derived:

Financial Performance: The Year-to-Date (YTD) Total Sales amounted to $386M, with a YTD Average Car Price of $28,050.

Trend Analysis: Sales demonstrated a consistent upward trend, with a 15% spike observed in weeks 35–40 (likely aligned with end-of-year dealer promotions).

Top Performers:

Body Style: SUVs dominated the market, accounting for 42% of total revenue, followed by Sedans at 35%.

Manufacturer: Chevrolet and Ford were the top-performing companies, collectively contributing to 18% of total volume.

Color Preference: "Black" and "Pale White" were the most popular car colors, correlating with higher resale value models.




