# -Market-Basket-Analysis-Exploratory-Association-Rule-Mining
This project performs Market Basket Analysis using a transactional dataset from Kaggle. The goal is to uncover purchasing patterns, identify top-selling products, and derive association rules to help understand customer buying behaviour. The project is suitable for business intelligence and recommendation system applications.

# 📌 Dataset
Source: Kaggle - Market Basket Analysis Dataset

Format: .csv, with semicolon (;) separators

Size: ~500K+ rows of retail transactions

# 📊 Project Highlights
1. Data Cleaning & Preprocessing

   - Parsed datetime and standardized formats

   - Removed missing and invalid entries (e.g., negative quantity/price)

   - Converted numeric columns (e.g., Price) to the correct format

   - Created TotalSales and Year/Month features

2. Exploratory Data Analysis (EDA)

   - Monthly sales trends over time

   - Top-selling products by quantity and revenue

   - Sales distribution across countries

   - Most popular items per country

3. Association Rule Mining

   - One-hot encoded item baskets by transaction (BillNo)

   - Used Apriori algorithm to identify frequent itemsets

   - Extracted rules with high lift and confidence
  


# 📦 Technologies Used
Python, Jupyter Notebook

pandas, matplotlib, seaborn for data wrangling & visualization

mlxtend for Apriori and association rule mining
