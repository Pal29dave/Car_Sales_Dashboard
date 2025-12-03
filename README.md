Car Sales Analytics Dashboard


📌 Project Overview
This project presents a comprehensive analysis of automotive sales data to uncover key performance indicators (KPIs) and market trends. Using 23,907 transactional records, I built an interactive Tableau Dashboard to visualize sales performance across time, regions, and car models.

The goal is to provide stakeholders with actionable insights on Weekly Sales Trends, YTD performance, and Manufacturer Market Share.

📂 Dataset Description

Source: Car Sales.csv (raw transactional data)
Volume: 23,907 rows
Dimensions: 16 columns

Key Dataset Categories
Category	Columns
Transaction Details	Car_id, Date, Price
Customer Data	Customer Name, Gender, Annual Income, Phone Number
Car Specifications	Company, Model, Engine, Transmission, Color, Body Style
Dealer Information	Dealer Name, Dealer Number, Dealer Region
🛠 Tools & Technologies

Tableau Desktop – dashboard creation, calculated fields, visual analytics

Microsoft Excel – initial data inspection and cleaning

Data Processing – transformations for YTD metrics and time intelligence

🔄 Project Workflow
1. Data Loading

Imported the raw CSV into Tableau.

2. Data Cleaning

Converted data types (dates, prices)

Addressed missing values in Customer Name and Region

3. Data Modeling

Built calculated fields for YTD Sales and YoY Growth

Grouped car models by Body Style for categorical insights

4. Dashboard Design

Grid-based layout with high-level KPIs at the top

Filters for Dealer Region, Company, and Time Period

Intuitive navigation and clean color theme

📊 Dashboard Components

YTD Key Metrics – Total Sales, Average Price, Cars Sold

Weekly Sales Trend – line chart showing seasonal patterns

Sales by Body Style – donut chart comparing SUVs, Sedans, Hatchbacks

Company-Wise Performance – bar chart ranking manufacturers by revenue

Regional Map – geospatial distribution of sales across regions

📈 Key Insights
Financial Performance

YTD Total Sales: $386M

YTD Average Price: $28,050

Trend Analysis

Consistent upward trend throughout the year

15% sales spike in Weeks 35–40, likely tied to year-end promotions

Top Performers

Body Style: SUVs lead with 42% of total revenue; Sedans follow at 35%

Manufacturer: Chevrolet & Ford jointly contribute 18% of total sales volume

Color Preference: “Black” and “Pale White” are the most purchased colors, aligning with high-resale models
