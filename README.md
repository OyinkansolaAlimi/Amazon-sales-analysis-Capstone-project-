# 📊 Amazon-sales-analysis-Capstone-project
This is a prerequisite for certification after three months of learning data analysis with the incubator hub

## 📌 Project title 
📊 **Amazon sales data analyis**

##  📂 Project Overview

This project focuses on analyzing product data from Amazon's marketplace to uncover patterns in pricing, discounts, ratings, patterns, customer engagement, and category insights. Using Excel's Pivot Tables, Power Query, and custom formulas, I transformed and visualized the data to extract insights that can guide strategic decisions in product improvement, marketing strategies, and customer engagement. 

## 📁 Dataset Description
The dataset contains information scraped from Amazon product pages, including: 
- Product details: name, category, price, discount, and ratings 
 - Customer engagement: user reviews, titles, and content 
 - Each row represents a unique product, with aggregated reviewer data stored as comma-separated values

**Total Records: 	1,465 rows**       
**Total Fields: 16 columns** 

## Data Preparation Cleaning and Transformation
Before analysis, the following transformations were done in Power Query and Excel:
 - Extracting the main category from multi-level category strings
 - Creating a Conditional Column; price bucket and Customn column; Potential Revenue Column
 - Removing duplicate entries and addressing missing vakues through Excel's data validation and filtering tools
 - Standardizing data formats and converting currency values to consistent unit
   
## 🛠 Tools & Techniques Used
- 📌 **Excel Features:**
  - Pivot Tables (with Distinct Count)
  - Power Query Editor (for transformation)
  - Slicers for interactivity
  - Conditional formatting
  
## Exploratory Data Analysis EDA
EDA involved asking several business questions from the data set, such as;

#### 🧠 Key Business Questions Answered
1. What is the average discount percentage by product category?
2. How many products are listed under each category?
3. What is the total number of reviews per category?
4. Which products have the highest average ratings?
5. What is the average actual vs discounted price by category?
6. Which products have the highest number of reviews?
7. How many products have a discount of 50% or more?
8. What is the distribution of product ratings?
9. What is the potential revenue (actual_price × rating_count) by category?
10. How many unique products fall into each price bucket?
11. How does discount level relate to rating?
12. How many products have fewer than 1,000 reviews?
13. Which categories offer the highest discounts?
14. What are the top 5 products by combined rating and reviews?

#### 📌 Key Metrics and Insights
| Metric | Insight |
|--------|---------|
| **Top-performing products** | Had rating above 4.5 and over 10,000 reviews |
| **High discounts** | Mostly found in Electronics |
| **Low-engagement zone** | Products with <1,000 reviews and low ratings |
| **Revenue concentration** | Driven by high-priced items with high review counts |
| **Price Buckets** | ₹200–₹500 products were most common but contributed less to revenue than high-end items but revenue was skewed towards the >₹500 segment, emphasizing that premium products drive more revenue per unit |
| **Discount segments** | Over 25% of the products offered discounts of 50% or more, possibly to stay competitive or to push slow-moving inventory | 

---
 #### 🔵 Visual Dashboard Components
  - Bar charts comparing Actual price vs Discount Price
  -  Pie chart showing product distribution by price bucket rrange
  -  Column chart showing Average discount by category
  -  Line Chart for identifying Products rating distribution

 🎛️ **Slicers**:
  - Category
  - Price Bucket

### Dashboard



    ins8ghts
    recommendationa

