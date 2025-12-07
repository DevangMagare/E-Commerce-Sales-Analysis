# E-Commerce-Sales-Analysis
📘 E-Commerce Sales Analysis — End-to-End Data Analytics Project

Python • Power BI • Data Cleaning • Exploratory Data Analysis • Dashboard Development

🔍 Project Overview

This project provides a complete end-to-end analysis of an e-commerce dataset using Python for data cleaning & analysis and Power BI for dashboard development.

The objective of this project is to understand business performance across:

Financial Performance

Customer Insights

Logistics & Fulfillment Efficiency

Product Management & Inventory Optimization

Customer Satisfaction & Returns

The project converts raw transactional data into actionable business insights to support data-driven decisions.


🛠️ Technologies Used

Python (Pandas, NumPy, Matplotlib)

Power BI Desktop

Jupyter Notebook / Colab

DAX Measures

Data Visualization Concepts

🧹 1. Data Cleaning & Preparation (Python)

Key cleaning steps performed:

✔ Column name standardization

Converted all column names to lowercase and snake_case for consistency.

✔ Handling missing values

Amount column → replaced missing values with median

Text fields → filled with "Unknown"

✔ Date formatting

Converted date column to datetime & extracted month for trend analysis.

✔ Cancelled orders

Set amount = 0 only where status == 'cancelled'.

✔ Fulfilment type standardization

Created fulfilment_type column for Amazon vs Merchant comparison.

📊 2. Exploratory Data Analysis (Python)
Key analyses performed:

Revenue trends

City-wise and state-wise sales performance

Cancellation & return patterns

B2B vs B2C comparison

High-demand product categories

Inventory planning recommendations

Logistics performance (shipping times, fulfilment efficiency)

All results are printed clearly within the notebook.

📈 3. Power BI Dashboard

A fully designed, interactive Power BI dashboard was created with:

Key KPIs

Total Revenue

Total Orders

Average Order Value (AOV)

Total Quantity Sold

Cancellation Rate

Dashboard Visuals

Revenue by City (Top 10)

Category-wise Revenue

Amazon vs Merchant Fulfillment

Weekly Sales Trend

Monthly Revenue Trend

Returns & Cancellations Overview

Inventory Demand Levels

Filters Included

Month-Year

Category

Ship-State

The dashboard uses a bright professional theme, clean layout, and business-focused insights.

📌 4. Key Insights
🔹 Financial Performance

Strong overall revenue with consistent monthly trends.

High contribution from top cities like Bengaluru, Hyderabad, and Mumbai.

🔹 Customer Insights

Customer retention strongest in metro cities.

Cancellation rate around 14%, influenced by fulfilment and courier performance.

🔹 Fulfillment & Logistics

Amazon Easy Ship showed faster shipping times compared to Merchant fulfilment.

Around 89% of non-cancelled orders were processed on time.

🔹 Product & Inventory

High-demand categories: Set and Kurta

Recommended to maintain higher safety stock for high-demand categories.

Low-demand items should be replenished carefully to avoid overstocking.

🧾 5. Recommendations

Strengthen fulfilment operations to reduce cancellation rates.

Improve forecasting accuracy for high-demand products.

Expand operations in top-performing cities.

Optimize weekday staffing based on weekly sales patterns.

Enhance customer service touchpoints to reduce returns.


📂 Repository Contents
/python-analysis
    - Notebook & .py file
    - Cleaned dataset

/powerbi-dashboard
    - PBIX dashboard
    - Dashboard screenshots

/presentation
    - Final PPT used for presentation


    📝 6. How to Use This Project
To run the Python analysis

Install required libraries

Open the .ipynb or .py file

Load the dataset

Run all cells to generate insights

To view the Power BI dashboard

Download the .pbix file

Open using Power BI Desktop


🙋‍♂️ Author

Devang Magare
Data Analyst | Python | SQL | Power BI | Dashboard Development
