# Analysis-of-Amazon-customers-review
This repository briefly describes analysis of Amazon products and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement.

# 📊 PRODUCT ANALYTICS DASHBOARD


This project provides a comprehensive analysis of product data, focusing on pricing, ratings, discount behavior, and category-level trends. Analyzing Amazon products' performance and the need to explore customer review data to uncover key insights such as top-selling products, distribution of ratings, highlight low-reviewed products, highest discounted products and sales trend using Data analysis tools such as Excel for creating pivot tables, data exploration and to produce an interactive dashboard that highlights these findings.

## 🔍 OBJECTIVES & KEY QUESTIONS EXPLORED:


- Top-Rated Products – Identify products with the highest average user ratings.

- Most Reviewed Products – Highlight the most reviewed and possibly most popular products.

- Products with ≥50% Discount – Count heavily discounted items to analyze aggressive pricing.

- Low-Review Products (<1,000 reviews) – Flag less-engaged or newer products.

- Top 5 Products (Rating + Reviews) – Rank products using a weighted score of rating and engagement.


## 📈 TOOLS USED:


- Excel for pivot tables, slicers, and dashboard visualizations

- Data Cleaning: COUNTIF, CEILING, helper columns

- Interactive Dashboards: Pivot Charts + Slicers for dynamic filtering


## DATA SOURCE

The Primary Data used here is DSA Data Analysis capstone project.xlsx for Amazon case study

## DATA CLEANING AND PREPARATIONS

At the preliminary phase of the data cleaning and preparations , I performed the following actions;

### i. Data loading and inspection

Data loading and inspection are crucial steps in data analysis, ensuring accuracy and reliability. In Excel, data is loaded through importing Excel file. Once loaded, data inspection involves checking for missing values, outliers, and data types using Excel's Data Validation. Power Query in Excel improves data inspection through interactive visualizations, allowing users to quickly identify trends and discrepancies.

### ii. Data cleaning and formatting

Excel was used in cleaning data which involves removing duplicates (using "Remove Duplicates" tool), and formatting data (using Text to Columns, Trim, and PROPER functions). Power Query in Excel was also used to "Transform" and remove blanks, trim text, and change data types. Excel's "Data Validation" tools help identify inconsistencies and errors.

## EXPLORATORY DATA ANALYSIS
This involves exploring of the data to answer some questions such as;

- Top-Rated Products.

- Most Reviewed Products.

- Products with ≥50% Discount

- Low-Review Products (<1,000 reviews)

- Top 5 Products (Rating + Reviews)

![image](https://github.com/user-attachments/assets/c4689a03-7003-49a7-937a-9c94d501bb94)


![image](https://github.com/user-attachments/assets/8262926f-5e91-4bf1-8308-e4699bd2d972)


![image](https://github.com/user-attachments/assets/8f868d25-556a-4a24-a66e-bae44b51b0c3)

 

## DATA ANALYSIS

INSIGHTS

i. Certain categories consistently offer higher discounts, but this does not always correlate with higher ratings.

ii. Products in mid-price ranges (₹200–₹500) are most common.

iii. Top-rated products are not always the most reviewed, indicating potential for under-discovered quality products.


Below is a picture of data visualization using pivot tables/charts in Excel

![image](https://github.com/user-attachments/assets/ce9eaf09-54f3-4d14-b92e-6a8f9e933f50)

![image](https://github.com/user-attachments/assets/0bc36748-60be-4197-b23b-f1de368b9d3f)

![image](https://github.com/user-attachments/assets/fd33c741-934e-405e-8e8b-12355d6bf68a)

![image](https://github.com/user-attachments/assets/50ed8970-d4f5-402c-8775-ba2252cb373a)



## ✅ RECOMMENDATION:

1. Attention should be prioritised to products such as kitchen heating equipments which had high rating count.
2. The Top 10 Products with the highest number of reviews should be focused on.
