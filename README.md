# 📊 Interactive Sales Dashboard in Excel (Pivot Table + Slicers)

An interactive Excel dashboard that summarizes customer purchase data by city and product using a PivotTable, a linked PivotChart, and slicers for one-click filtering

### 🎯 Project Objective

Turn a raw customer transaction sheet into a clean, interactive report that answers questions such as:

Which cities generate the most revenue?
How does revenue change when I filter by product category?
What is the overall sales total at a glance?
🗂️ Dataset

Sheet: sample in sample_report.xlsx (30 customer records)

Column	Description
Customer ID	Unique customer identifier (C001–C030)
Customer Name	Name of the customer
Age	Customer age
City	Customer city (13 cities across India)
Phone	Contact number
Join Date	Date the customer joined (2024)
Product	Product purchased (Laptop, Mouse, Monitor, Desktop, Headphone, etc.)
Amount	Purchase amount in ₹
Data quality observations

The raw data contains typical real-world issues worth cleaning before analysis:

Duplicate records (e.g., repeated customers with identical details)
Inconsistent phone number formats (spaces, wrong digit counts) and a missing phone number
A missing value in Age
Stray whitespace in an unlabeled trailing column
🛠️ What's Inside the Dashboard
Component	Purpose
PivotTable	Aggregates Sum of Amount by City, with a Grand Total
PivotChart	3D column chart, Sum of Amount by City, linked to the pivot
Slicer – City	Filter the report by one or more cities
Slicer – Product	Filter the report by one or more products

Both slicers are connected to the PivotTable and chart, so selecting a value updates the whole report instantly.

📈 Key Insights
Delhi is the top-performing city by a wide margin (~₹1.84 lakh).
Jaipur is second (~₹1.37 lakh), followed by Noida, Pune, Patna, and Lucknow.
Mumbai and Bangalore contribute the least in this sample.
The overall Grand Total is ₹7,70,550.

Delhi's lead is partly because it has the most customer records in the dataset (12 of 30), so this reflects a small sample rather than market-wide conclusions.

🧰 Tools & Skills Used
Microsoft Excel: PivotTables, PivotCharts, Slicers
Data cleaning and data validation
Data aggregation and summarization
Dashboard design and visualization


📍 Pune, India 🔗 LinkedIn · GitHub

⭐ If you found this project useful, consider giving it a star!
