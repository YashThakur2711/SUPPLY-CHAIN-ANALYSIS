# SUPPLY-CHAIN-ANALYSIS

**Project Title - Supply Chain Analysis**

**📌 Overview**

This project focuses on analyzing supply chain and inventory data to optimize stock levels, reduce stockouts, and prevent overstocking. It applies analytical methods using Python for data preprocessing, exploratory data analysis (EDA), and visualization to gain actionable insights into order patterns, stock behavior, and transportation nodes.

**🔍 Problem Statement**

Businesses often face challenges like stock-outs and excess inventory due to inefficient manual tracking and lack of predictive insights. This project aims to analyze sales, stock, and transportation data to identify optimization opportunities for inventory planning and order fulfillment.

**📊 Tools & Technologies Used**

Python (Pandas, NumPy, Seaborn, Matplotlib)

Jupyter Notebook

Visual Studio Code

**📁 Dataset**

The dataset is sourced from a CSV file, available on Kaggle for supply chain analysis. It includes:

Product types

Sales orders

Stock levels

Transport modes

Revenue generated


Dataset Name: supply_chain_data.csv
Source: https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis

**🧠 Approach**

Data Cleaning: Handled missing values, renamed columns for clarity, removed irrelevant fields

Exploratory Data Analysis (EDA): Analyzed trends in product demand, stock levels, and transport efficiency

Visualization: Used bar plots, scatter plots, and box plots to reveal insights

Segmented Analysis: Performed mode-wise, product-type, and stock vs order comparisons,supplier wise

Insight Generation: Interpreted visuals to form recommendations for inventory planning

**📈 Key Features**

📊 Stock vs Order Scatter Plot: Shows relationship between stock level and customer orders

🚚 Transport Mode Analysis: Evaluates which transport points handle the most average shipping value

📦 Product Type Sales Breakdown: Identifies high-performing products

💸 Revenue Analysis: Highlights revenue by region type

📌 ABC Classification Potential: Provides a base for future ABC inventory classification

**✅ Results**

High number of orders are associated with low stock in several product types — indicating risk of stock-outs

Revenue contribution is skewed toward a few product types — candidate for A class in ABC classification

Scatter plots revealed that some products have high stock but low orders, highlighting overstock scenarios

Insights can be used to set reorder points (ROP) and economic order quantities (EOQ) in future iterations
