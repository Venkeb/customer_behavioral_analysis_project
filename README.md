# customer_behavioral_analysis_project
Data analytics project showcasing customer behavior analysis using Python, SQL and Power BI
# Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes **customer shopping behavior** using transactional data from **3,900 purchases** across different product categories.

The objective is to identify customer spending patterns, product preferences, subscription behavior, discount usage, and customer segments to support data-driven business decisions.

## 🛠️ Tools & Technologies

* **Python** – Data loading, cleaning, feature engineering & Exploratory Data Analysis
* **Pandas** – Data manipulation and analysis
* **MS SQL Server** – Business analysis and SQL queries
* **Power BI** – Interactive dashboard and data visualization
* **Gamma** – Project presentation
* **Microsoft Word** – Project documentation/report

## 📊 Dataset

The dataset contains:

* **3,900 rows**
* **18 columns**
* Customer demographics
* Purchase and product details
* Discount and promotion information
* Previous purchase history
* Purchase frequency
* Review ratings
* Subscription status
* Shipping information

The dataset initially contained **37 missing values in the Review Rating column**.

## 🔍 Project Workflow

### 1. Data Loading & Exploration

The dataset was loaded into Python using Pandas.

Performed initial analysis using:

* `df.info()`
* `df.describe()`
* Null-value checks
* Data structure validation
* Basic statistical analysis

### 2. Data Cleaning & Preparation

The following data preparation activities were performed:

* Handled missing Review Rating values using the **median rating of each product category**
* Standardized column names using snake_case
* Created an `age_group` feature
* Created `purchase_frequency_days`
* Checked data consistency between discount and promo-code fields
* Removed the redundant `promo_code_used` column
* Exported the cleaned dataset to CSV for SQL analysis

### 3. SQL Analysis – MS SQL Server

The cleaned dataset was imported into **MS SQL Server** and analyzed using SQL queries.

Key business questions included:

* Revenue comparison by gender
* High-spending customers who used discounts
* Top 5 products based on review ratings
* Standard vs. Express shipping analysis
* Subscribers vs. non-subscribers spending comparison
* Products with the highest percentage of discounted purchases
* Customer segmentation into New, Returning, and Loyal customers
* Top 3 most purchased products within each category
* Relationship between repeat purchases and subscriptions
* Revenue contribution by age group

### 4. Power BI Dashboard

An interactive **Power BI dashboard** was created to visualize the key findings and make the analysis easier for business stakeholders to understand.

The dashboard helps analyze:

* Customer purchasing behavior
* Revenue trends
* Product performance
* Customer segments
* Subscription behavior
* Discount usage
* Demographic patterns

### 5. Project Documentation & Presentation

The complete analysis was documented in a project report covering the methodology, SQL analysis, dashboard, and business recommendations.

A project presentation was also created using **Gamma** to communicate the analysis and key findings in a concise business-friendly format.

## 💡 Business Recommendations

Based on the analysis, the following recommendations were identified:

* **Increase subscriptions:** Offer exclusive benefits to encourage customers to subscribe.
* **Strengthen customer loyalty:** Introduce loyalty programs for repeat customers.
* **Optimize discount strategy:** Review discount usage to balance sales growth and profitability.
* **Improve product marketing:** Promote highly rated and best-selling products.
* **Target high-value customers:** Focus marketing efforts on high-revenue customer age groups and relevant shipping segments.

## 📈 Key Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Python & Pandas
* SQL Server
* SQL Business Analysis
* Aggregations & Grouping
* Window Functions
* Customer Segmentation
* Feature Engineering
* Data Visualization
* Power BI Dashboard Development
* Business Insights & Recommendations
* Data Storytelling



## 🎯 Project Outcome

This project demonstrates an end-to-end **Data Analytics workflow**, starting from raw data preparation and exploratory analysis, followed by SQL-based business analysis and Power BI visualization.

The project focuses on converting raw customer transaction data into **actionable business insights and recommendations**.
