#  Global Superstores Ltd. Sales Analysis Dashboard 
## Table of Content
 - [Description](#description)
 - [Business Introduction](#businessintroduction)
 - [Business Problem](#businessproblem)
 - [Objectives of The Analysis](#objectivesofTheAnalysis)
 - [Analysis](#analysis)
 - [Conclusion](#conclusion)
 - [Recommendations](#recommendations)

### Description
This project offers a detailed dta analytics solution using Power Bi for retail and e-commerce industry application, including data integration, visualization and actional insight extraction.


<img width="1089" height="597" alt="Global Superstores Ltd  Sales Analysis" src="https://github.com/user-attachments/assets/b680b805-e376-4766-a786-dab6e7611d47" />



### Business Introduction
Global Superstores Ltd. operates within the retail and e-commerce industry, a highly competitive and data-driven sector where customer satisfaction, profitability, and operational efficiency are essential for sustained growth. With globalization and digitization reshaping consumer behavior, the ability to track and analyze key performance indicators (KPIs) across geographies and product lines is a strategic necessity.


### Business Problem
Despite achieving $1.47M in profit and fulfilling over 51K orders, several cities and regions (notably Nigeria and certain U.S. cities) are operating at a loss, and shipping costs vary drastically across sub-categories and regions. This dashboard seeks to answer:
Where is the company gaining or losing profit, and why? How can product and logistics decisions be optimized to improve performance?


### Objectives of The Analysis
The primary objective of this analysis is to:
-	Evaluate sales performance across countries, products, and customer segments
-	Identify profitable and underperforming regions and product categories
-	Understand cost implications, especially around shipping
-	Highlight top customers and products to optimize marketing and inventory planning


### Data Transformation and Analysis
To deliver clear insights, the following steps were taken:
1.	Data Cleaning:
- Tools: Power BI
- After the data was loaded, the tables were checked for duplicates.
- In the orders table, duplicates were removed.
- The tables were then categorized into fact and various dimension tables.
- Then created a new Date table. Order Date column (1st Jan 2011-31st Dec 2014). Ship Date column (3rd Jan 2011-7th Jan 2015).
2.	Data Aggregation:
- Tools: Power Query (Power BI), DAX
-	Consolidated sales, customer, shipping, and product data across all markets (U.S., India, China, Southeast Asia, Africa).
3.	Filtering and Categorization:
- Tools: Power Query (Power BI), DAX
-	Utilized slicers for Category, Order Priority, Region, Ship Mode, and Sub-Category to enable dynamic analysis and drill-down views.
4.	Visualization Techniques:
- Tools: Power BI Visualization features
-	Tree Maps for visualizing the most valuable customers and most purchased products.  
-	Bar Charts and Pie Charts for analyzing regional profitability, top-selling products and cost comparisons.
-	Stacked Columns to showcase sub-category shipping costs and city-level losses.


### Analysis
1. **Key Metrics Overview**
-	Total Customers: 1,590
-	Total Profit: $1.47 million
-	Total Orders: 51.29K
-	Average Shipping Cost: $26.38
 - These figures indicate a strong customer base and sales volume, though further scrutiny is needed on cost efficiency, particularly in logistics.

2. **Geographic Performance**
- Top Performing Countries by Profit
-	United States (2014): $92.7K
-	India (2014): $49.1K
-	China (2014): $46.8K
- The U.S. remains the dominant market in terms of profit, followed by emerging markets like India and China, which show promising potential.

**Underperforming Regions**
- Least Profitable U.S. Cities: Burlington, Lancaster, Rockford.
- These cities reflect negative profit margins, indicating either operational inefficiencies or poor market-product fit.

**African Region Analysis**
-	Nigeria shows negative profitability compared to Benin, Egypt, and Democratic Republic of Congo, suggesting a need to reassess market strategy or distribution costs in Nigeria.
  
3. **Product-Level Insights**
   
**Top Products Sold**
-	U.S.: Canon inkjet printers, Fellowes shredders, HP cartridges
-	India: Apple smartphones, Cisco switches, Sauder desks
-	China: HP copiers, Samsung monitors, Sharp printers
  - Canon and HP products appear frequently across regions, showing consistent global demand.
    
**Most Purchased Products (Globally)**
- Highlighted SKUs: TC-20909, SC-20095, RB-19360, and Canon imageCLASS series. These represent the top-value and high-frequency products among customers.

4. **Sub-Category Performance**
   
**Top 3 Most Profitable Sub-Categories Globally**
-	Appliances
-	Copiers
-	Phones
- These categories drive the majority of the profit and should remain focal points for sales strategies.
  
**Highest Shipping Cost Sub-Categories in U.S.**
-	Appliances: $161
-	Supplies: $112
-	Phones: $67
- These costs highlight a need for cost optimization or pricing adjustments, especially for heavy or high-volume products.

**Southeast Asia Sub-Category Profitability**
-	Positive: Accessories
-	Negative: Supplies, Tables
- There’s a clear product imbalance in Southeast Asia; Accessories perform well, but Tables and Supplies may need discontinuation or repositioning.
  
5. **Logistics and Cost Analysis**
-	The average shipping cost is relatively stable, but regional differences exist.
-	Benin and Egypt show more consistent shipping costs compared to Democratic Republic of Congo, which has more volatility, likely due to infrastructure or supplier variability.

### Conclusion
-	The United States, India, and China emerged as the most profitable countries, contributing significantly to overall revenue.
-	Canon, HP, and Apple products lead in sales, indicating strong brand loyalty and market demand.
-	Some U.S. cities (Burlington, Lancaster, Rockford) and Nigeria in the African region are operating at a net loss, requiring urgent attention.
-	Appliances and Supplies carry the highest shipping costs in the U.S., impacting profitability.
-	Accessories thrive in Southeast Asia, while Supplies and Tables underperform and negatively impact regional margins.


### Recommendations
1.	Reassess Low-Profit Zones:
Strategically exit or rework pricing/logistics in underperforming cities (e.g., Rockford) and Nigeria.
2.	Product Focus:
Reinforce marketing and inventory support around top-selling products such as Canon printers, Apple phones, HP copiers.
3.	Optimize Logistics:
Investigate more efficient shipping methods or regional warehouses for high-cost items, particularly Appliances.
4.	Regional Product Alignment:
Focus on Accessories in Southeast Asia while reconsidering or bundling low-performing categories like Tables and Supplies.
