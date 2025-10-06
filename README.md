# 📊 Tableau-Sales-and-Customers-Project

## 🧭 Introduction
This user story outlines the specifications for building **two Tableau dashboards** designed to help stakeholders — including sales managers and executives — analyze **sales performance** and **customer behavior**.

---

## 🚀 Dashboards Access
> 🔗 **View on Tableau Public:**  
> 🟢 [sales_and_customer_dashboard.twbx](/dashboard/sales_and_customers_dashboard.twbx)  
> 🔵 [Link](https://public.tableau.com/views/SalesCustomersDashboard_17597098655090/SalesDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 💼 Sales Dashboard | Requirements

### 🎯 Dashboard Purpose
The purpose of the **Sales Dashboard** is to present an overview of the key sales metrics and trends to analyze **year-over-year (YoY) sales performance** and understand **sales trends**.

---

### 🧩 Key Requirements

#### 🟢 KPI Overview
- Display a summary of:
  - **Total Sales**
   <p align="left">
  <img src="/docs/sales_kpi.png" alt="sales_kpi.png" width="350"/>
  </p>

  - **Total Profit**
  <p align="left">
  <img src="/docs/profit_kpi.png" alt="profit_kpi.png" width="350"/>
  </p>
  
  - **Total Quantity**
   <p align="left">
  <img src="/docs/quantity_kpi.png" alt="quantity_kpi.png" width="350"/>
  </p>
  
  - #### 🟢 KPI Overview
- Display a summary of:
  
  for both **the current year** and **the previous year**.

---

#### 📈 Sales Trends
- Present the data for each KPI **on a monthly basis** for both the current and previous year.  
- Identify **months with the highest and lowest sales** and make them easy to recognize (e.g., color highlights or annotations).

---

#### 🧮 Product Subcategory Comparison
- Compare **sales performance** by **different product subcategories** for both years.  
- Include a **comparison of sales and profit** side by side.
  <p align="left">
  <img src="/docs/product_subcategory_comparison.png" alt="/docs/product_subcategory_comparison.png" width="500"/>
  </p>
---

#### 📅 Weekly Trends for Sales & Profit
- Present **weekly sales and profit data** for the current year.  
- Display the **average weekly values** as a reference line or benchmark.  
- **Highlight weeks above and below average** to draw attention to performance variations.
  <p align="left">
  <img src="/docs/weekly_trend_for_sales_and_profit.png" alt="weekly_trend_for_sales_and_profit.png" width="500"/>
  </p>
  
---

## 👥 Customer Dashboard | Requirements

### 🎯 Dashboard Purpose
The **Customer Dashboard** aims to provide an overview of **customer data, trends, and behaviors**, helping marketing teams and management understand customer segments and improve satisfaction.

---

### 🧩 Key Requirements

#### 🟢 KPI Overview
- Display a summary of:
  - **Total Number of Customers**
     <p align="left">
  <img src="/docs/customers_kpi.png" alt="customers_kpi.png" width="350"/>
  </p>
  
  - **Total Sales per Customer**
     <p align="left">
  <img src="/docs/sales_per_customer_kpi.png" alt="sales_per_customer_kpi.png" width="350"/>
  </p>
  
  - **Total Number of Orders**
     <p align="left">
  <img src="/docs/orders_kpi.png" alt="orders_kpi.png" width="350"/>
  </p>
  
  for **the current year** and **the previous year**.

---

#### 📈 Customer Trends
- Present the data for each KPI **on a monthly basis** for both the current and previous year.  
- Identify **months with highest and lowest sales** and make them easy to recognize.

---

#### 📊 Customer Distribution by Number of Orders
- Represent the **distribution of customers** based on the **number of orders** they have placed.  
- Provide insights into **customer behavior, loyalty, and engagement**.
 <p align="left">
  <img src="/docs/customers_distribution_by_number_of_orders.png" alt="customers_distribution_by_number_of_orders.png" width="500"/>
  </p>
  
---

#### 🏆 Top 10 Customers by Profit
- Present the **top 10 customers** who have generated the highest profits for the company.  
- Include additional details such as:
  - Rank  
  - Number of Orders  
  - Current Sales  
  - Current Profit  
  - Last Order Date  
 <p align="left">
  <img src="/docs/top_10_customer_by_profit.png" alt="top_10_customer_by_profit.png" width="500"/>
  </p>
  
---

## 🎨 Design & Interactivity Requirements

### ⚙️ Dashboard Dynamics
- Allow users to check **historical data** by selecting **any desired year**.  
- Enable users to **navigate easily between dashboards** (Sales ↔ Customer).  
- Make charts and graphs **interactive**, allowing users to **filter data directly by clicking on visuals**.

---

### 🔍 Data Filters
Enable users to filter data by:
- **Product Information**
  - Category  
  - Subcategory
- **Location Information**
  - Region  
  - State  
  - City  

  <p align="left">
  <img src="/docs/sales_and_customers_dashboard.gif" alt="sales_and_customers_dashboard.gif" width="700"/>
  </p>
  
---

## 🧱 Project Summary
| Dashboard | Focus Area | Primary Users | Key Insights |
|------------|-------------|----------------|---------------|
| **Sales Dashboard** | Sales performance, trends, and profitability | Sales Managers, Executives | YoY trends, top-performing subcategories, weekly analysis |
| **Customer Dashboard** | Customer segmentation and profitability | Marketing, Management | Customer loyalty, order frequency, top customers |

---

### 💡 Tools & Technologies
- **Tableau Public**
- **CSV data sources**
- **Calculated Fields, Parameters, Filters, Actions & Charts**

---

🌟 About Me: 
Hi there! I'm Abolfazl Sadeghi. I’m an IE undergraduate in Shahid Beheshti University on to learn new things about data

connect with me:
abolfazl84.as@gmail.com
