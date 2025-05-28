# 🛍️ Retail Analytics Project

This project focuses on analyzing retail transaction data to uncover customer behavior patterns, segment users using RFM analysis, and identify churn risk. It combines data cleaning, exploratory data analysis (EDA), and interactive visualization using Power BI.

---

## 📌 Project Objectives

- Clean and preprocess raw retail transaction and response data.
- Perform insightful exploratory data analysis.
- Identify top customers and high-performing months.
- Segment customers based on RFM (Recency, Frequency, Monetary) analysis.
- Detect churn using customer response data.
- Visualize insights using Power BI dashboards.

---

## 🧰 Tools & Technologies

- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scipy
- **Visualization**: Power BI
- **IDE**: Google Colab / Jupyter Notebook
- **Frontend**: HTML + Embedded Power BI

---

## 📊 Key Features

### 🔹 Data Cleaning
- Merged transaction and response data.
- Handled missing values and datatype corrections.
- Removed outliers using Z-score method.

### 🔹 Exploratory Data Analysis (EDA)
- Analyzed top months and customers by transaction volume.
- Visualized data using bar plots, line charts, and boxplots.

### 🔹 RFM Customer Segmentation
- Recency: Days since last transaction.
- Frequency: Number of transactions.
- Monetary: Total spending amount.
- Segmented customers into:
  - `P0`: High value
  - `P1`: Medium value
  - `P2`: Low value

### 🔹 Churn Analysis
- Used `response` column to identify churned vs active users.
- Visualized churn distribution using bar charts.

### 🔹 Power BI Dashboard
- Three interactive pages for:
  - Monthly sales trends
  - Customer segmentation
  - High-value customer tracking
- Embedded in a responsive HTML interface.

---

## 🖥️ How to Run

1. Clone this repo.
2. Run `datacleaning.py` or open `DataCleaning.ipynb`.
3. View final datasets: `MainData.csv`, `AdditionalAnalysis.csv`.
4. Open `Retail_Analytics.html` to view the integrated Power BI dashboard.

---



