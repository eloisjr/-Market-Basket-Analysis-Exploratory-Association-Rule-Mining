# Market-Basket-Analysis-Exploratory-Association-Rule-Mining
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

# 💼 Business Insights Summary
## 🌍 Top-Selling Items by Country
The analysis reveals which products are most favored in different countries, providing valuable input for regional marketing and inventory strategies:

- Australia: MINI PAINT SET VINTAGE

- Austria: SET 12 KIDS COLOUR CHALK STICKS

- France: RABBIT NIGHT LIGHT

- Japan: RABBIT NIGHT LIGHT

- Germany: ROUND SNACK BOXES SET OF4 WOODLAND

- Italy: FEATHER PEN, HOT PINK

- United Kingdom: PAPER CRAFT , LITTLE BIRDIE with 80,995 units sold

## 📝 Insight: 
Some products (e.g., RABBIT NIGHT LIGHT) are top sellers across multiple countries, suggesting potential for broader regional campaigns or bundled promotions.

## 📊 Quantity-Driven Regional Demand
- Products with the highest total quantity sold vary by country, highlighting localized preferences.

- The UK dominates in quantity, likely due to a larger customer base.

- Smaller yet consistent sales in countries like Switzerland and Portugal can help identify niche markets.

## 📌 Actionable Tip: Tailor marketing efforts and product recommendations per region to maximize conversion rates.

### 🔄 Market Basket Analysis (Association Rules)


If a customer buys: ROSES REGENCY TEACUP AND SAUCER + PINK REGENCY TEACUP AND SAUCER

Then they are likely to also buy: GREEN REGENCY TEACUP AND SAUCER

Confidence: 90.3% | Lift: 18.16

## 🚀 Insight:

High confidence and lift indicate strong purchasing relationships between these items.

Use this to drive:

Cross-sell strategies ("Frequently bought together")

   - Product bundles

   - Targeted recommendations
  


# 📦 Technologies Used
Python, Jupyter Notebook

pandas, matplotlib, seaborn for data wrangling & visualization

mlxtend for Apriori and association rule mining
