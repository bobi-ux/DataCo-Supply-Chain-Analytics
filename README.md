# 📊 DataCo Supply Chain Analytics

An interactive **Supply Chain Analytics and Business Intelligence project** using Python, Pandas, NumPy, and Power BI to analyze sales, orders, inventory, delivery performance, products, categories, regions, and shipping efficiency.

> **Project Theme:** From Data Cleaning to Actionable Supply Chain Insights

---

## 📌 Project Overview

This project analyzes the **DataCo Supply Chain dataset** and transforms raw operational data into meaningful business insights.

The project follows a complete data-to-decision workflow:

**Raw Data → Data Cleaning → Data Analysis → KPI Development → Power BI Dashboards → Business Insights**

The dataset contains **2,599 records and 24 columns**, covering sales, orders, products, inventory, customers, shipping, delivery status, and geographic information across five global markets.

---

## 🎯 Objectives

* Understand the structure and characteristics of the dataset
* Identify and handle missing values
* Check and remove duplicate records
* Standardize column names and category labels
* Convert date columns into proper datetime format
* Analyze sales and order performance
* Analyze delivery and shipping performance
* Analyze inventory and product performance
* Compare regional and market performance
* Create interactive Power BI dashboards
* Generate actionable supply-chain insights

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Power BI**
* **Microsoft Excel**
* **CSV**

---

## 🧹 Data Preprocessing

The raw dataset was cleaned using Python.

### Main preprocessing steps:

1. **Data Loading & Inspection**

   * Loaded the Excel dataset using Pandas
   * Checked dataset shape, columns, and data types

2. **Missing Value Treatment**

   * Numerical missing values → **Median imputation**
   * Categorical missing values → **Mode imputation**

3. **Duplicate Checking**

   * Checked for duplicate records
   * Prepared a clean dataset without exact duplicate rows

4. **Date Conversion**

   * Converted `Order Date` and `Shipping Date` into datetime format

5. **Standardization**

   * Standardized column names
   * Corrected inconsistent category labels

These preprocessing steps produced a clean and analysis-ready dataset.

---

## 📈 Key KPIs

| KPI                               |      Value |
| --------------------------------- | ---------: |
| 💰 Total Sales                    |      6.13M |
| 📦 Total Orders                   |         3K |
| 💵 Total Profit                   |    220.13K |
| 🚚 Average Shipping/Delivery Days |       3.95 |
| ✅ On-Time Delivery                |     32.13% |
| ⚠️ Late Delivery Rate             |     ~41.7% |
| 📦 Total Inventory                | ~40K units |
| 💎 Inventory Value                |     11.65M |

The project identifies **delivery reliability as a major area for improvement**, with on-time delivery at approximately 32.13% and late deliveries at approximately 41.7%.

---

## 📊 Power BI Dashboards

The project contains **four interactive Power BI dashboards**.

### 1️⃣ Executive Overview

Provides a high-level view of:

* Total Sales
* Total Orders
* Total Profit
* Average Shipping Days
* Market performance
* Regional performance

📷 Screenshot: `Screenshots/Dashboard_Overview.png`

---

### 2️⃣ Warehouse Efficiency

Focuses on:

* Order volume
* Shipping efficiency
* Average shipping days
* Delivery status
* Late delivery rate
* Shipping modes
* Market performance

📷 Screenshot: `Screenshots/Supplier_Scoreboard.png`

---

### 3️⃣ Inventory & Product Performance

Analyzes:

* Product performance
* Inventory levels
* Category sales
* Product quantity
* Profitability
* Customer cities

📷 Screenshot: `Screenshots/Transportation_Cost.png`

---

### 4️⃣ Delivery & Regional Performance

Focuses on:

* Late delivery rate
* On-time delivery
* Average delivery days
* Regional performance
* Country performance
* Shipping modes
* Delivery risk

📷 Screenshot: `Screenshots/Route_Carrier_Performance.png`

---

## 🔍 Key Business Insights

### 💰 Sales Performance

The dataset contains approximately **6.13M in total sales** and **3K orders**, providing an overview of the commercial scale of the business.

### 🌍 Regional Performance

The **South region is the strongest displayed region by sales**, while other regions show differences in sales and delivery performance.

### 🚚 Delivery Performance

Average delivery/shipping time is approximately **3.95 days**, while on-time delivery is only around **32.13%**. This indicates that delivery reliability requires attention.

### 📦 Inventory

The project identifies approximately **40K inventory units** with an inventory value of approximately **11.65M**, showing the importance of effective inventory monitoring.

### ⚠️ Delivery Risk

Approximately **1.08K records** are associated with late-delivery risk. Risk can be investigated using region, customer segment, and shipping mode.

---

## 📁 Project Structure

```text
📁 DataCo-Supply-Chain-Analytics
│
├── 📄 README.md
│
├── 📁 Documentation
│   ├── 📄 DataCo_Supply_Chain_Project_Report.pdf
│   └── 📄 DataCo_Dataset.csv
│
├── 📁 PowerBI
│   └── 📊 DataCo_Supply_Chain_Dashboard.pbix
│
└── 📁 Screenshots
    ├── 📊 Dashboard_Overview.png
    ├── 📊 Supplier_Scoreboard.png
    ├── 📊 Transportation_Cost.png
    └── 📊 Route_Carrier_Performance.png
```

---

## 💡 Recommendations

Based on the analysis:

* Monitor late deliveries regularly
* Compare actual shipping days with scheduled shipping days
* Analyze delivery performance by shipping mode
* Monitor high-risk regions and customer segments
* Review inventory together with product sales
* Prioritize products requiring closer inventory monitoring
* Use Power BI dashboards for regular performance monitoring
* Investigate specific country → department → shipping mode → delivery status combinations

The recommendations are focused on operational improvement and monitoring.

---

## ⚠️ Limitations

* The dataset does not contain a direct transportation-cost field.
* The project is focused on descriptive analytics and dashboard-based decision support.
* Predictive analytics and machine learning are not included as completed capabilities.
* Carrier-level performance cannot be accurately claimed because the source data does not establish a carrier-performance field.
* Dashboard insights depend on the selected filters and dimensions.

---

## 🚀 Future Scope

Future improvements could include:

* Predictive delivery-risk modeling
* Demand forecasting
* Inventory forecasting
* Anomaly detection
* Route optimization
* Real-time dashboard integration
* Transportation-cost data integration
* Carrier-level performance analysis

These are proposed future enhancements and are not part of the completed project.

---

## 👩‍💻 Project Team

**Infosys Springboard Virtual Internship**

* Vaishnavi
* Shreya
* Pujitha
* Siva Reddy
* Imam Khasim

---

## 📌 Conclusion

The **DataCo Supply Chain Analytics** project transforms raw supply-chain records into an interactive business-intelligence solution.

Using **Python, Pandas, NumPy, and Power BI**, the project provides insights into sales, orders, inventory, products, delivery performance, shipping modes, regions, and operational risk.

The main business takeaway is the need to **improve delivery reliability while continuously monitoring inventory and regional performance**.

> **From Data Cleaning to Actionable Supply Chain Insights.**
