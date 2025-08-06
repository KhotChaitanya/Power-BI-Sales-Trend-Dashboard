# Power BI Sales Trend Dashboard

An interactive sales trend dashboard built with Microsoft Power BI to analyze global retail data, focusing on weekly sales, top products, and regional performance.

## Overview

This project provides a comprehensive business intelligence solution for analyzing retail sales data. Utilizing the "Global Superstore" dataset, this dashboard, built entirely in Microsoft Power BI, transforms over 50,000 records into actionable insights. The system is designed for stakeholders to monitor key performance indicators (KPIs), identify trends, and perform deep-dive analyses with ease. The final dashboard is a powerful tool for data-driven decision-making, featuring a clean layout, interactive filtering, and a suite of insightful visualizations.

## Technologies Used

* **Microsoft Power BI**
* **DAX (Data Analysis Expressions):** For creating custom measures and calculations.
* **Power Query (M Language):** For data cleaning, transformation, and preparation (ETL).

## Features

* **Interactive KPI Cards:** At-a-glance metrics for Total Sales, Total Profit, Profit Margin, and Total Orders.
* **Dynamic Slicers:** User-friendly dropdown filters for Year, Month, and Market, allowing for granular deep-dive analysis.
* **Weekly Sales Analysis:** A line chart that dynamically displays sales trends for the weeks within a selected month and year.
* **Top N Product Analysis:** A bar chart that automatically identifies and displays the top 10 best-selling products by revenue.
* **Geographical Performance Mapping:** An interactive map that visualizes sales volume by country (bubble size) and profitability (conditional color formatting).
* **Sales Composition Breakdown:** A donut chart that clearly shows the proportion of sales contributed by each product category.
* **Professional Design:** A clean, grid-based layout with a consistent color scheme, shadows, and aligned visuals for a polished user experience.
* **Enhanced Tooltips:** Custom tooltips on charts provide additional layers of data without cluttering the main view.

## Methodology & Pipeline

The project follows a structured business intelligence workflow:

1.  **Data Loading & Transformation (ETL):** The "Global Superstore" dataset was loaded into Power BI. In the Power Query Editor, data types were verified, columns were renamed, and the data was cleaned to ensure quality.
2.  **Data Modeling:** A robust data model was created by establishing a relationship between the main sales table and a custom-built **Calendar Table**. This DAX-generated table is the foundation for all time-based analysis.
3.  **DAX Measures:** Core business calculations like `Total Sales`, `Total Profit`, and `Profit Margin` were created as reusable DAX measures. A dynamic title measure was also developed for the weekly sales chart.
4.  **Dashboard Development:** Visuals were added to the canvas and populated with the appropriate data fields and measures.
5.  **Formatting & Design:** A consistent theme, color palette, and layout grid were applied. Each visual was individually formatted with titles, shadows, and backgrounds to create a professional "card" layout.
6.  **Interactivity:** Slicers and Power BI's native cross-filtering capabilities were leveraged to create a fully interactive user experience.

## Output

### Unfiltered Dashboard View
<img width="1838" height="1060" alt="MD" src="https://github.com/user-attachments/assets/a0a70c9a-3794-4eac-867a-c9b15169b73d" />

*(This is the main dashboard, providing a high-level overview of global sales performance across all time.)*

### Filtered Dashboard View
<img width="1837" height="1046" alt="DF" src="https://github.com/user-attachments/assets/c93fc190-7f73-44f2-a69d-069909ef0851" />

*(This view demonstrates the dashboard's interactivity, showing a deep-dive analysis for the European market in May 2012.)*

## Dataset

The dataset used for this project can be downloaded from the following Kaggle link:

* **Global Superstore Dataset:** [https://www.kaggle.com/](https://www.kaggle.com/)

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
