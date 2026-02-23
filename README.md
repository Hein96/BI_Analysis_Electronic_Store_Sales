# BI_Analysis_Electronic_Store_Sales

Executive Summary: Electronics Sales Analysis Dashboard
Project Overview

This project involved building a robust, end-to-end Business Intelligence solution to analyze over 10,000 rows of electronic store sales data. The goal was to identify the "Product Hierarchy" of revenue and uncover "Temporal Patterns" in consumer behavior. To achieve this, I utilized a Windows 11 virtual machine on an M4 Mac to leverage the full power of the Excel DAX engine and Power Pivot.

Key Business Insights

The "Premium" Driver: While low-cost accessories like cables represent a high volume of transactions, the MacBook Pro Laptop is the primary revenue driver, contributing significantly to the total sales of $34.4M.

Peak Shopping Hours: Analysis of the temporal data revealed specific "surges" in shopping activity throughout the day, providing actionable data for targeted marketing and inventory management.

Geographic Variability: By engineering a custom City extraction from unstructured address data, the dashboard allows for real-time comparison of sales performance across major tech hubs like San Francisco, Austin, and New York.

Technical Stack & Methodology

Environment: Windows 11 Pro via UTM on Apple Silicon (M4).

Data Modeling: Implemented a Star Schema by creating a dedicated Calendar Dimension Table linked to the Sales Fact Table.

Advanced Analytics (DAX): Developed custom measures including Total Revenue, Average Order Value (AOV), and Total Units Sold.

Data Engineering: Used Power Query for advanced ETL (Extract, Transform, Load) processes, including URI hostname troubleshooting and delimiter-based string manipulation.
