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
- Removed rows with missing **Description**  
- Retained rows with missing **CustomerID**

### ✔ Duplicate Records  
- Removed **5,225 duplicate rows** to avoid double‑counting

### ✔ Data Type Fixes  
- Converted `InvoiceDate` to datetime format

### ✔ Feature Engineering  
Created new columns:

- `Year`  
- `Month`  
- `MonthName`  
- `Day`  
- `Date`  
- `Revenue = Quantity × UnitPrice`

---

## 📊 Dashboard Features (Plotly + Dash)

### **1. KPI Cards**
- **Total Revenue**  
- **Total Orders**  
- **Average Transaction Value**

### **2. Filters**
- Month  
- Country  
- Product  

### **3. Visualizations**
- **Top Products by Revenue (Bar Chart)**  
- **Revenue Trend Over Time (Line Chart)**  
- **Revenue Share by Country (Pie Chart)**  
- **Revenue Distribution (Box Plot)**  

---

## 🧠 Key Insights  
- The **United Kingdom** contributes the highest share of revenue.  
- A few products generate disproportionately high revenue.  
- Revenue shows clear **seasonal peaks and dips**.  
- Most transactions are small, with a few **high‑value outliers**.

---

## 🛠️ Technologies Used  
- **Python**  
- **Pandas**  
- **NumPy**  
- **Matplotlib & Seaborn**  
- **Plotly Express**  
- **Dash**  
- **Jupyter Notebook**

---

## 🚀 Installation & Setup

### **1. Clone the repository**
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
