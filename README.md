# 📊 Data Cleaning, Exploratory Data Analysis (EDA) & Business Intelligence

## 📌 Project Overview

This project focuses on performing **Data Cleaning, Exploratory Data Analysis (EDA), SQL Analysis, Excel Reporting, and Power BI Dashboard Creation** using the Superstore dataset.

The objective is to transform raw business data into meaningful insights through visualization, KPI tracking, and business reporting.

---

## 🎯 Objectives

* Clean and preprocess raw data
* Identify and handle missing values
* Remove duplicate records
* Perform Exploratory Data Analysis (EDA)
* Calculate important business KPIs
* Analyze sales and profit trends
* Create Excel Pivot Tables and Charts
* Perform SQL-based analysis
* Build an interactive Power BI dashboard
* Generate business insights

---

## 🛠️ Tools & Technologies Used

* Python
* Google Colab
* Pandas
* Matplotlib
* SQLite
* Microsoft Excel 2010
* Power BI
* GitHub

---

## 📂 Dataset

Dataset Used: **Sample Superstore Dataset**

Features include:

* Order ID
* Customer ID
* Category
* Sub-Category
* Region
* Segment
* Sales
* Profit
* Order Date
* Ship Date

---

## 🧹 Data Cleaning Process

* Imported dataset into Google Colab
* Checked data types
* Handled missing values
* Removed duplicate entries
* Converted date columns into datetime format
* Exported cleaned dataset

---

## 📈 Exploratory Data Analysis

The following analyses were performed:

### Sales Analysis

* Sales by Category
* Sales by Segment
* Top Selling Products

### Profit Analysis

* Profit by Region
* Profit Distribution
* Loss-Making Products

### Customer Analysis

* Total Customers
* Total Orders
* Segment Contribution

---

## 📊 Key Performance Indicators (KPIs)

* Total Sales
* Total Profit
* Total Orders
* Total Customers

---

## 📑 Excel Analysis

Created Pivot Tables for:

* Sales by Category
* Profit by Region
* Segment-wise Sales

Created charts including:

* Bar Charts
* Column Charts
* Pie Charts

---

## 🗄️ SQL Analysis

Sample SQL Queries:

```sql
SELECT Category,
SUM(Sales)
FROM sales
GROUP BY Category;
```

```sql
SELECT Region,
SUM(Profit)
FROM sales
GROUP BY Region;
```

```sql
SELECT Segment,
COUNT(*)
FROM sales
GROUP BY Segment;
```

---

## 📊 Power BI Dashboard

Dashboard Components:

✔ KPI Cards

✔ Sales by Category

✔ Profit by Region

✔ Segment Analysis

✔ Interactive Filters

✔ Top Products Analysis

---

## 💡 Business Insights

* Technology category generated the highest sales.
* West region contributed maximum profit.
* Consumer segment generated significant revenue.
* Certain products showed negative profit margins.
* Sales performance varies across regions.

---

## 📁 Project Structure

```text
Task1-EDA

│
├── Task1_EDA.ipynb
├── SampleSuperstore.csv
├── cleaned_superstore.csv
├── Task1_Excel.xlsx
├── dashboard.pbix
├── sales_chart.png
├── profit_chart.png
├── top_products.png
├── README.md
```

---

## 🚀 How to Run the Project

### Clone Repository

```bash
git clone https://github.com/yourusername/Task1-EDA.git
```

### Install Dependencies

```bash
pip install pandas matplotlib openpyxl
```

### Run Notebook

Open:

```text
Task1_EDA.ipynb
```

in Google Colab and execute all cells.

--

## 👩‍💻 Author

**Yogita Dahiya**

BCA Student

Hindu Girls College, Sonipat

Aspiring Data Analyst | Python | SQL | Excel | Power BI
