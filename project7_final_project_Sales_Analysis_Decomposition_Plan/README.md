
# 📊 Sales Analysis Dashboard - README

## 1. Project Overview
This project was created as part of the final onboarding assignment for the role of Junior Analyst at Zomato.  
The goal was to analyze the performance of restaurant sales using a provided dataset and deliver insights through a Tableau dashboard.

## 2. Tableau Dashboard Link
👉 https://public.tableau.com/views/SavannahRodriguez-FinalProject/SalesAnalysis?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## 3. Data Cleaning & Preparation Steps
- Loaded `Cleaned_Sales_Data.xlsx` and `Cleaned_Restaurant_Data.xlsx` into Tableau.
- Joined datasets on `r_id` using a Left Join.
- Converted `order_date` field to Date type.
- Filtered out invalid sales records (`sales_amount <= 0`).
- Created calculated fields for `Year`, `Month`, and `Quarter` from the `order_date`.
- Created KPI fields: `Total Revenue`, `Total Quantity`, and `AOV (Average Order Value)`.

## 4. Visualizations in the Dashboard
- **KPI Cards** for Total Revenue, Total Quantity, and AOV.
- **Line Chart** to display revenue trends over time (monthly and quarterly).
- **Bar Chart** to compare total revenue by city.
- **Heatmap** to observe seasonal revenue patterns across months and cities.
- Filters for `Year`, `City`, and `Quarter` to enable interactivity.

## 5. Insights & Business Recommendations
- **Revenue Trends:** The line chart revealed seasonal spikes in revenue, often during Q2 and Q4. These may align with holidays or marketing campaigns.
- **Top Performing Cities:** The bar chart highlighted several cities contributing the highest to overall revenue. These cities can be targeted for promotional efforts or additional partnerships.
- **Seasonality Patterns:** The heatmap showed clear dips in sales in specific months (e.g., January), suggesting slow periods that may benefit from special offers or discounts.
- **Customer Demand:** A consistent relationship between high sales quantity and AOV suggests upselling strategies (e.g., combos) may be working effectively.

## 6. Conclusion
This dashboard enables the Zomato BI team to monitor restaurant sales performance, identify top markets, and optimize operations based on sales seasonality.  
The analysis supports data-driven decision-making for marketing strategies and resource planning.
