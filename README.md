# Sales_DashBoard_PowerBI
Analysed a dataset of sales transactions to identify trends, patterns, and key insights using MySQL and PowerBI to optimize business decision-making by data visualization and dashboards.
Sales Analysis Dashboard in Power BI
Project Overview
The Sales Analysis Dashboard is designed to analyze sales performance across various dimensions such as time, product categories, regions, and customer demographics. It helps stakeholders gain actionable insights into revenue trends, customer preferences, and profitability.

This dashboard was developed as part of a data visualization project to demonstrate the power of interactive and dynamic reporting using Power BI.

Key Features
Dynamic Visualizations:

Sales trends over time with year-over-year comparisons.
Region-wise performance and product category distribution.
KPIs and Metrics:

Total Sales: Summarized revenue generated.
Profit Margins: Gross profit percentage calculation.
Top Performing Products: Identifies high-performing products.
Filters and Drill-Down:

Interactive filters for regions, product categories, and time ranges.
Drill-down options for exploring data hierarchies (e.g., year → quarter → month).
Insights:

Identifies areas for improvement, such as low-performing products or regions.
Tracks seasonal trends and customer purchase behavior.
Technologies Used
Power BI Desktop: For building visualizations and creating the dashboard.
Power Query: To clean and transform raw data.
DAX (Data Analysis Expressions): For creating calculated measures and custom logic.
Dataset
Sources
The dashboard leverages three key datasets:

Sales Data:
Fields: Order ID, Product ID, Quantity, Sales Amount, and Date.
Purpose: To analyze total sales and trends.
Customer Data:
Fields: Customer ID, Region, Age Group, and Gender.
Purpose: For demographic analysis.
Product Data:
Fields: Product ID, Category, Subcategory, and Price.
Purpose: To link sales data with product details.
Installation and Usage
Prerequisites
Install Power BI Desktop (Version 2023 or later is recommended).
Steps to Get Started
Clone or download the repository:
bash
Copy code
git clone https://github.com/shivammishra9911/Sales-Analysis-Dashboard.git
Open the .pbix file using Power BI Desktop.
Navigate through the report pages:
Overview: High-level summary of sales.
Detailed Analysis: In-depth breakdown of sales by region, time, and product.
Use slicers and filters to interact with the data and generate insights.![Screenshot 2025-01-09 234534](https://github.com/user-attachments/assets/e37af52b-aea4-405a-be16-284387870ce2)
![Screenshot 2025-01-09 234605](https://github.com/user-attachments/assets/f41cf092-13cf-40e1-92fb-db20d2693ff8)
![Screenshot 2025-01-09 234647](https://github.com/user-attachments/assets/ab29ef09-0d2a-4e55-83a6-1fe27f02d609)
![Screenshot 2025-01-09 234839](https://github.com/user-attachments/assets/c644dd55-345f-4a66-958c-50ccfd9f4163)
How It Works
Data Transformation:

Duplicates and null values were removed.
Fields were renamed for clarity.
Relationships between datasets were defined in the Power BI model.
DAX Formulas:

Total Sales: SUM(Sales[Amount])
Profit Margin: (SUM(Sales[Profit]) / SUM(Sales[Amount])) * 100
Visualizations:

Line graphs for time trends.
Bar charts for categorical comparisons.
Map visuals for geographic analysis.
Future Enhancements
Integrate real-time data sources via APIs or live connections.
Add predictive analytics using Power BI's AI insights.
Expand the analysis to include marketing and customer acquisition costs.
License
This project is open-source and licensed under the MIT License. You are free to use, modify, and distribute it with proper attribution.

Contributing
Contributions are welcome! Feel free to open issues or submit pull requests. For major changes, please discuss your ideas in advance.

Contact
Name: Shivam Mishra

