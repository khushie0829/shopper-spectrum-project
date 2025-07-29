# shopper-spectrum-project
This project aims to explore customer behavior, segment them based on purchase patterns using RFM Analysis, and build a product recommendation engine to enhance customer experience and business profitability. The approach involves a mix of Exploratory Data Analysis (EDA), unsupervised machine learning (clustering), and association rule mining for product recommendations.

💻 Tech Stack
Language: Python 🐍
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Plotly, mlxtend
Tools: Jupyter Notebook

ML Techniques: KMeans Clustering, Association Rule Mining (Apriori)
Type of Project: Unsupervised Learning + EDA + Recommendation System

🧾 Dataset Info
Source: UCI/Kaggle Online Retail Dataset
Duration: One year of transactional data from a UK-based e-commerce store

Attributes:
InvoiceNo, StockCode, Description
Quantity, UnitPrice, InvoiceDate
CustomerID, Country

Problem Statement
How can we:
Identify valuable customers?
Target them differently based on their behavior?
Recommend products based on historical co-purchase patterns?
Maximize revenue by understanding purchase dynamics?

✅ Solution Approach
🔍 1. Data Cleaning
Removed nulls, duplicates, canceled orders
Handled negative values and type conversion

📊 2. Exploratory Data Analysis (EDA)
Univariate, Bivariate & Multivariate visualizations (15+)
Extracted trends in quantity, price, location, time, and sales

📦 3. RFM Segmentation
Recency: Days since last purchase
Frequency: Number of purchases
Monetary: Total revenue per customer
Used KMeans for clustering based on RFM metrics

🎯 4. Recommendation System
Association Rule Mining using Apriori
Recommended items with highest lift/support for each segment

📈 Exploratory Data Analysis (EDA)
Structured as per UBM (Univariate, Bivariate, Multivariate) with insights for each chart.

Sample Charts:
Top countries by revenue
Sales trend over months
Product-wise contribution
Quantity vs Price heatmaps
Recency vs Frequency plots

Each visualization includes:
📌 Why the chart was chosen
💡 Insight derived

📊 Business implication
📊 RFM Analysis & Clustering
Normalized RFM features
Clustered customers using KMeans
Segments like:
Loyal Customers
Recent High Spenders
At-Risk Customers
Occasional Buyers

🛍️ Product Recommendation System
Generated association rules (lift, confidence, support)
Recommended most commonly co-purchased items
Segment-based personalized recommendation strategy

💡 Business Impact
Helps in retargeting dormant or churned users
Enables personalized marketing & promotions
Drives revenue by promoting co-purchased items
Better customer retention and engagement
