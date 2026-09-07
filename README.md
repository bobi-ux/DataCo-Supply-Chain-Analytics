# 📊 DataCo Supply Chain Analytics

> End-to-end Supply Chain Analytics project using Python, Power BI and DAX.

## 🏢 About the Project

This project was developed as part of the **Infosys Springboard Virtual Internship**.

The objective was to transform raw DataCo supply-chain data into a clean, analysis-ready dataset and develop interactive Power BI dashboards for monitoring sales, inventory, delivery performance, regional performance and operational risks.

## 👥 Team Members

* Vaishnavi
* Shreya
* Pujitha
* Siva Reddy
* Imam Khasim

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Power BI
* DAX
* Microsoft Excel

## 📁 Dataset

The project uses the **DataCo Supply Chain** dataset.

### Dataset Overview

* **Rows:** 2,599
* **Columns:** 24
* **Markets:** LATAM, USCA, Pacific Asia, Africa and Europe
* **Data Type:** Order-level supply-chain operational data

The dataset contains information related to orders, products, customers, sales, inventory, shipping and delivery performance.

## 🧹 Data Preprocessing

The raw dataset was processed using Python.

Major preprocessing activities included:

1. Loading and inspecting the dataset
2. Checking dataset dimensions and data types
3. Identifying missing values
4. Handling numerical missing values using median imputation
5. Handling categorical missing values using mode imputation
6. Checking and removing duplicate records
7. Converting order and shipping dates into datetime format
8. Standardizing column names and category labels

The resulting dataset was prepared for further analysis and visualization.

## 📈 Key KPIs

| KPI                   |  Value |
| --------------------- | -----: |
| Total Sales           |  6.13M |
| Total Orders          |     3K |
| Average Delivery Days |   3.95 |
| On-Time Delivery      | 32.13% |
| Total Inventory       |    40K |
| Inventory Value       | 11.65M |

## 📊 Power BI Dashboards

The project contains four interactive dashboards:

### 1. Executive Overview

Provides an overall view of supply-chain performance and management KPIs.

### 2. Warehouse Efficiency

Analyzes orders, shipping efficiency and delivery performance to identify operational bottlenecks.

### 3. Inventory & Product Performance

Provides visibility into inventory, products, sales, quantity and profitability.

### 4. Delivery & Regional Performance

Analyzes delivery reliability across markets, countries, regions and shipping modes.

## 🔎 Analysis Areas

The project analyzes:

* Sales trends
* Order volume
* Delivery performance
* Inventory
* Products
* Categories
* Customer segments
* Regions
* Cities
* Shipping modes
* Late-delivery risk

## 💡 Key Insights

* Sales performance varies across months and quarters.
* Regional analysis highlights differences in sales performance.
* Inventory analysis provides visibility into stock levels and inventory value.
* Average delivery time is approximately **3.95 days**.
* On-time delivery is approximately **32.13%**, highlighting an important area for improvement.
* Shipping-mode and regional analysis can help identify logistics areas requiring operational attention.

## 📂 Project Structure

```text
DataCo-Supply-Chain-Analytics/
│
├── README.md
│
├── Documentation/
│   └── DataCo_Supply_Chain_Project_Report.pdf
│
├── Python/
│   └── data_preprocessing.py
│
├── PowerBI/
│   └── DataCo_Supply_Chain_Dashboard.pbix
│
├── Dataset/
│   └── README.md
│
└── Screenshots/
    ├── executive_overview.png
    ├── warehouse_efficiency.png
    ├── inventory_product.png
    └── delivery_regional.png
```

## 🎯 Business Value

The dashboards provide an interactive decision-support framework for monitoring supply-chain KPIs, identifying performance gaps and prioritizing opportunities for operational improvement.

## 🎓 Internship

**Infosys Springboard Virtual Internship**

**Project:** DataCo Supply Chain Analytics

---

### 📌 Project Theme

**From Data Cleaning to Actionable Supply Chain Insights**

---

⭐ If you find this project useful, feel free to explore the repository.
