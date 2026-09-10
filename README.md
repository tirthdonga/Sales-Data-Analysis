<div align="center">

# 📊 Sales Data Analysis
### *Excel Sales Data Analysis, What-If Analysis, Regression & Dashboard Project*

![Excel](https://img.shields.io/badge/Microsoft%20Excel-Data%20Analysis-green?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Analytics](https://img.shields.io/badge/Data-Analytics-blue?style=for-the-badge)
![Regression](https://img.shields.io/badge/Linear-Regression-orange?style=for-the-badge)
![Dashboard](https://img.shields.io/badge/Interactive-Dashboard-purple?style=for-the-badge)

</div>

---

# 📋 Table of Contents

- [📌 Overview](#-overview)
- [🎯 Objective](#-objective)
- [✨ Features](#-features)
- [🏗️ Workbook Structure](#️-workbook-structure)
- [🗂️ Worksheets](#️-worksheets)
- [🔍 10 Tasks & Excel Analysis](#-10-tasks--excel-analysis)
- [📊 Data Analysis Techniques](#-data-analysis-techniques)
- [📈 Dashboard](#-dashboard)
- [🛠️ Tech Stack](#️-tech-stack)
- [📈 Learning Outcomes](#-learning-outcomes)
- [👤 Author](#-author)

---

# 📌 Overview

**PR. 2 Analyzer** is a practical Microsoft Excel data-analysis project focused on analyzing customer sales, discounts, profit, monthly growth, regional performance, and product performance.

The workbook applies Excel formulas, Conditional Formatting, What-If Analysis, the Data Analysis ToolPak, Pivot Tables, filters, and charts to convert raw sales data into useful business insights.

The project contains **200 sales records** and multiple analysis worksheets covering the ten required tasks.

---

# 🎯 Objective

The main objective of this project is to develop practical Excel data-analysis skills by applying analytical tools and formulas to a sales dataset.

The project focuses on:

- Conditional Formatting
- What-If Analysis
- Linear Regression using Data Analysis ToolPak
- Descriptive Statistics
- Data Storytelling
- Custom Formatting with symbols/arrows
- Timestamp creation using `NOW()`
- High-value customer identification
- `INDEX()` and `MATCH()` combinations
- Filters and customer analysis
- Pivot Tables
- Bar, Line, and Pie Charts
- KPI Dashboard creation

---

# ✨ Features

- 🏆 Highlight the top 10 customers based on total purchase
- 💡 Analyze how different discount rates affect total profit
- 📈 Perform Linear Regression between Sales and Profit
- 📊 Generate Descriptive Statistics for Sales and Profit
- ⬆️⬇️ Show monthly sales growth using arrows/symbols
- 🕒 Create a timestamp using `NOW()`
- 🔎 Identify high-value customers using `INDEX()`, `MATCH()`, and filters
- 🧮 Analyze total sales by region and product category using a Pivot Table
- 📉 Visualize KPIs using bar, line, and pie charts
- 📋 Present key business insights through a dashboard

---

# 🏗️ Workbook Structure

```text
📦 PR. 2 Analyzer
│
├── 📊 Dashboard
│      ├── KPI visualization
│      ├── Sales charts
│      ├── Profit analysis
│      └── Business insights
│
├── 📄 data
│      ├── Customer information
│      ├── Region
│      ├── Product Category
│      ├── Sales
│      ├── Quantity
│      ├── Discount
│      ├── Order Date
│      └── Profit
│
├── 🏆 Top 10
│      └── Q1 & Q7 Customer Analysis
│
├── 💡 What-If
│      └── Q2 Discount & Profit Analysis
│
├── 📈 Regression & Statistics
│      └── Q3 Regression + Q4 Descriptive Statistics
│
├── 📅 Monthy Sales
│      └── Q5 Monthly Sales Growth
│
├── 💰 Total Sales
│      └── Q8 Pivot Table & Product/Region Analysis
│
└── 📝 Summarize Insight
       └── Q10 Business Insights
```

---

# 🗂️ Worksheets

## 📊 Dashboard

The **Dashboard** worksheet provides a visual summary of the sales analysis using KPIs and charts.

### Main Elements

- Sales KPIs
- Profit KPIs
- Customer analysis
- Regional/product performance
- Bar charts
- Line charts
- Pie charts
- Business insights

## Output

> 🖼️ **Dashboard Screenshot**

**[ 📸 Insert Dashboard Screenshot Here ]**

`Images/dashboard.png`

---

## 📄 Data Worksheet

The **data** worksheet is the main source dataset used throughout the project.

### Main Columns

| Column | Description |
|---|---|
| `Customer_ID` | Unique customer identifier |
| `Customer_Name` | Customer name |
| `Region` | Sales region |
| `Product_Category` | Product category |
| `Sales` | Sales amount |
| `Quantity` | Quantity purchased |
| `Discount` | Discount percentage |
| `Order_Date` | Order date |
| `Profit` | Profit generated |

---

# 🔍 10 Tasks & Excel Analysis

## 1. 🏆 Top 10 Customers

**Task:** Apply Conditional Formatting to highlight the top 10 customers based on total purchase.

### Analysis

- Calculate total sales for each customer
- Rank customers based on total purchase
- Identify the top 10 customers
- Apply Conditional Formatting to highlight high-value customers

### Excel Concepts

- `SUMIF()`
- `COUNTIF()`
- `AVERAGEIF()`
- `RANK()`
- Conditional Formatting

## Output

<img src="images/q1.png">
<img src="images/image.png">

---

## 2. 💡 What-If Analysis – Discount vs Profit

**Task:** Perform What-If Analysis to understand the impact of changing the discount on total profit.

### Analysis

Different discount rates are evaluated to calculate projected total profit and compare the result with current profit.

### Excel Concepts

- What-If Analysis
- Scenario comparison
- `AVERAGE()`
- `SUM()`
- Profit calculations

## Output

> 🖼️ **Q2 Screenshot – What-If Analysis**

**[ 📸 Insert Q2 Screenshot Here ]**

`Images/Q2-what-if.png`

---

## 3. 📈 Linear Regression – Profit vs Sales

**Task:** Use the Data Analysis ToolPak to run Linear Regression between Profit and Sales.

### Analysis

The regression output evaluates the relationship between sales and profit using statistical measures such as:

- Multiple R
- R Square
- Adjusted R Square
- Standard Error
- Observations
- Regression coefficients
- P-value

### Excel Tool

**Data → Data Analysis → Regression**

## Output

> 🖼️ **Q3 Screenshot – Linear Regression**

**[ 📸 Insert Q3 Screenshot Here ]**

`Images/Q3-regression.png`

---

## 4. 📊 Descriptive Statistics

**Task:** Use the **Descriptive Statistics** feature from the Analysis ToolPak on the dataset.

### Statistics Analyzed

- Mean
- Standard Error
- Median
- Mode
- Standard Deviation
- Sample Variance
- Kurtosis
- Skewness
- Range
- Minimum
- Maximum
- Sum
- Count

### Excel Tool

**Data → Data Analysis → Descriptive Statistics**

## Output

> 🖼️ **Q4 Screenshot – Descriptive Statistics**

**[ 📸 Insert Q4 Screenshot Here ]**

`Images/Q4-descriptive-statistics.png`

---

## 5. 📅 Monthly Sales Growth

**Task:** Add up/down arrows to show monthly sales growth.

### Analysis

Monthly sales are compared with the previous month to calculate the percentage growth.

### Example Formula

```excel
=(Current Month Sales - Previous Month Sales) / Previous Month Sales
```

### Excel Concepts

- Monthly sales analysis
- Percentage growth
- Conditional Formatting
- Up/Down arrows
- Line Chart

## Output

> 🖼️ **Q5 Screenshot – Monthly Sales Growth**

**[ 📸 Insert Q5 Screenshot Here ]**

`Images/Q5-monthly-growth.png`

---

## 6. 🕒 Create Timestamp

**Task:** Create a timestamp column using `NOW()`.

### Formula

```excel
=NOW()
```

The timestamp records the current date and time when the formula is calculated.

### Excel Concept

- `NOW()`
- Date & Time formatting

## Output

> 🖼️ **Q6 Screenshot – Timestamp**

**[ 📸 Insert Q6 Screenshot Here ]**

`Images/Q6-timestamp.png`

---

## 7. 🔎 Identify High-Value Customers

**Task:** Identify high-value customers using `INDEX()`, `MATCH()`, and filters.

### Analysis

Customer-level sales information is summarized and used to identify customers with high total purchase values.

### Excel Concepts

- `INDEX()`
- `MATCH()`
- `SUMIF()`
- `COUNTIF()`
- Filters
- Customer ranking

## Output

> 🖼️ **Q7 Screenshot – High-Value Customers**

**[ 📸 Insert Q7 Screenshot Here ]**

`Images/Q7-high-value-customers.png`

---

## 8. 💰 Pivot Table – Total Sales

**Task:** Create a Pivot Table to analyze total sales by region and product.

### Analysis Dimensions

**Rows:**
- Product Category

**Columns:**
- Region

**Values:**
- Total Sales

The Pivot Table provides a quick comparison of product performance across Central, East, North, South, and West regions.

## Output

> 🖼️ **Q8 Screenshot – Pivot Table**

**[ 📸 Insert Q8 Screenshot Here ]**

`Images/Q8-pivot-table.png`

---

## 9. 📊 Charts & KPI Visualization

**Task:** Create bar, line, and pie charts to visualize important KPIs.

### Charts Used

- 📊 Bar Chart – Compare categories/regions
- 📈 Line Chart – Show monthly sales trends
- 🥧 Pie Chart – Show proportional contribution

### Purpose

Charts transform numerical analysis into easy-to-understand visual information for business decision-making.

## Output

> 🖼️ **Q9 Screenshot – Charts**

**[ 📸 Insert Q9 Screenshot Here ]**

`Images/Q9-charts.png`

---

## 10. 📝 Dashboard Insights

**Task:** Summarize the main findings using a dashboard.

### Dashboard Storytelling

The final dashboard brings together:

- Sales performance
- Profit performance
- Customer performance
- Product performance
- Regional performance
- Monthly trends
- Chart-based KPIs
- Key observations

The goal is to present the analysis in a concise and decision-friendly format.

## Output

> 🖼️ **Q10 Screenshot – Dashboard Insights**

**[ 📸 Insert Q10 Screenshot Here ]**

`Images/Q10-insights.png`

---

# 📊 Data Analysis Techniques

| Technique | Purpose |
|---|---|
| Conditional Formatting | Highlight important values such as top customers |
| What-If Analysis | Study the effect of changing discount rates |
| Regression | Measure the relationship between Sales and Profit |
| Descriptive Statistics | Summarize Sales and Profit distributions |
| `NOW()` | Generate a timestamp |
| `INDEX()` + `MATCH()` | Retrieve customer information dynamically |
| Filters | Focus on selected/high-value customers |
| Pivot Table | Summarize sales by product and region |
| Bar Chart | Compare categories |
| Line Chart | Display sales trends |
| Pie Chart | Show proportional contribution |
| Dashboard | Combine KPIs and insights |

---

# 📈 Dashboard

The dashboard is the final visual layer of the project. It combines the analysis from multiple worksheets into a single business-oriented view.

### Dashboard Screenshot

**[ 📸 Insert Your Final Dashboard Screenshot Here ]**

`Images/dashboard.png`

> 💡 **Tip:** Create an `Images` folder in the project repository and place your dashboard screenshot and Q1–Q10 screenshots inside it. Replace the placeholder image paths above with the actual filenames.

---

# 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| 🟢 Microsoft Excel | Spreadsheet & Data Analysis |
| 📊 Conditional Formatting | Highlight important values |
| 🔮 What-If Analysis | Scenario analysis |
| 📈 Data Analysis ToolPak | Regression & Descriptive Statistics |
| 🧮 Excel Formulas | Calculations |
| 🔎 INDEX + MATCH | Dynamic lookup |
| 📋 Pivot Tables | Data summarization |
| 📊 Excel Charts | Data visualization |
| 🎯 Dashboard | KPI reporting & storytelling |

---

# 📈 Learning Outcomes

- ✅ Apply Conditional Formatting to business data
- ✅ Perform What-If Analysis
- ✅ Understand the relationship between Sales and Profit
- ✅ Run Linear Regression using the Data Analysis ToolPak
- ✅ Generate Descriptive Statistics
- ✅ Calculate monthly sales growth
- ✅ Use custom arrows/symbols for visual analysis
- ✅ Create timestamps with `NOW()`
- ✅ Use `INDEX()` and `MATCH()` for dynamic lookups
- ✅ Identify high-value customers
- ✅ Build Pivot Tables for multi-dimensional analysis
- ✅ Create bar, line, and pie charts
- ✅ Design a professional Excel dashboard
- ✅ Communicate findings through data storytelling

---

# 👤 Author

<div align="center">

# Tirth Donga

[![GitHub](https://img.shields.io/badge/GitHub-Tirth_Donga-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tirthdonga)

**PR. 2 Analyzer – Excel Sales Data Analysis Project**

---

### ⭐ Thank You For Visiting This Project ⭐

Made with ❤️ using Microsoft Excel

</div>
