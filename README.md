# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

**Customer Shopping Behavior Analysis** is a data analytics project focused on understanding customer purchasing patterns, spending behavior, product preferences, customer segments, discounts, shipping methods, and subscription behavior.

The project analyzes a dataset containing **3,900 customer purchases and 18 features** to uncover meaningful business insights and support data-driven decision-making.

## 🎯 Project Objectives

* Analyze customer purchasing and spending patterns
* Understand revenue by customer demographics
* Identify top-rated products
* Segment customers based on purchasing behavior
* Analyze the impact of discounts and shipping methods
* Compare subscribers and non-subscribers
* Identify high-revenue categories and age groups
* Generate actionable business recommendations

## 📊 Dataset

| Attribute    | Details                             |
| ------------ | ----------------------------------- |
| Records      | 3,900                               |
| Features     | 18                                  |
| Missing Data | 37 null values in Review Rating     |
| Data Type    | Customer shopping and purchase data |

The dataset contains information related to **customer demographics, purchase details, behavior, and shipping**.

## 🧹 Data Preparation

The following data preparation and feature engineering steps were performed:

1. Loaded and explored the dataset using descriptive analysis.
2. Identified missing values and handled **Review Rating** nulls using the median by category.
3. Standardized column names using **snake_case**.
4. Created new features:

   * `age_group`
   * `purchase_frequency_days`
5. Removed `promo_code_used` because it was redundant with `discount_applied`.
6. Loaded the cleaned dataset into **PostgreSQL** for structured SQL analysis.

## 🗄️ Database & SQL Analysis

The cleaned data was integrated with **PostgreSQL** to perform business-oriented SQL analysis.

Key analyses included:

* Revenue by gender
* Average purchase amount
* Average product rating
* Top-rated products
* Discount analysis
* Subscription analysis
* Customer segmentation
* Category-wise revenue
* Age-group analysis
* Shipping method analysis

## 📈 Key Insights

### 💰 Revenue & Demographics

* **Male revenue:** $157,890
* **Female revenue:** $75,191
* **Overall average purchase:** $59.76
* **Average rating:** 3.75

### ⭐ Top-Rated Products

| Product | Average Rating |
| ------- | -------------: |
| Gloves  |           3.86 |
| Sandals |           3.84 |
| Boots   |           3.82 |
| Hat     |           3.80 |
| Skirt   |           3.78 |

### 🚚 Shipping Analysis

* Express shipping average purchase: **$60.48**
* Standard shipping average purchase: **$58.46**

### 🎟️ Discount Analysis

Products with high discount rates included:

* Hat
* Sneakers
* Coat
* Sweater
* Pants

These products had approximately **47–50% discount rates**.

### 👥 Customer Segmentation

Customers were segmented into three groups based on purchasing behavior:

| Segment   | Customers | Description                  |
| --------- | --------: | ---------------------------- |
| Loyal     |     3,116 | Frequent buyers              |
| Returning |       701 | Repeat, mid-frequency buyers |
| New       |        83 | Early-engagement customers   |

### 🔔 Subscription Analysis

* Subscribers: **1,053**
* Non-subscribers: **2,847**
* Average subscriber spend: **$59.49**
* Average non-subscriber spend: **$59.87**

## 💡 Business Recommendations

### 1. Boost Subscriptions

Promote exclusive subscription benefits to encourage more customers to sign up.

### 2. Strengthen Loyalty Programs

Reward repeat customers to encourage retention and expand the loyal customer segment.

### 3. Review Discount Strategy

Balance discount-driven sales growth with profitability and margin control.

### 4. Product Positioning

Promote highly rated and best-selling products to increase customer engagement.

### 5. Targeted Marketing

Focus marketing campaigns on high-revenue age groups and customers using express shipping.

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **PostgreSQL**
* **SQL**
* **Data Cleaning**
* **Feature Engineering**
* **Exploratory Data Analysis (EDA)**

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Exploration
     ↓
Data Cleaning
     ↓
Feature Engineering
     ↓
PostgreSQL Integration
     ↓
SQL Analysis
     ↓
Customer Segmentation
     ↓
Business Insights
     ↓
Recommendations
```

## 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── dataset/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── customer_behavior_queries.sql
│
├── presentation/
│   └── customer_behavior_analysis.pdf
│
└── README.md
```

## 📌 Conclusion

This project demonstrates how customer transaction data can be transformed into meaningful business insights using **data cleaning, feature engineering, PostgreSQL, and SQL analysis**.

The analysis helps identify customer segments, product preferences, revenue patterns, discount trends, shipping behavior, and subscription opportunities that can support better marketing and customer-retention strategies.



**Skills Demonstrated:** Python • Pandas • SQL • PostgreSQL • Data Analysis • Data Cleaning • Feature Engineering • Customer Segmentation
