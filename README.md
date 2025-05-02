# Beauty & Cosmetics Sales Performance and Analytics Dashboard

## Description
This project showcases a comprehensive Power BI analysis of beauty and cosmetics sales performance across various dimensions, including customer behavior, supplier performance, and regional trends. The dataset used in this project is **simulated and fictitious**, crafted to reflect real-world brands, products, and categories for illustrative and educational purposes. A key component of this project was the creation and optimization of a dynamic data model within Power BI, leveraging relational database concepts such as primary and foreign keys to establish meaningful relationships between tables. The project highlights advanced data transformation, interactive visualizations, and actionable insights tailored to decision-making in the beauty industry.

## Tools, Techniques, and Analytical Logic Used

- **Power BI**: Developed the full dashboard using custom visuals, slicers, tooltip layers, DAX-based cards, and interactive filters.
- **SQL (SSMS)**: Used for structuring tables, creating customer spend metrics, and prepping the dataset for import.
- **Excel**: Used for ETL cleanup, category grouping logic, and modeling `Customer Segmentation by Tier`.
- **ETL Workflow**: Structured raw data across products, orders, suppliers, and customers for seamless relational modeling.
- **Data Model Relationships**: Connected dimension and fact tables through one-to-many relationships across orders, customers, inventory, and suppliers.
- **Customer Segmentation Table**: Created to segment by spend tiers (High, Medium, Low); used to power visual filters and insights.
- **Customer Spend Behavior Analysis**: Built using `Total Order Value`, `Average Order Value`, and purchase frequency logic.
- **Price Tiering Analysis**: Compared pricing bands across prestige and drugstore brands for pricing strategy modeling.
- **Inventory & Supplier Dependency Metrics**: Visualized inventory concentration and supplier contributions to model risk exposure.


## Key Features
- **Comprehensive Sales Analysis**: Insights into customer behavior, product performance, and revenue trends.
- **Interactive Visualizations**: Dashboards with slicers, filters, and drill-down capabilities.
- **Regional Performance Insights**: Geographical analysis of sales distribution.
- **Product & Supplier Analysis**: Understanding brand performance, category-level trends, and supplier contributions.

## 📊 Interactive Power BI Dashboard  

[📎 View the Full Strategic Business Intelligence Report (PDF)](./Beauty_Cosmetics_PowerBI_Report/Beauty_Cosmetics_Sales_Performance_Analysis_Report.pdf)

This interactive Power BI report provides insights into beauty and cosmetics sales trends, customer segmentation, supplier performance, and inventory insights.

## Screenshots

![Customer Insights Dashboard](customer_insights_dashboard.png)  
*Customer Insights Dashboard - Focused on Customers*

![Average Price by Category Groups](average_price_by_category_groups.png)  
*Average Price by Category Groups - Focused on Price Segmentation*

![Product Insights Visualization](product_insights_visualization.png)  
*Product Insights - Focused on Products; groups and categories*

## Future Enhancements
This project is part of a broader portfolio. Future phases will include:
- **Tableau**: Advanced visualizations and dashboards with the same dataset for comparative insights.
- **R Programming**: Statistical analysis and visualization of larger beauty industry datasets.
- **Expanded Dataset Analysis**: Incorporating additional months and product categories to provide deeper insights into trends and performance.

## How to Use
- Clone this repository to your local system.
- Open the Power BI file to explore the visualizations and insights.

## Disclaimer
The dataset used in this project is entirely **simulated and fictitious**. While the dataset is inspired by real-world brands, products, and categories, it was fabricated solely for the purpose of demonstrating data analysis and business intelligence skills. Any resemblance to actual sales data or business performance is purely coincidental.
