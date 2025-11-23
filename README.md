📊 Telco Customer Churn Analytics Project

End-to-End Customer Churn Analysis using Python & Power BI

📁 Project Overview

This project analyzes customer churn for a telecom company using Python (EDA) and a fully interactive Power BI dashboard.
The goal is to understand why customers leave, which customer segments churn more, and highlight business insights to reduce churn.

🎯 Objectives

Identify churn drivers (price, contract type, tenure, services used)

Perform complete Exploratory Data Analysis (EDA)

Build customer segments (tenure group, charges group)

Visualize churn behavior through an interactive Power BI dashboard

Present actionable business insights

🛠️ Tools & Technologies
Task	Tools Used
Data Cleaning	Python (Pandas, NumPy)
Data Visualization	Matplotlib, Seaborn
Dashboard	Power BI
Documentation	GitHub README
Dataset	Telco Customer Churn (IBM Sample Dataset)
📂 Project Structure
Telco-Customer-Churn-Analytics/
│
├── data/
│   └── Telco_customer_churn.xlsx
│
├── python/
│   └── Telco_Churn_EDA.ipynb
│
├── powerbi/
│   └── Telco_Churn_Dashboard.pbix
│
├── images/
│   ├── dashboard.png
│   ├── charts.png
│   └── correlations.png
│
└── README.md

📌 Dataset Information

The dataset contains 7,000+ telecom customer records with features such as:

Customer demographics

Account information

Subscription type

Monthly/Total charges

Internet & Phone service details

Churn label (Yes/No)

🧹 Python EDA Steps
✔ 1. Data Cleaning

Removed duplicates

Converted incorrect data types

Handled blank values in Total Charges

Encoded Yes/No fields to 1/0

✔ 2. Feature Engineering

Created new segmentation features:

Tenure Group

0–12 months

12–24 months

24+ months

Monthly Charges Group

Low (0–30)

Medium (30–60)

High (60+)

✔ 3. Exploratory Data Analysis

Using Python visualizations:

Churn distribution

Charges vs churn

Tenure vs churn

Service type comparison

Correlation heatmap

📊 Power BI Dashboard Overview

<img width="885" height="499" alt="Dashboard Image" src="https://github.com/user-attachments/assets/89407d41-6f6a-4e98-9de0-5fe18ddc34a6" />


The dashboard includes:

📍 KPIs

Total Customers

Total Churned Customers

Churn Rate

Average Monthly Charges

Total Revenue

📍 Visuals

Churn by Payment Method

Churn by Contract Type

Churn vs Tenure Group

Churn vs Charges Group

Churn vs Internet Service Type

Slicers (Churn Label, Contract Type)

🔍 Key Insights

📌 Customers with month-to-month contracts have the highest churn rate.
📌 High monthly charge customers churn more (price sensitivity).
📌 Low tenure customers (0–12 months) churn the most.
📌 Electronic check users show maximum churn.
📌 Fiber optic customers churn more compared to DSL.

These insights suggest that the company should:

Offer discounts for high monthly charge customers

Improve onboarding experience for new customers

Promote yearly contracts with incentives

🚀 How to Use This Project

Download the .ipynb file and run it in Jupyter Notebook/VS Code.

Open the .pbix file in Power BI Desktop to explore the dashboard.

Explore the dataset inside the /data folder.

🧑‍💻 Author

Harshit Rai
Aspiring Data Analyst

⭐ If you found this project helpful, don't forget to star the repository!
