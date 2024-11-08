# LITA_Capstone_Project
This project analyses retail sales data to uncover key insights into product performance, regional sales distribution, and monthly trends. The objective is to create an interactive Power BI dashboard to visualize total sales, top-selling products, and revenue by region, enabling better business decision-making based on sales performance

### Project Title: Sales Performance Analysis for a Retail Store
[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

### Project Overview
---
This project explores a retail store's sales data to gain insights into product performance, regional sales, and monthly trends. The analysis began with Excel, using pivot tables and formulas to identify key metrics and sales patterns. SQL queries were then used to uncover additional insights, including product category totals, top customers, and regional contributions. Finally, an interactive Power BI dashboard was created to visually represent the findings, helping to identify high-performing products and trends across different regions.

### Data Sources
---
The data for this project was provided in an Excel file titled "LITA Capstone Dataset.xlsx", containing detailed sales information by order ID, product, customer, and region. For SQL analysis, the data was converted to a CSV (comma-delimited) file for easier import into SQL Server

### Tools Used
---
- Microsoft Excel [Download Here](https://www.microsoft.com)
  1. For Data Cleaning
  2. For Analysis
  3. For Data Visualization
- SQL – Structured Query Language for querying of Data
- PowerBI - Used for creating an interactive dashboard to visualize key insights
- GitHub - For Portfolio Building

### Data Cleaning and Preparations
---
During the initial phase of the Data cleaning and preparations, the following actions were performed:
1. Data loading and Inspection
2. Handling missing variables
3. Data Cleaning and formatting

### Exploratory Data Analysis
---
EDA questions focused on understanding sales trends, product performance, and regional contributions:
- Which products generate the highest and lowest total revenue?
- What are the monthly sales trends, and are there any seasonal patterns?
- How does sales performance vary across different regions?
- Who are the top 5 customers by total purchase amount?
- Which product categories contribute most to total sales?

### Data Analysis
---
```SQL
SELECT format(SUM(Sales),'c') AS Total_Sales, Product
FROM [dbo].[LITA Sales DAta]
GROUP BY Product
```

### Data Visualizations
---
![Sales Performance Analysis Dashboard](https://github.com/user-attachments/assets/bb9c6b20-ab56-4ca6-a56c-0f16333758c2)

### Results/Findings
---
- The analysis results are summarized as follows:
- Top-Performing Products: Analysis revealed that certain products generated significantly higher revenue than others, with Hats and Shoes leading in total sales.
- Regional Performance: The South region contributed the highest percentage of sales, while the West had the lowest sales volume.
- Seasonal Trends: Sales increased markedly in certain months, indicating potential seasonality in customer purchasing behaviour.
- Top Customers: Identified the top 5 customers who contributed a notable share of the overall revenue.


### Recommendations
---
Based on the analysis carried out, we recommend the following:

### Limitations
---
