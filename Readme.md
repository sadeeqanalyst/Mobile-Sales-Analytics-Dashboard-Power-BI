# 📱 Mobile Sales Analytics Dashboard — Power BI

An interactive **Mobile Sales Analytics Dashboard** built with Microsoft Power BI to analyze sales performance, customer behavior, transactions, product performance, and geographical sales distribution.

The dashboard transforms raw mobile sales data into meaningful business insights through interactive visualizations, KPIs, filters, and analytical views.

---

## 📊 Dashboard Preview

![Mobile Sales Dashboard](dashboard.png)

> Replace `dashboard.png` with the actual screenshot file name uploaded to this repository.

---

## 🎯 Project Objective

The objective of this project is to develop a professional Business Intelligence dashboard that helps stakeholders:

- Monitor overall sales performance
- Analyze sales trends over time
- Identify high-performing brands and mobile models
- Understand customer ratings
- Analyze payment method preferences
- Compare sales performance across cities
- Identify daily and monthly sales patterns
- Support data-driven business decisions

---

## 🔍 Key KPIs

The dashboard provides high-level performance indicators including:

- **Total Sales**
- **Total Quantity Sold**
- **Total Transactions**
- **Customer Ratings**
- **Sales by Brand**
- **Sales by Mobile Model**
- **Sales by City**
- **Transactions by Payment Method**

---

## 📈 Dashboard Features

### 1. Sales Performance Analysis
Analyze total sales across different brands and mobile models to identify top-performing products.

### 2. Geographic Sales Analysis
Interactive map visualization showing sales distribution across different cities.

### 3. Monthly Trend Analysis
Track monthly quantity trends and identify changes in sales activity throughout the year.

### 4. Customer Rating Analysis
Analyze customer ratings from 1 to 5 to understand overall customer satisfaction.

### 5. Payment Method Analysis
Compare transaction volumes across:

- UPI
- Debit Card
- Cash
- Credit Card

### 6. Brand & Product Analysis
Compare brands and mobile models based on:

- Total Sales
- Total Quantity
- Transactions

### 7. Day-wise Analysis
Analyze sales performance across different days of the week.

### 8. Interactive Filtering
The dashboard includes dynamic slicers for:

- Mobile Model
- Payment Method
- Brand
- Day Name

Users can interact with the filters to perform focused analysis.

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **Microsoft Power BI** | Dashboard development & visualization |
| **Power Query** | Data cleaning & transformation |
| **DAX** | Measures & analytical calculations |
| **Data Modeling** | Structuring analytical data |
| **Data Visualization** | Business insight presentation |

---

## 🧹 Data Preparation

The data preparation process included:

- Data cleaning
- Handling data types
- Removing inconsistencies
- Transforming columns
- Creating calculated fields
- Preparing data for analysis
- Building relationships within the data model

Power Query was used extensively to prepare the dataset before visualization.

---

## 🧮 DAX & Measures

DAX was used to create business metrics and analytical calculations such as:

- Total Sales
- Total Quantity
- Total Transactions
- Average Customer Rating
- Brand-wise performance
- Product-wise performance
- Monthly trends

The measures were designed to work dynamically with dashboard filters and slicers.

---

## 📊 Business Insights

The dashboard enables stakeholders to answer questions such as:

- Which brands generate the highest sales?
- Which mobile models are performing best?
- Which cities contribute the most to sales?
- How does sales quantity change month by month?
- Which payment method is most frequently used?
- What is the distribution of customer ratings?
- Which days show stronger sales performance?
- How do different brands compare in terms of transactions and quantity?

---

## 🏗️ Dashboard Structure

The dashboard is organized into several analytical sections:

```text
Mobile Sales Dashboard
│
├── KPI Overview
│   ├── Total Sales
│   ├── Total Quantity
│   └── Transactions
│
├── Geographic Analysis
│   └── Sales by City
│
├── Trend Analysis
│   └── Monthly Quantity
│
├── Customer Analysis
│   └── Customer Ratings
│
├── Payment Analysis
│   └── Payment Methods
│
├── Product Analysis
│   ├── Brand Performance
│   └── Mobile Model Performance
│
└── Time Analysis
    └── Sales by Day
