# 📊 Sales Insights Dashbord | 
# <img src= "https://www.google.com/search?q=adidas+logo&oq=adidas+logo&gs_lcrp=EgZjaHJvbWUyDAgAEEUYORixAxiABDIKCAEQABixAxiABDIHCAIQABiABDIHCAMQABiABDIHCAQQABiABDIHCAUQABiABDIHCAYQABiABDIHCAcQABiABDIHCAgQABiABDIHCAkQABiABNIBCjE0OTczajBqMTWoAgiwAgHxBeGOoxHLwCyg&sourceid=chrome&ie=UTF-8#vhid=hRwr6wlK0it0lM&vssid=_HtLHaOClFcuZseMP35GA8Ak_42" alt="Adidas Logo" width="40"/> Adidas Sales Analysis Dashboard

A dynamic *Power BI* dashboard providing a deep dive into the sales performance of Adidas products across various branches. This analysis uncovers key trends in customer behavior, product performance, and payment methods to drive strategic business decisions.

![Adidas Dashboard Preview](images/dashboard-preview.png) 


## 📖  Overview
A comprehensive Power BI Dashboard built to transform raw sales data into actionable insights. This interactive report allows stakeholders to monitor key performance indicators (KPIs), analyze sales trends over time, and understand customer and product performance across different regions.

---
 ## ✨ Features
- 📈 *Executive Summary*: View top-level KPIs like Total Revenue, Total Profit, Units Sold, and Profit Margin at a glance.
- 📅 *Trend Analysis:* Analyze sales and profit performance over time with interactive line and bar charts.
- 🗺️ *Geographical View:* Visualize sales distribution across states and cities on an interactive map.
- 📦 *Product & Category Analysis:* Drill down into performance by product category and sub-category to identify best-sellers and top profits.
- 👥 *Customer Segmentation:* Analyze sales by customer segments to identify top-performing groups.
- ⚙️ *Interactive Filtering:* Use slicers for Year, Quarter, Month, Region, and Product Category to slice the data dynamically.

 
---
 ## 🛠️ Built With
- *Microsoft Power BI Desktop* – For data modeling, DAX, and visualization
- *Power Query* – For data extraction, transformation, and loading (ETL)
- *DAX (Data Analysis Expressions)* – For creating calculated columns and measures. 

---
## 💡 Key DAX Measures
This project utilizes advanced DAX to calculate critical business metrics:
- Total Sales = SUM(Sales[Sales Amount])
- Total Profit = SUM(Sales[Profit])
- Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
- YTD Sales = TOTALYTD([Total Sales], 'Date'[Date])
- YoY Growth = DIVIDE([Total Sales] - CALCULATE([Total Sales], SAMEPERIODLASTYEAR('Date'[Date])), CALCULATE([Total Sales], SAMEPERIODLASTYEAR('Date'[Date])))

---
##  Build Dashboard :
Data visualization for the data analysis (DAX) was done in Microsoft Power BI Desktop.
Shows visualizations from Sales insights :

                                                                      Key Insights
<img width="1920" height="1080" alt="Screenshot 2025-09-15 140209" src="https://github.com/user-attachments/assets/f948564b-a739-4301-ad17-e4dfeafc6e2e" />


---
## 👩‍💻 Developed by *Jhachhavi*
      Data Analyst | Visual Storyteller 
---


