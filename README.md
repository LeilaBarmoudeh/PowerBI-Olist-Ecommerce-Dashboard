# PowerBI-Olist-Ecommerce-Dashboard
A professional Power BI Sales and Orders Dashboard built using the Olist Brazilian E‑Commerce public dataset. Includes sales insights, order trends, delivery performance, and seller analytics.

Brazilian E‑Commerce (Olist) Power BI Dashboard 
Author: Leila Barmoudeh  
Tool: Microsoft Power BI  
Dataset: Olist Brazilian E‑Commerce Public Dataset  

---

Project Overview  
This project presents an end‑to‑end *Sales & orders Performance Dashboard* built in *Power BI*, using the real‑world *Brazilian E‑Commerce Public Dataset* published by Olist on Kaggle.  
The goal of this dashboard is to demonstrate core data analytics skills including:

 Data modeling (star schema)  
 DAX for KPIs & time intelligence  
 Data visualization and storytelling  
 Performance monitoring & business insights  
 ETL (Power Query)  
 Dashboard design best‑practices  

This dashboard is created as part of my portfolio to showcase my ability to analyze e‑commerce performance, delivery reliability, seller behavior, and customer demand patterns.

Dataset Description  
Source: *Brazilian E‑Commerce Public Dataset by Olist (Kaggle)*  
The dataset contains 100k+ real e‑commerce orders from 2016–2018 and includes:

- *Orders:* timestamps, delivery dates, order status  
- *Order Items:* product, seller, freight, price  
- *Sellers:* location (city, state)  
- *Products:* category and attributes  
- *Payments:* type and installments  
- *Customer reviews*  
- *Geolocation*  

For this dashboard, the following *cleaned, gold‑layer* tables that I preprocessed from original data in Azure SQL, were used:

- gold_fact_sales.csv  
- gold_fact_sales_items.csv  
- gold_dim_sellers.csv 
- DimDate` (DAX‑generated date dimension)  

Additional tables may be added later for deeper insights.

*Key relationships:*
- Sellers → Sales Items (seller_id)
- Sales Items → Sales (order_id)
- Sales → DimDate (order_purchase_ts)

Key Performance Indicators (KPIs)

 *Sales KPIs*
- Total Sales
- Total Orders
- Total Items Sold
- Average Order Value (AOV)


  
