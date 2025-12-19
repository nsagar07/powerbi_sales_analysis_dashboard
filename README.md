📊 Sales Performance & Forecasting Dashboard – Power BI Project
Overview
This project features an end-to-end Sales Analytics Power BI Dashboard built using a synthetic business dataset that simulates real-world retail transactions. The dashboard provides insights into revenue performance, product sales trends, customer behavior, and regional distribution, along with forecasting capabilities for strategic decision-making.
The dataset includes 9,000+ sales transactions, 800 customers, and 80 products across multiple regions and channels (Online, Retail, Distributor). It was generated using Python in Jupyter Notebook to ensure realistic data patterns, seasonality, and relationships.
________________________________________
🛠 Tools & Technologies
Category	Tools
Visualization	Power BI Desktop
Data Processing	Python (Pandas, NumPy)📊 Sales Performance & Forecasting Dashboard – Power BI Project
Overview
This project features an end-to-end Sales Analytics Power BI Dashboard built using a synthetic business dataset that simulates real-world retail transactions. The dashboard provides insights into revenue performance, product sales trends, customer behavior, and regional distribution, along with forecasting capabilities for strategic decision-making.
The dataset includes 9,000+ sales transactions, 800 customers, and 80 products across multiple regions and channels (Online, Retail, Distributor). It was generated using Python in Jupyter Notebook to ensure realistic data patterns, seasonality, and relationships.
________________________________________
🛠 Tools & Technologies
Category	Tools
Visualization	Power BI Desktop
Data Processing	Python (Pandas, NumPy)
Storage	CSV Files
Modeling	DAX, Power Query
Versioning	GitHub (optional)
________________________________________
📂 Dataset Structure
Tables
Table	Rows	Description
customers.csv	~800	Customer information, region & preferred sales channel
products.csv	~80	Product catalog with pricing & cost
sales_transactions.csv	~9,000	Transaction facts including revenue, units, date, region & channel
________________________________________
🧠 Key Business Metrics
Metric	Description
Total Revenue	Sum of sales revenue
Gross Profit	Revenue – cost
Average Order Value (AOV)	Revenue ÷ number of orders
Total Units Sold	Sum of product quantities sold
Gross Margin %	Profit % relative to revenue
YoY & MoM growth	Time-based performance trend
Forecasting	Predictive revenue trend using Power BI analytics
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


Storage	CSV Files
Modeling	DAX, Power Query
Versioning	GitHub (optional)
________________________________________
📂 Dataset Structure
Tables
Table	Rows	Description
customers.csv	~800	Customer information, region & preferred sales channel
products.csv	~80	Product catalog with pricing & cost
sales_transactions.csv	~9,000	Transaction facts including revenue, units, date, region & channel
________________________________________
🧠 Key Business Metrics
Metric	Description
Total Revenue	Sum of sales revenue
Gross Profit	Revenue – cost
Average Order Value (AOV)	Revenue ÷ number of orders
Total Units Sold	Sum of product quantities sold
Gross Margin %	Profit % relative to revenue
YoY & MoM growth	Time-based performance trend
Forecasting	Predictive revenue trend using Power BI analytics
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

