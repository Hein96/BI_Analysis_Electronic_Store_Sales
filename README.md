# 📊 Electronics Sales Analysis Dashboard

## Executive Summary

This project involved building a robust, end-to-end Business Intelligence solution to analyze over **10,000 rows** of electronic store sales data. The primary objective was to identify the **Product Hierarchy of revenue** and uncover **temporal patterns** in consumer behavior.

To achieve this, the solution leveraged a **Windows 11 virtual machine running on Apple Silicon (M4)** to utilize the full capabilities of the Excel DAX engine and Power Pivot.

---

## 📊 Dashboard Preview

<p align="center">
  <img src="image/BI%20Analysis.jpg" width="900"/>
</p>

## 🚀 Key Business Insights

### 💎 The "Premium" Revenue Driver

* While low-cost accessories such as cables generate high transaction volume, the **MacBook Pro Laptop** is the dominant revenue contributor.
* The product significantly drives the total sales figure of **$34.4M**.

### ⏰ Peak Shopping Hours

* Temporal analysis revealed distinct **surges in shopping activity** throughout the day.
* These insights enable:

  * Targeted marketing campaigns
  * Optimized staffing
  * Improved inventory planning

### 🌎 Geographic Variability

* Implemented custom **City extraction** from unstructured address data.
* The dashboard supports real-time comparison across major tech hubs, including:

  * San Francisco
  * Austin
  * New York

---

## 🛠 Technical Stack & Methodology

### Environment

* Windows 11 Pro via UTM on Apple Silicon (M4)

### Data Modeling

* Implemented a **Star Schema** architecture
* Created a dedicated **Calendar Dimension Table**
* Established relationships with the **Sales Fact Table**

### Advanced Analytics (DAX)

Custom measures developed:

```DAX
Total Revenue := SUM(Sales[Revenue])

Total Units Sold := SUM(Sales[Quantity Ordered])

Average Order Value := DIVIDE([Total Revenue], DISTINCTCOUNT(Sales[Order ID]))
```

### Data Engineering (Power Query)

Performed advanced ETL processes:

* Data cleaning and normalization
* URI hostname troubleshooting
* Delimiter-based string manipulation
* Custom city extraction from address field

---

## 📂 Project Scope

* ✔ End-to-end BI pipeline
* ✔ Data modeling with Power Pivot
* ✔ Advanced DAX measures
* ✔ Interactive dashboard design
* ✔ Geographic and temporal analysis

---

## 🔮 Future Improvements

* Add predictive sales forecasting
* Integrate real-time data refresh
* Expand geographic segmentation
* Deploy to Power BI Service

---

## 📌 Author Notes

This project demonstrates practical Business Intelligence skills including **data modeling, DAX analytics, and ETL engineering** in a Microsoft-centric analytics stack.
