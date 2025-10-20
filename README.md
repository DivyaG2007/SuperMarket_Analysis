# Supermarket Sales Analysis

## Project Overview
This project focuses on *exploratory data analysis (EDA)* of a supermarket sales dataset obtained from Kaggle. The goal is to uncover insights about sales patterns, customer behavior, and product performance using descriptive statistics and visualizations.  
No machine learning models were built — the analysis strictly focuses on data understanding and interpretation.

---

## Dataset Information
- *Source*: [Kaggle – Supermarket Sales Dataset](https://www.kaggle.com/datasets/faresashraf1001/supermarket-sales)
- *File Used*: SuperMarket Analysis.csv
- *Description*:  
  The dataset contains sales transactions from a supermarket, including branch details, product lines, customer demographics, payment methods, and sales metrics.

### Key Columns
| Column | Description |
|:--------|:-------------|
| Invoice ID | Unique identifier for each transaction |
| Branch | Store branch (A, B, or C) |
| City | City where the branch is located |
| Customer type | Member or Normal customer |
| Gender | Gender of the customer |
| Product line | Category of the product purchased |
| Unit price | Price per unit |
| Quantity | Number of units purchased |
| Tax 5% | 5% tax on the purchase amount |
| Total | Total amount (including tax) |
| Date | Date of the transaction |
| Time | Time of the transaction |
| Payment | Mode of payment (e.g., Cash, Ewallet, Credit card) |
| Rating | Customer satisfaction rating |

---

## Technologies Used
- *Language*: Python  
- *Libraries*:
  - pandas — Data manipulation and cleaning
  - numpy — Numerical analysis
  - matplotlib — Data visualization
  - seaborn — Statistical plots

---

## Analysis Performed
### 1. *Data Loading and Inspection*
- Loaded dataset into a pandas DataFrame.
- Inspected column names, data types, and non-null values.
- Displayed basic statistical summaries using describe().

### 2. *Data Cleaning*
- Handled inconsistent date formats.
- Removed missing values using dropna().
- Standardized categorical columns (e.g., trimmed spaces, corrected capitalization).
- Detected outliers using *Interquartile Range (IQR)* for numeric features.

### 3. *Exploratory Analysis*
#### A. Product Performance
- Computed *total quantity sold per product line* to identify high-demand categories.
- Visualized demand using *bar plots* and *pie charts*.

#### B. Sales and Revenue Insights
- Analyzed *total sales* and *tax contributions* by city and branch.
- Compared *payment methods* across customers.
- Identified *top-performing branches* in terms of total sales.

#### C. Customer Demographics
- Examined *gender distribution* across product lines.
- Investigated the relationship between *customer type* (Member/Normal) and *average spending*.

#### D. Temporal Analysis
- Converted Date to datetime and analyzed sales trends over time.
- Derived *weekday/weekend sales patterns*.

---

## Visualizations
The notebook includes multiple insightful plots:
- Bar plots for product demand and city-wise sales.
- Pie charts for payment methods and gender distribution.
- Line plots showing sales trends over time.

---
## Credits

- Developed by: Giddaluru Divya

- Dataset Source: Kaggle – Supermarket Sales Dataset


   
