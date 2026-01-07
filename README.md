# Customer-Behavior-Analysis
Data Analytics project showcasing  Customer Behavior Analysis using Python, SQL and Power BI 

# 📊 Customer Shopping Behavior Analysis

## 📌 Overview
This project analyzes customer shopping behavior using retail transactional data to uncover trends, patterns, and actionable business insights.  
It follows an **end-to-end data analytics workflow**, covering data cleaning, exploratory analysis, SQL-based querying, and interactive dashboard development.

The project demonstrates practical experience with **Python, SQL Server, and Power BI**.

---

## 📂 Dataset
- **Records:** 3,900+ transactions  
- **Columns:** 18  
- **Key Features:**
  - Customer demographics (Age, Gender, Location, Subscription Status)
  - Purchase details (Product, Category, Amount, Season, Size, Color)
  - Shopping behavior (Discount Applied, Purchase Frequency, Review Rating, Shipping Type)
- **Data Quality:**
  - Missing values in the *Review Rating* column, handled during preprocessing

---

## 🛠 Tools & Technologies
- **Python:** Pandas, NumPy (EDA & data cleaning)
- **SQL Server (MSSQL):** Data analysis and business queries
- **Power BI:** Dashboard creation and visualization
- **Jupyter Notebook:** Analysis and documentation

---

## 🔄 Project Workflow

### 1️⃣ Data Loading & Exploration (Python)
- Loaded dataset using Pandas  
- Inspected schema, data types, and summary statistics  
- Identified missing values and data inconsistencies  

### 2️⃣ Data Cleaning & Feature Engineering
- Imputed missing *Review Ratings* using category-level medians  
- Standardized column names for consistency  
- Created new features such as **Age Groups** and **Purchase Frequency (Days)**  
- Removed redundant columns to improve data quality  

### 3️⃣ SQL Analysis (SQL Server)
- Loaded cleaned data into **MSSQL Server**  
- Executed SQL queries to analyze:
  - Revenue by gender, age group, and subscription status  
  - Discount usage vs purchase value  
  - Top-rated and best-performing products  
  - Customer segmentation (New, Returning, Loyal)  
  - Shipping type impact on spending  

### 4️⃣ Dashboard Development (Power BI)
- Built an interactive Power BI dashboard to visualize:
  - Revenue trends  
  - Customer segmentation  
  - Product and category performance  
  - Discount and subscription impact  
- Enabled filters for deeper business analysis  

### 5️⃣ Reporting & Insights
- Created a structured analytical report  
- Provided business recommendations based on insights  

---

## 📊 Dashboard
The Power BI dashboard highlights:
- Customer purchasing behavior  
- Revenue contribution by different segments  
- Product and category performance  
- Impact of discounts and subscriptions  



---

## 📈 Results & Key Insights
- Identified high-value customer segments and repeat buyers  
- Evaluated discount effectiveness and subscription behavior  
- Highlighted top-performing and highly rated products  
- Delivered insights to improve customer retention and revenue strategies  

