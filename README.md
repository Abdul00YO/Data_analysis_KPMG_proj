# 📊 Customer Segmentation & Targeting Analysis  
### Sprocket Central Pty Ltd — KPMG Virtual Internship Dataset

## 📌 Project Overview
This project focuses on identifying the **top 1000 high-value customers** for **Sprocket Central Pty Ltd** using structured data analysis techniques.  
The dataset is part of the **KPMG Data Analytics Virtual Internship**, and the objective is to support **data-driven marketing decisions** through customer segmentation.

The analysis was performed using **Microsoft Excel**, applying **RFM (Recency, Frequency, Monetary) analysis**, data cleaning, visualization, and customer profiling.

---

## 🎯 Business Objective
- Identify customers with the **highest business value**
- Segment customers based on purchasing behavior
- Provide actionable insights to support **targeted marketing strategies**

---

## 🗂 Dataset Description
The analysis is based on the following datasets:

- **Transactions** – Customer purchase history
- **Customer Demographic** – Personal and professional details
- **Customer Address** – Geographic information
- **New Customer List** – Potential future customers

---

## 🧩 Project Structure

```
📁 sprocket-customer-analysis
│
├── Task 1 – Data Quality & Issues Documentation
│   └── Dataset issues and data consistency analysis
│
├── Task 2 – Approach Presentation
│   └── PowerPoint outlining data exploration, modeling, and interpretation
│
├── Task 3 – Dashboard & Insights
│   └── Excel dashboard with customer insights and top customer list
│
└── README.md
```

---

## 📝 Task 1: Data Quality & Issues Identification
A detailed assessment was conducted to identify inconsistencies and quality issues across datasets.

### Key Issues Identified

#### Customer Demographic Dataset
- Missing values in:
  - `DOB`
  - `last_name`
  - `job_title`
- Invalid date entries in `DOB`
- Inconsistent gender values (`Male`, `Female`, `M`, `F`)
- High number of `n/a` values in `job_industry_category`
- `default` column contained irrelevant data and was removed

#### Transactions Dataset
- Missing values in:
  - `online_order`
  - `brand`
  - `product_line`
  - `product_class`
  - `product_size`
  - `standard_cost`
  - `product_first_sold_date`
- Invalid date formats in `product_first_sold_date`

#### Customer Address Dataset
- Data quality was consistent and required no major corrections

---

## 📊 Task 2: Analytical Approach
This task explains **how the analysis was performed**, focusing on methodology rather than results.

### Tools Used
- Microsoft Excel
- Pivot Tables
- Quantile-based scoring
- Charts & dashboards

### Key Steps
1. Converted datasets into Excel tables
2. Standardized data types (dates, numbers, categorical fields)
3. Feature engineering:
   - Created `Recency` using current date and transaction date
   - Calculated `Profit` as `list_price – standard_cost`
4. Built a customer-level Pivot Table with:
   - Frequency (count of products)
   - Recency (minimum days)
   - Monetary value (sum of profit)
5. Applied **RFM Scoring** using quantiles:
   - Scores ranged from **1 (lowest)** to **4 (highest)**
6. Computed overall RFM Score:
   ```
   RFM Score = (100 × R) + (10 × F) + M
   ```
7. Segmented customers into:
   - Bronze
   - Silver
   - Gold
   - Platinum

---

## 📈 Task 3: Dashboard & Insights
An interactive Excel dashboard was developed to visualize insights and support decision-making.

### Dashboard Features
- Customer segmentation overview
- Distribution of RFM segments
- Revenue and profitability trends
- Frequency and recency patterns
- **Top 1000 customer list** based on RFM scores

### Key Insight
- **Platinum customers** represent the most valuable segment and were selected as the **primary marketing target group**.

---

## 🏆 Key Outcomes
- Identified the **top 1000 high-value customers**
- Delivered a clear, structured, and scalable targeting approach
- Translated raw data into **business-ready insights**
- Demonstrated end-to-end data analytics workflow using Excel

---

## 🛠 Skills Demonstrated
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- RFM Customer Segmentation
- Business Analytics
- Dashboard Design
- Data Storytelling
- Microsoft Excel (Advanced)

---

## 📌 Conclusion
This project demonstrates how structured data analysis and customer segmentation can drive smarter marketing decisions. The approach is simple, effective, and scalable — making it ideal for real-world business applications.

---

📎 *This project is part of a professional data analytics portfolio and is intended for educational and demonstration purposes.*
