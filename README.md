# Customer Shopping Behavior Analysis

A Data Analytics project focused on understanding customer purchasing patterns using Python, SQL, and Power BI.

## Project Overview

In this project, I analyzed customer shopping behavior to understand:

- Which product categories generate the most revenue
- How customer spending varies by gender and age group
- Subscription vs non-subscription behavior
- Discount usage and its impact on purchasing
- Product ratings and top-rated products
- Shipping preferences
- Customer loyalty based on previous purchases
- Purchase frequency and payment methods

## Tools Used

- Python
- Pandas
- SQL / MySQL
- Power BI
- Jupyter Notebook

## Analysis Process

### 1. Data Cleaning – Python

I used Python and Pandas to prepare the dataset.

Main steps:

- Checked dataset structure and data types
- Identified missing values
- Filled missing Review Rating values using category-wise median
- Standardized column names
- Removed redundant columns
- Created age groups
- Converted purchase frequency into approximate days

### 2. Exploratory Data Analysis – Python

I analyzed:

- Customer demographics
- Product categories
- Purchase amount
- Review ratings
- Subscription status
- Discount usage
- Shipping type
- Age groups
- Payment methods
- Purchase frequency

### 3. SQL Analysis

I used SQL to answer business questions such as:

- Revenue contribution by gender
- Customers with discounted purchases above average
- Top 5 products by average rating
- Average purchase amount by shipping type
- Subscription vs non-subscription spending
- Products with the highest discount percentage
- New, Returning and Loyal customer segments
- Most purchased product in each category
- Subscription behavior among repeat customers
- Revenue by age group

### 4. Power BI Dashboard

I created an interactive Power BI dashboard to visualize the analysis.

The dashboard includes:

- Customer count
- Average purchase amount
- Average review rating
- Subscription analysis
- Revenue by category
- Sales by category
- Revenue by age group
- Sales by age group
- Gender, category, subscription and shipping filters

## Key Findings

- Clothing is the leading category in the analysis.
- Average purchase amount is approximately **$59.76**.
- Average review rating is approximately **3.75**.
- Approximately **27%** of records are subscribers.
- Approximately **73%** are non-subscribers.
- Young Adult is the strongest age-group segment in the Power BI analysis.

## Power BI Dashboard

<img width="1272" height="645" alt="dashboard" src="https://github.com/user-attachments/assets/ccc354ad-e7b6-46e5-afc1-11c7b8543b50" />


## 🚀 How to Run

### Python

Install the required libraries:

```bash
pip install pandas numpy sqlalchemy pymysql jupyter

Open Jupyter Notebook:

jupyter notebook

Then open and run:

Customer-Shopping-Behavior-Analysis.ipynb
SQL
Install MySQL.
Create the required database.
Load the cleaned customer data.
Run the SQL queries from:
customer_shopping_behavior_analysis.sql
Power BI

Open:

customer_shopping_behavior_analysis.pbix

and refresh the data source if required.

🔮 Future Scope

Future improvements could include:

RFM Customer Segmentation
Customer Lifetime Value Analysis
Churn Prediction
Purchase Prediction
Time-Series Analysis after adding transaction dates
Automated Power BI Refresh
Advanced Customer Segmentation

📁 Project Structure
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── Customer-Shopping-Behavior-Analysis.ipynb
│
├── sql/
│   └── customer_shopping_behavior_analysis.sql
│
├── dashboard/
│   └── customer_shopping_behavior_analysis.pbix
│
├─── dashboard.png
│
└── project-report.pdf
│
├─── presentation
│
└── README.md

## 👤 Author
NAME: NIRAJ KUMAR — LinkedIn: www.linkedin.com/in/niraj649 — Email: niraj.kumar.in07@gmain.com

Data Analytics | Python | SQL | Power BI

