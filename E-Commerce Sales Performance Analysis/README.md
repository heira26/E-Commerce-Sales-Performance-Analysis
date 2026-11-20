## E-Commerce Sales Performance Analysis

## 1. Project Overview

This project explores e-commerce sales data to evaluate business performance across product categories, geographic regions, and customer segments.

The objective is to identify sales patterns, compare business performance indicators, and extract actionable insights that can support better business decisions.

## 2. Dataset

- **Source:** Kaggle — E-Commerce Sales Performance Analysis by srisyra02
- **Records:** 5,000 orders
- **Features:** 12 columns
- **Period:** January 2022 – September 2035

The dataset contains information about orders, customers, product categories, regions, payment methods, discounts, delivery times, customer ratings, and revenue.

## 3. Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## 4. Project Workflow

The analysis followed these steps:

1. **Data Overview:** Examined the dataset structure, data types, missing values, and duplicate records.
2. **Data Preparation:** Converted the order date column into a datetime format and validated the result.
3. **Product Category Analysis:** Compared order volume, total revenue, and average revenue per order across product categories.
4. **Regional Analysis:** Evaluated sales performance across geographic regions.
5. **Customer Analysis:** Examined purchasing frequency and revenue concentration among customers.
6. **Key Findings & Limitations:** Summarized the main insights and documented the dataset's limitations.

## 5. Key Business Findings

### Product Category Performance

- Electronics generated the highest total revenue: **1,829,899.22**.
- Electronics also recorded the highest order volume: **1,777 orders**.
- Beauty achieved the highest average revenue per order: **1,059.28**.

### Regional Performance

- West generated the highest total revenue: **1,345,582.16**.
- West recorded the highest order volume: **1,289 orders**.
- West also achieved the highest average revenue per order: **1,043.90**.

### Customer Analysis

- The dataset contains **989 unique customers**.
- The average number of orders per customer was **5.06**.
- The highest number of orders placed by one customer was **14**.
- The top 10 customers contributed approximately **2.91%** of total revenue.

## 6. Data Limitations

Several limitations should be considered when interpreting the results:

- The dataset contains exactly one order per calendar day across the available date range, which limits the realism of time-based analysis.
- The revenue calculation method is not officially documented.
- Customer rating generation methodology is not documented.
- Revenue should not be interpreted as profit because product costs and operating expenses are unavailable.
- The dataset covers an unusually long period, extending to September 2035.

## 7. Conclusion

The analysis identified differences in product category performance, regional sales, and customer purchasing behavior.

Electronics was the leading category in total revenue, while Beauty achieved the highest average revenue per order. West was the strongest-performing region across the three measured indicators.

Customer revenue was not heavily concentrated among the top 10 customers.

These findings provide an overview of business performance while highlighting the importance of considering data quality and limitations before making business decisions.

## 8. Project Files

The main deliverable is a Jupyter Notebook containing the analysis, code, visualizations, and business insights.

---

*This project was developed as part of my Data Analytics portfolio.*
