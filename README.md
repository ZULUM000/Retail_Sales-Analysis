# 📊 Retail Sales Analysis

## **Project Overview**
This project focuses on analyzing retail sales data through **ETL (Extract, Transform, Load) processes** and **data visualization** using Power BI. The objective is to derive insights into sales trends, customer behavior, and business performance by leveraging **data cleansing, aggregation, and KPI tracking**.

---

## Data Exploration:

**1. Transaction ID:** A unique identifier assigned to each sales transaction for tracking and reference.
   
**2. Date:** The specific date on which the transaction took place.
   
**3. Customer ID:** A unique identifier assigned to each customer to differentiate individual buyers.
 
**4. Gender:**  The gender of the customer who made the purchase.

**5. Age:** The age of the customer at the time of the transaction.
 
**6. Product Category:** The type of product purchased, categorized as Beauty, Clothing, or Electronics.

**7. Quantity:** The number of units of the product bought in the transaction.
 
**8. Price per Unit:** The cost of a single unit of the purchased product.
   
**9. Total Amount:**  The total value of the transaction.


## **🔄 ETL Process**

### **1️⃣ Extract (Data Sources)**
- The dataset was obtained from an Excel file containing transaction records.
- Data fields include **Date, Product Type, Quantity Sold, Revenue, and Customer Details**.

### **2️⃣ Transform (Data Cleaning & Preparation)**
To ensure accurate and reliable insights, we applied the following transformations:

✅ **Handling Missing Data**
   - Filled missing numerical values using mean/median imputation.
   - Categorical fields were assigned default values based on logical assumptions.

✅ **Structuring Age Groups**
   - Grouped customers into age brackets: **18–29, 30–39, 40–49, 50–64**.

✅ **Date Attribute Extraction**
   - Created additional time-based fields:
     - **Year** (e.g., 2023, 2024)
     - **Month** (January, February, etc.)
     - **Quarter** (Q1, Q2, Q3, Q4)
     - **Weekday & WeekType** (Weekday or Weekend classification)

✅ **Categorizing Product Types**
   - Standardized into three main categories: **Beauty, Clothing, Electronics**.

### **3️⃣ Load (Data Integration in Power BI)**
- Cleaned and structured data was imported into **Power BI**.
- Created calculated columns and measures using **DAX (Data Analysis Expressions)** for deeper analysis.

---
## **📊 Insights & Visualization**
The Power BI dashboard provides key insights into business performance, including:

### **1️⃣ Key Metrics Tracking**
✔ **Total Sales** – Measures total revenue over different periods.
✔ **Units Sold** – Tracks the number of products sold.
✔ **Average Price per Unit** – Helps in understanding pricing strategies.

### **2️⃣ Revenue & Sales Trends**
📌 **Revenue Over the Years** – Shows how sales have grown or declined year-over-year.

📌 **Revenue Per Month** – Identifies peak and low-performing months.

📌 **Quantity Sold Per Year** – Measures customer purchase trends.

📌 **Transaction Amount Per Month & Year** – Highlights sales performance patterns.

### **3️⃣ KPI Indicators & Performance Tracking**
📊 **Profit/Loss Indicator** – Displays whether the business made a **Profit or Loss**.

📊 **Revenue Growth % (YoY Change)** – Measures annual percentage growth in revenue.

📊 **Revenue Change Over Time** – Highlights increases/decreases in revenue.

### **4️⃣ Conditional Formatting (KPI Visuals with Arrows)**
- 📈 **Green Arrows** indicate **positive growth** (Revenue & Profit Increase).
  
- 📉 **Red Arrows** highlight **declining trends** (Revenue Drop or Loss).

---
## **💡 Key Findings & Business Impact**
🔹 **Seasonal Trends**: Higher sales observed in Q4, indicating a **holiday shopping spike**.

🔹 **Product Performance**: Electronics generated the highest revenue, while Beauty products had **consistent demand**.

🔹 **Customer Behavior**: Weekends had **higher transaction volumes**, signaling increased shopping activity.

🔹 **Revenue Growth**: Positive growth was observed year-over-year, though certain months exhibited dips requiring further analysis.

---
## **🚀 Next Steps & Improvements**
📌 Further **optimize pricing strategies** based on product performance.

📌 Improve **inventory management** to align with peak sales months.

📌 Use **predictive analytics** to forecast sales trends.

---
## **📂 Project Files**
- **`retail_sales_dataset_cleaned.xlsx`** → Cleaned and transformed dataset.
- **`RETAIL SALES.pbix`** → Power BI report with interactive dashboards.
- **`retailsalesdata.ipynb`** → Python script for data preprocessing.

---
## **👨‍💻 Contributors**
🚀 Developed by **[Your Name]** – Data Analyst

📧 Contact: your.email@example.com

