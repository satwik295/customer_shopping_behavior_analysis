# README.md

# Customer Shopping Behavior Analysis

## Overview

The **Customer Shopping Behavior Analysis** project demonstrates an end-to-end data analytics workflow, from raw data preparation to business intelligence reporting. The project combines **Python**, **SQL (PostgreSQL/MySQL/SQL Server)**, **Power BI**, and **Gamma** to transform customer transaction data into actionable business insights.

The analysis focuses on understanding customer purchasing patterns, revenue trends, subscription behavior, product performance, and customer segmentation to support data-driven business decisions. 

---

## Dataset

The project uses a retail customer shopping dataset containing **3,900 customer purchase records** with **18 features**.

### Dataset Includes

* Customer Demographics

  * Age
  * Gender
  * Location
  * Subscription Status

* Purchase Information

  * Item Purchased
  * Category
  * Purchase Amount
  * Season
  * Size
  * Color

* Customer Behavior

  * Discount Applied
  * Promo Code Used
  * Previous Purchases
  * Frequency of Purchases
  * Review Rating
  * Shipping Type

### Data Quality

* Total Records: **3,900**
* Total Columns: **18**
* Missing Values:

  * 37 missing values in the **Review Rating** column



---

## Tools & Technologies

| Tool                            | Purpose                                          |
| ------------------------------- | ------------------------------------------------ |
| Python                          | Data loading, cleaning, EDA, feature engineering |
| Pandas                          | Data manipulation                                |
| NumPy                           | Numerical operations                             |
| PostgreSQL / MySQL / SQL Server | Business query analysis                          |
| SQL                             | Data extraction and reporting                    |
| Power BI                        | Interactive dashboard development                |
| Gamma                           | Report and presentation creation                 |

---

## Project Workflow

### 1. Data Loading

* Imported dataset using Pandas
* Inspected dataset structure
* Generated summary statistics

---

### 2. Data Cleaning

Performed multiple preprocessing tasks including:

* Handling missing values
* Median imputation for Review Rating
* Renaming columns to snake_case
* Removing redundant columns
* Validating data consistency



---

### 3. Feature Engineering

Created additional analytical features including:

* Age Group
* Purchase Frequency (Days)

These features improved customer segmentation and reporting capabilities.



---

### 4. SQL Analysis

The cleaned dataset was loaded into a relational database for business analysis.

Key SQL analyses included:

* Revenue by Gender
* High-Spending Discount Users
* Top Rated Products
* Shipping Type Comparison
* Subscriber vs Non-Subscriber Analysis
* Discount-Dependent Products
* Customer Segmentation
* Top Products by Category
* Repeat Buyer Analysis
* Revenue by Age Group

These queries helped uncover customer behavior patterns and business opportunities. 

---

## Power BI Dashboard

An interactive Power BI dashboard was developed to visualize business insights.

### Dashboard Features

* Customer Overview
* Average Purchase Amount
* Average Review Rating
* Revenue by Category
* Sales by Category
* Revenue by Age Group
* Subscription Distribution
* Interactive Filters

  * Gender
  * Category
  * Shipping Type
  * Subscription Status



---

## Key Results

The analysis revealed several valuable business insights:

* Female customers generated lower overall revenue than male customers.
* Express shipping customers recorded a slightly higher average purchase amount.
* Non-subscribers represented the majority of customers.
* Loyal customers formed the largest customer segment.
* Certain products showed significantly higher dependency on discounts.
* Younger adult customers contributed the highest revenue among age groups.



---

## Business Recommendations

Based on the analysis:

* Increase subscription adoption through exclusive offers.
* Reward loyal and repeat customers with loyalty programs.
* Optimize discount strategies to improve profitability.
* Promote highly rated and frequently purchased products.
* Focus marketing campaigns on high-value customer segments.



---

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
│   └── customer_shopping_data.csv
│
├── Python/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│   └── feature_engineering.ipynb
│
├── SQL/
│   └── business_queries.sql
│
├── PowerBI/
│   └── Customer_Shopping_Dashboard.pbix
│
├── Report/
│   └── Customer_Shopping_Behavior_Analysis.pdf
│
├── Presentation/
│   └── Project_Presentation.pptx
│
└── README.md
```

---

## How to Run

### Step 1

Clone the repository.

```bash
git clone <repository-url>
```

### Step 2

Install the required Python libraries.

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
```

### Step 3

Load the dataset and execute the Python notebooks/scripts for data cleaning and exploratory data analysis.

### Step 4

Import the cleaned dataset into PostgreSQL, MySQL, or SQL Server.

### Step 5

Execute the SQL scripts to generate business insights.

### Step 6

Open the Power BI (.pbix) file to explore the interactive dashboard.

### Step 7

Review the final PDF report and Gamma presentation for business recommendations.

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* SQL Query Writing
* Relational Database Management
* Business Intelligence
* Dashboard Development
* Data Visualization
* Business Analytics
* Report Writing
* Presentation Design


