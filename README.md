<h1 align="center">☕ Coffee Shop Sales Dashboard — Power BI</h1>

<p align="center">
  <strong>Interactive Coffee Shop Sales Analysis Dashboard</strong>
</p>

<p align="center">
  Power BI • Excel • DAX • Data Analysis • Data Visualization
</p>

---

## 📌 Project Overview

This project presents an interactive **Coffee Shop Sales Dashboard** built using **Microsoft Power BI**.

The dashboard analyzes coffee shop sales data to identify sales trends, customer purchasing patterns, product performance, and peak business hours.

The goal of this project is to transform raw transactional data into meaningful and actionable business insights through interactive dashboards and visualizations.

---

## 🎯 Project Objectives

- Analyze overall coffee shop sales performance
- Identify monthly and daily sales trends
- Analyze sales by hour of the day
- Understand product category performance
- Identify high-performing products
- Analyze customer purchasing behavior
- Identify peak sales hours
- Create an interactive and easy-to-use business dashboard

---

## 📊 Key Performance Indicators

| KPI | Value |
|---|---:|
| 🧾 Total Transactions | **149K+** |
| 💰 Total Sales | **698K+** |
| 📦 Total Quantity Sold | **214K+** |
| 🛒 Average Order Value | **4.69** |

---

## 📈 Dashboard Features

### 1. 💰 Sales Performance

- Total sales analysis
- Monthly sales trends
- Daily sales performance
- Average Order Value
- Total quantity sold

### 2. ⏰ Hourly Sales Analysis

- Sales by hour
- Identification of peak business hours
- Customer purchasing patterns throughout the day

### 3. 📅 Time-Based Analysis

- Monthly performance
- Day-wise sales analysis
- Weekday performance
- Hourly trends

### 4. ☕ Product Analysis

- Product category performance
- Product-level sales analysis
- Quantity sold by product
- Identification of high-performing products

### 5. 🎛️ Interactive Filters

The dashboard includes interactive slicers and filters to allow users to explore:

- Month
- Day
- Product Category
- Product
- Time Period

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Microsoft Excel**
- **DAX**
- **Data Cleaning**
- **Data Transformation**
- **Data Visualization**
- **Pivot Tables**

---

## 🧮 DAX Measures

### Total Sales

```DAX
Total Sales = SUM(Sales[Sales])
```

### Total Quantity

```DAX
Total Quantity = SUM(Sales[Quantity])
```

### Total Transactions

```DAX
Total Transactions = DISTINCTCOUNT(Sales[transaction_id])
```

### Average Order Value

```DAX
Average Order Value =
DIVIDE(
    [Total Sales],
    [Total Transactions]
)
```

> Note: Update the table and column names according to your Power BI data model if they are different.

---

## 🔄 Data Analysis Process

```text
Raw Data
   ↓
Data Cleaning
   ↓
Data Transformation
   ↓
Data Modeling
   ↓
DAX Measures
   ↓
Interactive Visualizations
   ↓
Power BI Dashboard
   ↓
Business Insights
```

---

## 🔍 Key Insights

The dashboard helps identify:

- 📈 Sales trends across different months
- ⏰ Peak sales hours
- ☕ Best-performing product categories
- 📦 Products with higher sales quantities
- 📅 Differences in sales across days
- 💰 Overall revenue performance
- 🛒 Customer ordering patterns

These insights can help coffee shop businesses improve inventory planning, staffing, promotions, and sales strategies.

---

## 📷 Dashboard Preview

<p align="center">
  <img src="images/dashboard.png" alt="Coffee Shop Sales Dashboard" width="900">
</p>

---

## 📂 Project Structure

```text
Coffee-Shop-Sales-Dashboard-PowerBI/
│
├── 📊 coffee dashboard.pbix
├── 📁 images/
│   └── dashboard.png
└── 📄 README.md
```

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Data Analysis
- Data Visualization
- Microsoft Excel
- Microsoft Power BI
- DAX
- KPI Development
- Dashboard Design
- Business Intelligence
- Interactive Reporting
- Business Insights

---

## 🎓 Learning Outcomes

This project helped strengthen my understanding of:

- Building interactive Power BI dashboards
- Creating DAX measures
- Designing meaningful KPIs
- Analyzing transactional data
- Creating time-based analysis
- Using slicers and filters
- Converting raw data into business insights

---

## 🔮 Future Improvements

- Add sales forecasting
- Add profit and cost analysis
- Add customer segmentation
- Add geographical analysis
- Add automated data refresh
- Add advanced Power BI analytics

---

## 👨‍💻 About Me

**Kamlesh Kumar**

Aspiring Data Analyst with an interest in **Python, SQL, Excel, Power BI and Data Visualization**.

Currently building practical data analytics projects and looking for opportunities to apply my skills to real-world problems.

---

## 📫 Connect With Me

- 💼 [LinkedIn](https://www.linkedin.com/)
- 🐙 [GitHub](https://github.com/kamleshk64998-hash)

---

<p align="center">
  ⭐ If you find this project useful, feel free to explore the repository and give it a star!
</p>
