# Amazon Product Analysis

## 📌 Project Overview

This project analyzes a large Amazon products dataset to explore product pricing, discounts, ratings, customer engagement, and category performance.

The project follows a complete data analysis workflow, starting with data cleaning and preprocessing, followed by exploratory data analysis, data visualization, feature engineering, and interactive dashboard development.

---

## 🎯 Project Objectives

- Clean and preprocess the Amazon products dataset.
- Handle duplicate, missing, and invalid values.
- Analyze and evaluate outliers.
- Explore product pricing and discount patterns.
- Analyze product ratings and customer engagement.
- Investigate relationships between prices, discounts, ratings, and number of ratings.
- Build an interactive dashboard to present key findings.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI
- Jupyter Notebook

---

## 🧹 Data Cleaning & Preprocessing

The dataset was cleaned and prepared for analysis through several steps:

- Removed duplicate records.
- Selected relevant columns for the analysis.
- Cleaned text values and removed unnecessary whitespace.
- Cleaned currency symbols and separators from price columns.
- Converted numerical columns to appropriate data types.
- Identified and handled invalid values.
- Analyzed missing values and applied appropriate imputation methods.
- Investigated outliers in numerical variables.

---

## 🔧 Feature Engineering

Log transformations were applied to highly skewed numerical variables where appropriate to improve the distribution and visualization of the data.

The analysis retained the original variables for business interpretation while using log-transformed variables where they provided better analytical or visual representation.

---

## 📊 Exploratory Data Analysis

The analysis focused on:

- Product distribution across main categories.
- Product distribution across sub-categories.
- Actual and discounted price analysis.
- Discount percentage analysis.
- Product rating analysis.
- Customer engagement based on the number of ratings.
- Relationships between prices, discounts, ratings, and customer engagement.
- Correlation analysis of numerical features.

---

## 📈 Dashboard

An interactive Power BI dashboard was created to provide a clear overview of the Amazon product data.

The dashboard includes:

- Median Actual Price
- Average Rating
- Total Number of Ratings
- Average Discount Percentage
- Number of Products by Main Category
- Total Number of Ratings by Main Category

Users can interact with the dashboard using:

- Main Category
- Sub Category
---

## 🔍 Key Analysis Areas

The project explores important business questions such as:

- Which product categories contain the most products?
- Which categories have the highest median prices?
- How are discounts distributed across categories?
- Which categories receive the most customer ratings?
- Is there a relationship between product discounts and customer engagement?
- How do product ratings vary across categories and sub-categories?

---

## 📂 Project Structure

```text
amazon-product-analysis/
│
├── Amazon_Product_Analysis.ipynb
│
├── README.md
│
└── images/
    └── amazon_dashboard.png
