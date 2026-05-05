📊 Sales Analytics Dashboard (Power BI Project)
📌 Project Overview

This project is an end-to-end Sales Analytics Dashboard built using Power BI, designed to analyze business performance across products, customers, employees, regions, and time periods.

It provides insights into:

Total Sales & Profitability
Product Performance
Customer Analysis
Time-based Sales Trends
Regional Performance (City / Country)
Employee-related sales contribution
📁 Dataset Description

The project uses a relational dataset consisting of multiple CSV files:

customers.csv – Customer details
employees.csv – Employee information
offices.csv – Office location data
orderdetails.csv – Order line-level details
orders.csv – Order transactions
payments.csv – Payment records
productline.csv – Product category information
products.csv – Product details
🔄 Data Cleaning & Transformation

All data preprocessing was done using Power Query Editor, including:

Removal of duplicate records
Handling missing (null) values
Fixing inconsistent data types and errors
Standardizing column formats
Creating relationships between tables
🧹 Key Transformations:
Created Full Name column for customers by combining first and last name
Extracted Month Name and Month Number from Order Date
Structured data into a proper star schema model
🧠 Data Modeling

A proper relationship model was built between tables:

Orders → OrderDetails → Products
Customers → Orders
Employees → Offices

This enabled efficient filtering and aggregation across the dashboard.

🧮 DAX Measures & Calculations

Several important measures and calculated columns were created:

📌 Core Metrics:
Total Sales
Total Profit
Profit Margin %
Quantity Ordered
📌 Sales Logic:
Sales was calculated using order-level computations (Quantity × Price Each)
Profit was calculated using:
Sales − Buy Price impact from product cost
📌 Profit Margin:
Profit Margin % = DIVIDE([Total Profit], [Total Sales])
📌 Time Intelligence Measures:
Sales by Year (2003, 2004, 2005)
Sales by Month
Monthly trend analysis using Order Date
📊 Dashboard Features

The Power BI report includes three main views:

🟢 1. Main Dashboard (Overview)
Total Sales
Total Profit
Profit Margin %
Top Products
Key KPI cards
Regional and product performance overview
🔵 2. Detailed Analysis View
Sales by Product Line
Quantity Ordered by Product Line
Sales by Product Name
Quantity Ordered by Product Name
Year-wise Sales Trends
🟣 3. Tooltip View
Interactive tooltip showing:
Sales by Product Name (Bar Chart)
Provides quick insights on hover
📈 Key Insights
Identified top-performing product lines
Analyzed seasonal sales trends
Found highest revenue-generating products
Compared profitability across product categories
Evaluated regional sales performance
🛠 Tools & Technologies Used
Power BI Desktop
Power Query (Data Cleaning & Transformation)
DAX (Data Analysis Expressions)
Excel / CSV datasets
🚀 Project Outcome

This dashboard helps businesses:

Track sales performance in real-time
Identify top products and regions
Improve decision-making using data-driven insights
Understand profitability at a granular level
📷 Screenshots
01_Sales_Overview_Dashboard.png
02_Sales_Detailed_View.png
03_Sales_Tooltip_View.png
📌 Author

DHARSHINI M R
Aspiring Data Analyst | Power BI | SQL | Data Visualization

⭐ If you like this project

Feel free to ⭐ the repository and explore more projects!