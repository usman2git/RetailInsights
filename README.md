# 📊 Online Retail Sales Analysis & Interactive Dashboard  
### *Python • Pandas • Plotly • Dash • Data Visualization Project*

## 📁 Project Overview  
This project analyzes the **Online Retail Dataset**, which contains real transaction records from an online retail business. The goal was to transform raw sales data into **actionable business insights** through:

- Data cleaning & preprocessing  
- Feature engineering  
- Exploratory data analysis (EDA)  
- Interactive dashboard development using **Dash & Plotly**

The final dashboard allows users to explore revenue trends, top‑selling products, country‑level performance, and transaction distribution through dynamic filters.

---

## 📦 Dataset Description  
The dataset includes:

- **InvoiceNo** – Unique invoice identifier  
- **StockCode** – Product code  
- **Description** – Product name  
- **Quantity** – Number of units sold  
- **InvoiceDate** – Date and time of transaction  
- **UnitPrice** – Price per unit  
- **CustomerID** – Unique customer identifier  
- **Country** – Customer’s country  

---

## 🧹 Data Cleaning & Preparation  
Key preprocessing steps performed:

### ✔ Missing Values  
- Removed rows with missing **Description** (product info required for analysis)  
- Retained rows with missing **CustomerID** (not essential for business questions)

### ✔ Duplicate Records  
- Identified and removed **5,225 duplicate rows** to prevent double‑counting

### ✔ Data Type Fixes  
- Converted `InvoiceDate` to proper datetime format

### ✔ Feature Engineering  
Created new columns to support time‑based analysis:

- `Year`  
- `Month`  
- `MonthName`  
- `Day`  
- `Date`  
- `Revenue = Quantity × UnitPrice`

---

## 📊 Dashboard Features (Plotly + Dash)

The interactive dashboard includes:

### **1. KPI Cards**
- **Total Revenue**  
- **Total Orders**  
- **Average Transaction Value**

These KPIs update instantly when filters change.

### **2. Filters**
Users can filter the entire dashboard by:

- **Month**  
- **Country**  
- **Product**

### **3. Visualizations**
#### **Top Products by Revenue (Bar Chart)**
Shows highest‑earning products, helping identify key revenue drivers.

#### **Revenue Trend Over Time (Line Chart)**
Reveals daily revenue patterns, seasonality, and sales spikes.

#### **Revenue Share by Country (Pie Chart)**
Highlights which countries contribute most to total revenue  
(UK is the dominant market).

#### **Revenue Distribution (Box Plot)**
Shows variability and outliers — identifying unusually large transactions.

---

## 🧠 Key Insights  
- The **United Kingdom** generates the majority of total revenue.  
- A few products (e.g., *REGENCY CAKESTAND 3 TIER*) contribute disproportionately to sales.  
- Revenue shows clear **peaks and dips**, indicating seasonal or promotional effects.  
- Most transactions are small, but a few **high‑value outliers** significantly impact revenue.

---

## 🛠️ Technologies Used  
- **Python**  
- **Pandas** – Data cleaning & manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib & Seaborn** – Initial EDA visualizations  
- **Plotly Express** – Interactive charts  
- **Dash** – Web‑based interactive dashboard  
- **Jupyter Notebook** – Development environment  

---

## 🚀 How to Run the Dashboard

### **1. Clone the repository**
```bash
git clone https://github.com
