# 📦📊 Amazon Sales Analysis – Power BI Dashboard (2025)

Welcome to my Amazon Sales Analytics Project, where I analyze ₹1.12 Billion worth of sales, 15K+ orders, and 7K+ customers across India using Power BI.

This project converts raw sales data into actionable, decision-ready insights.

## 🚀 Project Summary

This project covers:

₹1.12 Billion Total Sales

15,000+ Orders

7,259 Customers

Average Order Value: ₹74,540

Average Rating: 3.04

5 Categories & 25+ Products

Sales Across All Indian States

## 🔍 Goal:
To uncover patterns in sales, returns, customer behaviour, product performance, delivery efficiency, and payment method usage.

## 📁 Project Files
File	Description
Amazon.pbix	Full interactive Power BI report
Amazon_sales_2025_INR.csv	Dataset used for visualization
Screenshots Folder	All dashboard pages in PNG format

## 🛠️ Tools & Technology Used

Power BI Desktop

Power Query

DAX (Data Analysis Expressions)

Bing Maps Visualization

Treemaps, Donuts, KPI Cards, Scatter Charts

## 🟧 1. Overview Dashboard – Business Summary
<img width="670" height="376" alt="OVERVIEW" src="https://github.com/user-attachments/assets/7315f80b-4cae-4b83-bd6c-f8b1f4cad1e6" />

### ⭐ Key KPIs

1.12Bn – Total Sales

15K – Orders

74.54K – Avg Order Value

7,259 – Customers

3.04 – Avg Rating

### 📅 Sales Trend (Monthly)

Highest Sales: June (97.2M)

Lowest Sales: February (85M)

### 🌍 Sales by State

North-East states show strong performance:
Delhi, Maharashtra, Tamil Nadu also among top.

### 🛍️ Sales by Category

Beauty — 227M

Electronics — 227M

Books — 225M

Clothing — 222M

Home & Kitchen — 217M

### 🚚 Delivery Performance

Delivered — 33.87%

Pending — 33.65%

Returned — 32.48% ⚠ High return rate

## 🟪 2. Product & Category Insights
<img width="669" height="376" alt="Product and Category" src="https://github.com/user-attachments/assets/d29e5567-7f88-4f8a-94b4-cccf21cbd48a" />

### 🛒 Top Products by Sales (≈48M each)

Lipstick

Children’s Books

Headphones

### 📦 Quantity Sold per Category

Beauty — 9.1K units (highest)

### 🗂️ Category Sales Treemap

Beauty & Electronics dominate (~227M each)

Home & Kitchen is the lowest-performing category

### ⭐ Category Ratings

Highest Rating: Electronics (3.07)

Lowest Rating: Clothing (3.00)

## 🟦 3. Payment & Delivery Dashboard
<img width="670" height="377" alt="Payment and Delivery" src="https://github.com/user-attachments/assets/40925558-d47a-4edd-b256-59e6da2ec96d" />

### 💳 Sales by Payment Method

Credit Card – 286.9M

Debit Card – 286.5M

Cash on Delivery – 273M

UPI – 271M

### 👉 Sales distribution is evenly spread — diverse customer base.

### 🚚 Delivery Status Insight

Delivered & Pending: ~0.38Bn each

Returned Orders: 4,881 ⚠

### 🔁 Return Rate by Category

Books — 21.08%

Electronics — 20.61%

📉 Payment Method Affecting Sales

COD has the highest pending deliveries, indicating drop-offs or customer cancellations.

## 🟩  4. Regional Sales & Customer Insights
<img width="669" height="377" alt="Regional Sales and Customer Insights" src="https://github.com/user-attachments/assets/e0c517ed-800e-4410-ac55-bb025a2e5527" />

### 🏆 State-Level Highlights

Sikkim — Highest Orders

Tripura — Highest Avg Rating (3.14)

### 💰 Sales by State

Most states fall in the 41M–43M range.

### ⭐ Customer Rating Distribution

Most states have rating averages between 2.95 and 3.10.

## 📊 Key Business Insights (Must-Read)
### 🔥 1. Beauty & Electronics drive the highest revenue (~227M each)

These two categories alone contribute nearly 40% of the total sales.

### 🔄 2. Return Rate is high (32%+)

Especially Books & Electronics → Indicates customer dissatisfaction, delivery issues, or mismatch of expectations.

#### 💳 3. No dominant payment method

All four methods show balanced adoption, proving a diverse online customer base.

### 🚚 4. COD has maximum pending orders

Affects delivery success & leads to cancellations.

### 🏙️ 5. North-East states perform unexpectedly well

Sikkim, Tripura, Meghalaya are among the strongest performers.

### ⭐ 6. Average customer rating is only 3.04

A clear opportunity for improving product quality & experience.

### 🛒 7. Fast-moving consumer goods dominate

Lipstick, Headphones, Children’s Books → strong volume & stable sales.

## 🧮 DAX Measures Used
Total Sales = SUM(Sales[Total_Sales_INR])

Average Order Value = [Total Sales] / [Total Orders]

Returned % = DIVIDE([Returned Sales], [Total Sales])

Delivered % = DIVIDE([Delivered Sales], [Total Sales])

Avg Rating = AVERAGE(Sales[Rating])

## 🔧 Data Model Structure

✔ 1 Fact Table: Sales
✔ Multiple Dimension Tables: Product, Category, State, Month
✔ Cleaned with Power Query
✔ Used relationship-based modeling

## 🏁 Conclusion

This dashboard provides a complete 360° view of Amazon sales – covering:

✔ Revenue trends
✔ Product & category performance
✔ Delivery & returns health
✔ Regional buying behaviour
✔ Payment method impact
✔ Customer satisfaction

It transforms raw data into clear, actionable insights for business decisions.

## 🙌 Connect With Me

If you want a custom dashboard or want help improving your analytics project, feel free to reach out!
