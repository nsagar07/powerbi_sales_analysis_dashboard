# 📊 Sales Performance & Forecasting Dashboard – Power BI

---

## 🧾 Overview

This project features an end-to-end **Sales Analytics Power BI Dashboard** built using a **synthetic business dataset** that simulates real-world retail transactions. The dashboard provides insights into **revenue performance**, **product sales trends**, **customer behavior**, and **regional distribution**, along with **forecasting capabilities** for strategic decision-making.

The dataset includes **9,000+ sales transactions**, **800 customers**, and **80 products** across multiple regions and sales channels (Online, Retail, Distributor). The data was generated using **Python in Jupyter Notebook** to ensure realistic patterns, seasonality, and proper relational structure.

---

## 🛠 Tools & Technologies

| Category | Tools |
|---------|-------|
| Visualization | Power BI Desktop |
| Data Processing | Python (Pandas, NumPy) |
| Storage | CSV Files |
| Modeling | Power Query, DAX |
| Version Control | GitHub |

---

## 📂 Dataset Structure

### Tables

| Table | Rows | Description |
|-------|-------|-------------|
| customers.csv | ~800 | Customer information including region and preferred channel |
| products.csv | ~80 | Product catalog with pricing and cost |
| sales_transactions.csv | ~9,000 | Transaction-level sales data including revenue, units, date, region, and channel |

---

## 🧠 Key Business Metrics

| Metric | Description |
|--------|-------------|
| Total Revenue | Sum of all sales revenue |
| Gross Profit | Revenue minus total product cost |
| Average Order Value (AOV) | Revenue divided by number of transactions |
| Total Units Sold | Sum of all units sold |
| Gross Margin % | Profit as a percentage of revenue |
| MoM Growth | Month-over-month revenue change |
| YoY Growth | Year-over-year revenue change |
| Forecasting | Revenue trend prediction using Power BI analytics |

---

## 📈 Dashboard Features

| Feature | Description |
|--------|-------------|
| Executive KPI Overview | High-level KPIs with interactive slicers |
| Revenue Trend Analysis | Monthly revenue trend with 6-month forecast |
| Regional Performance | Sales distribution across regions |
| Channel Analysis | Comparison of Online, Retail, and Distributor channels |
| Product Performance | Top and bottom performing products |
| Interactive Filtering | Cross-filtering and drill-down functionality |

---

## 🔗 Data Model (Star Schema)


________________________________________
🛠 Tools & Technologies
| Category        | Tools                  |
| --------------- | ---------------------- |
| Visualization   | Power BI Desktop       |
| Data Processing | Python (Pandas, NumPy) |
| Storage         | CSV Files              |
| Modeling        | DAX, Power Query       |
| Version Control | GitHub                 |

________________________________________
📂 Dataset Structure
| Table | Rows | Description |
|-------|-------|-------------|
| customers.csv | ~800 | Customer information, region & channel preference |
| products.csv | ~80 | Product catalog with pricing & cost |
| sales_transactions.csv | ~9,000 | Transaction facts including revenue, units, date, region & channel |
________________________________________

🧠 Key Business Metrics

| Metric                    | Description                                      |
| ------------------------- | ------------------------------------------------ |
| Total Revenue             | Sum of all sales revenue                         |
| Gross Profit              | Revenue minus product cost                       |
| Average Order Value (AOV) | Revenue divided by number of transactions        |
| Total Units Sold          | Sum of product quantities sold                   |
| Gross Margin %            | Profit as a percentage of revenue                |
| MoM Growth                | Month-over-month revenue change                  |
| YoY Growth                | Year-over-year revenue change                    |
| Forecasting               | Predicted revenue trend using Power BI analytics |

________________________________________

📈 Dashboard Features
•	📍 Executive KPI Overview with slicers
•	📆 Revenue trend with 6-month forecasting
•	🌍 Sales by Region and by Channel
•	🎯 Top-selling Products
•	👥 Customer channel insights
•	🧮 DAX calculations for KPIs
•	📊 Interactive drill-through & filtering
________________________________________

🔗 Data Model (Star Schema)
   Customers        Products
        \              /
         \            /
          \          /
      Sales_Transactions  (Fact Table)
________________________________________

📌 DAX Measures (Examples)
Total Revenue = SUM('sales_transactions'[Revenue])
Total Units = SUM('sales_transactions'[Units])
AOV = DIVIDE([Total Revenue], DISTINCTCOUNT('sales_transactions'[TransactionID]), 0)
Gross Profit = [Total Revenue] - SUMX('sales_transactions', RELATED(products[Cost]) * 'sales_transactions'[Units])
________________________________________

🚀 Outcome
This project demonstrates the ability to:
•	Design and build interactive dashboards
•	Work with relational datasets and star-schema modeling
•	Analyze business performance and extract actionable insights
•	Apply forecasting and analytics techniques
•	Transform raw data into clear business recommendations
________________________________________

📦 How to Use
1.	Download all dataset CSV files
2.	Open Power BI Desktop
3.	Load files via Home → Get Data → Text/CSV
4.	Build relationships in Model View
5.	Add DAX & visualizations
________________________________________

📍 Future Enhancements
•	Customer segmentation & CLTV modeling
•	Inventory optimization dashboard
•	RFM scoring
•	Integration with SQL database backend
________________________________________

🧑‍💻 Author
Nimmy Sagar
Data Analyst | SQL | Power BI | Python
📍 Frankfurt, Germany
📧 nimmy.sagar83@gmail.com
________________________________________

🎉 Thank You!
Feel free to connect or share feedback.
⭐ If this project helped you, please give it a star on GitHub!

