# Car Sales Analysis Dashboard

This project analyzes a large car sales dataset using Microsoft Excel and Power BI.
The goal of the project was to clean and prepare the raw data in Excel, build a structured data model in Power BI, and create a dashboard that reveals useful business insights about revenue, vehicles, sellers, states, and sales trends over time.

## Project Overview

The dataset contains car sales information such as:
- Year
- Make
- Model
- Trim
- Body
- Transmission
- VIN
- State
- Condition
- Odometer
- Color
- Interior
- Seller
- Market Value
- Selling Price
- Sale Date

The raw dataset was first cleaned and optimized in Excel before being imported into Power BI for modeling and dashboard creation.

## Tools Used

- Microsoft Excel
- Power BI
- Power Query
- DAX

## Data Cleaning in Excel

Before building the dashboard, I cleaned the dataset in Excel by:
- checking for missing values
- removing duplicate rows where necessary
- standardizing column formats
- ensuring dates were properly formatted
- preparing the data for analysis and reporting

This step helped make the dataset more reliable and easier to work with in Power BI.

## Data Model in Power BI

To improve performance and reporting clarity, the dataset was structured into a star schema model with:

- **Fact Table**
- **Date table**
- **Seller table**
- **State table**
- **Vehicle table**

This model made it easier to analyze the data by date, seller, vehicle type, and location.

## Dashboard Pages

### 1. Overview Dashboard
This page gives a high-level summary of the business with KPIs such as:
- Total Revenue
- Total Market Value
- Total Cars Sold
- Average Selling Price
- Average Discount %

It also shows:
- Revenue Growth %
- MoM Growth %
- Top Make Revenue Share %
- Top Seller Contribution %


### 2. Seller Analysis
This page focuses on seller performance and helps identify:
- Revenue by State
- Average Revenue and Total cars by Seller
- A Table summarizing Total Revenue, Count of cars sold by each Seller
- Top 10 Sellers & First State


### 3. Vehicle Analysis
This page analyzes vehicle performance by:
- Odometer & Selling price by Model & Make
- sales trend by Body type
- sales trend by Transmission
- sales trend by Model

### 4. Time & Pricing Analysis
This page explores:
- sales trend by month
- sales by quarter
- sales trend by Day
- selling price vs market value by Vehicle


## Key Measures / KPIs

Some of the key KPIs used in the report include:
- Total Revenue
- Total Market Value
- Total Cars Sold
- Average Selling Price
- Average Discount %
- Revenue Growth %
- Month-over-Month Growth %
- Top Make Revenue Share %
- Top Seller Contribution %

## Insights From the Analysis

This dashboard helps answer questions such as:
- Which vehicle makers generate the most revenue?
- Which models perform best?
- Which sellers contribute most to sales?
- How does selling price compare to market value?
- How does mileage affect pricing?
- What are the sales trends over time(month & day)?

## What I Learned

This project helped me improve my skills in:
- Excel data cleaning and preparation
- Power Query transformation
- Star schema modeling
- DAX calculations
- Power BI dashboard design
- Business reporting and data storytelling

### Overview
<img width="1226" height="636" alt="Overview" src="https://github.com/user-attachments/assets/c2750ba0-39bd-47ff-89d7-f912a5eb1ddc" />
### Seller Analysis
<img width="1225" height="634" alt="Seller analysis" src="https://github.com/user-attachments/assets/b98138ec-89e7-4c42-864e-2fd605276566" />
### Vehicle Analysis
<img width="1226" height="633" alt="Vehicle Analysis" src="https://github.com/user-attachments/assets/8863b6f4-4abb-47a1-afc5-d89f51fd55a3" />
### Time & Pricing Analysis
<img width="1231" height="632" alt="Pricing Analysis" src="https://github.com/user-attachments/assets/6eee0015-c8d7-4e3f-abbc-7c2ff625dad7" />
### Time & Pricing Analysis
![Time and Pricing Analysis](screenshots/time-pricing-analysis.png)
