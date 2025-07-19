# 📊 Business Optimization Dashboard - Insigh BI

A Power BI dashboard designed to help businesses monitor **product demand**, **availability**, and **financial performance** to reduce supply shortages and increase profitability.

> 🔍 **Objective**: Deliver visual insights into product supply-demand gaps, profitability, and losses to support smarter business decisions.

---

## 🚀 Project Summary

This interactive Power BI dashboard enables stakeholders to:

- Track average demand and availability per product daily
- Monitor **total supply shortages** and **daily loss**
- Evaluate total **profit vs. loss**
- Analyze performance over time using filters (product name & order date)

---

## 📸 Dashboard Pages

### 📄 Page 1: Demand & Availability Overview
## Screenshot 1
![Screenshot 1](https://github.com/kunal1300/Product_Analysis-/blob/837d2b1256ac4871c84634b51925fe38c0287527/Screenshot%202025-07-16%20200552.png)

| Metric | Value | Description |
|--------|-------|-------------|
| **Average Demand per Day** | `3.40` | The mean number of units demanded daily across all products. |
| **Average Availability per Day** | `2.87` | The average daily product availability, which is slightly below demand. |
| **Total Supply Shortage** | `579` | Number of units not fulfilled due to insufficient stock. |

📌 **Key Insight**: There is a supply-demand mismatch leading to shortages. Adjust procurement to meet daily demand.

---

### 📄 Page 2: Profitability Insights
## Screenshot 2
![Screenshot 1](https://github.com/kunal1300/Product_Analysis-/blob/837d2b1256ac4871c84634b51925fe38c0287527/Screenshot%202025-07-16%20200623.png)

| Metric | Value | Description |
|--------|-------|-------------|
| **Total Profit** | `22K` | Aggregated profit made across all products and days. |
| **Total Loss** | `97K` | Accumulated monetary loss, possibly due to unmet demand or operational inefficiencies. |
| **Average Daily Loss** | `88.84` | The average value lost per day. |

📌 **Key Insight**: Losses are substantially higher than profits. Businesses must identify underperforming products or review cost strategies.

---

## 🧠 Filters & Interactivity

- **Order Date** – Filter data by specific days or periods
- **Product Name** – View performance for individual products like:
  - 4K Smart TV
  - Action Camera
  - Air Purifier
  - Bluetooth Speaker, etc.

---

## 📁 Data Model Overview

The dataset includes:

| Column Name         | Description |
|---------------------|-------------|
| `Product_ID`        | Unique identifier for each product |
| `Product_Name`      | Name of the product |
| `Unit_Price`        | Price per unit |
| `Demand`            | Units demanded per day |
| `Availability`      | Units available per day |
| `Total Profit`      | Total profit for the product |
| `Total Loss`        | Total loss associated with the product |
| `Order_Date_DD_MM_YYYY` | Date of transaction |

---

## 📊 Measures Used

| Measure Name | Description |
|--------------|-------------|
| `Average Demand per Day` | Average of daily demand values |
| `Average Availability per Day` | Average of daily stock available |
| `Total Supply Shortage` | Sum of unmet demand (Demand - Availability when positive) |
| `Total Profit` | Aggregate of profits across dates |
| `Total Loss` | Aggregate of losses across dates |
| `Average Daily Loss` | Mean of daily losses |

---

## 🛠️ Tech Stack

- **Power BI** – Data visualization & dashboard development
- **DAX** – Measures and calculated columns
- **Power Query** – Data transformation and filtering
- **SQL Query** - To update the data in table
---

## 💡 Business Use Cases

- Identify **stock-outs** and avoid missed sales
- Optimize **inventory planning**
- Evaluate **profitability vs. loss**
- Enable **product-specific** strategic adjustments

---
📍 Author
Kunal Solanki
📌 Data Analyst | Business Intelligence Specialist
🔗 LinkedIn | 📫 kunalsolanki@email.com

## 📂 Repository Structure

```bash
📁 business-optimization-dashboard
├── README.md
├── images/
│   ├── dashboard-page1.png
│   ├── dashboard-page2.png
└── Business_Optimization.pbix (optional - Power BI file)


