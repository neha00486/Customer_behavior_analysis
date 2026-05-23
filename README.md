# Customer Shopping Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior using transactional data to identify customer trends, spending patterns, subscription behavior, and product preferences.

The project includes:

* Data Cleaning and Analysis using Python
* Business Query Analysis using SQL (PostgreSQL)
* Interactive Dashboard using Power BI

---

## Tools & Technologies

* Python
* Pandas
* PostgreSQL
* SQLAlchemy
* Power BI

---

## Dataset Information

* Total Records: 3900
* Total Columns: 18

### Key Features

* Customer demographics
* Purchase details
* Subscription status
* Review ratings
* Shipping type
* Purchase frequency
* Discounts and promo codes

---

## Project Workflow

### 1. Data Cleaning & Preprocessing (Python)

* Loaded dataset using Pandas
* Checked missing values
* Filled missing `review_rating` values using category median
* Converted column names to snake_case
* Created:

  * `age_group`
  * `purchase_frequency_days`
* Removed redundant columns

---

### 2. SQL Analysis (PostgreSQL)

Performed business analysis queries such as:

* Revenue by gender
* Subscribers vs non-subscribers
* Top-rated products
* Customer segmentation
* Revenue by age group
* Shipping type comparison
* Repeat customer analysis

---

### 3. Power BI Dashboard

Built an interactive dashboard to visualize:

* Revenue by category
* Revenue by age group
* Sales by age group
* Subscription analysis
* Customer insights

---

## Key Insights

* Clothing category generated the highest revenue
* Loyal customers contributed significantly to total sales
* Subscribers showed higher average spending
* Certain products heavily depended on discounts
* Senior and middle-aged groups contributed high revenue

---

## Business Recommendations

* Improve customer loyalty programs
* Promote subscription benefits
* Focus marketing on high-revenue age groups
* Highlight top-rated products in campaigns
* Optimize discount strategies

---

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
├── notebooks/
├── sql_queries/
├── powerbi_dashboard/
├── README.md
```

---

## Future Improvements

* Add predictive analytics
* Build recommendation system
* Deploy dashboard online
* Add real-time sales tracking

---

