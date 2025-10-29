🛍️ E-Commerce Customer Segmentation & Churn Analysis Dashboard
📊 Project Overview

This project analyzes customer purchasing behavior, identifies churn risk, and uncovers revenue insights for an e-commerce business.
The analysis combines Python (for data cleaning and RFM modeling) with Power BI (for visualization and reporting) to deliver a complete data-driven solution.

🎯 Objectives

Clean and preprocess raw e-commerce transaction data using Python

Perform RFM (Recency, Frequency, Monetary) segmentation to classify customers

Identify active vs churned customers and calculate revenue metrics

Create an interactive Power BI dashboard to visualize performance and trends

🧩 Tools & Technologies

Python: Pandas, NumPy, Matplotlib — for cleaning and analysis

Power BI: Data modeling, DAX measures, and visualization

Excel: Final output format exported from Python

Dataset Source: Kaggle

📂 Folder Structure
E-Commerce-Customer-Segmentation-Churn-Analysis/
│
├── 📁 Raw_Data/
│   └── Online Retail II Dataset (from Kaggle)
│
├── 📁 Cleaned_Data/
│   ├── Ecommerce_Transactions_Clean.xlsx
│   └── Ecommerce_Customer_RFM.xlsx
│
├── 📁 Python_Notebook/
│   └── E-Commerce_Customer_Segmentation.ipynb
│
├── 📁 Power_BI_Dashboard/
│   └── E-Commerce_Customer_Segmentation.pbix
│
└── README.md

📈 Power BI Dashboard KPIs
KPI	Description
Total Customers	Total unique customers in the dataset
Active Customers	Customers who made purchases recently
Churned Customers	Customers who have not purchased recently
Churn Rate (%)	(Churned Customers / Total Customers) × 100
Total Revenue	Overall sales revenue
Active Revenue	Revenue from active customers
Churned Revenue	Revenue lost from churned customers
📊 Visuals Used

KPI Cards (7 total)

Donut Chart: Revenue Share by Status (Active vs Churned)

Line Chart: Monthly Revenue Trend

Bar/Column Chart: Revenue by Country or Segment

Map Visual: Revenue Distribution by Country

🔗 Data Sources

Original Kaggle Dataset:
Online Retail II Dataset (Kaggle)

🔗 https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci

Processed Project Files (Google Drive):
Download Cleaned Data, Notebook & Dashboard

📁 https://drive.google.com/file/d/1gLYaIKTsEV2mJdtO7WSW5C8Ca_rcQ2Wu/view?usp=sharing

⚙️ Steps Performed

Imported raw CSV dataset from Kaggle using Python

Cleaned data — removed nulls, duplicates, and invalid quantities or prices

Created calculated columns such as TotalAmount and InvoiceMonth

Performed RFM analysis to score customers based on purchase behavior

Exported cleaned data as Excel files for Power BI integration

Built Power BI dashboard with custom DAX measures for KPIs

Designed interactive visuals for better business insights

🧠 Insights Gained

Majority of revenue comes from Loyal Customers

Churn Rate indicates potential customer loss areas

Revenue trend shows clear seasonality and peak months

Country-wise analysis reveals top-performing markets

💡 Key Learnings

Practical understanding of RFM segmentation and customer behavior analysis

Integration of Python preprocessing with Power BI visualization

Ability to calculate and visualize business KPIs effectively

👨‍💻 Author

Aadi Chauhan
📅 Project Year: 2025

🖼️ Dashboard Preview

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/90dee94f-070c-4e43-b900-50d4eee89842" />
