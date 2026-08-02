# 📊 Project Overview

This project analyzes historical sales data to evaluate product performance, pricing strategy, profitability, and demand responsiveness. The objective is to identify key business insights, assess promotional effectiveness, and provide data-driven recommendations through exploratory data analysis (EDA) and KPI visualizations.

# 🎯 Business Objectives
The analysis aims to answer the following questions:

- How have sales performed over time?
- What is the average selling price of the product?
- How profitable is the product?
- Do promotions increase demand?
- Is customer demand price-sensitive?
- What pricing strategies can improve business performance?

# 📂 Dataset

The dataset contains daily transactional data from January 2014 to December 2016.

Variables:
- Variable	DescriptionDate	Transaction date
- Sales	Daily sales revenue (R)
- Cost Of Sales	Daily cost associated with sales
- Quantity Sold	Number of units sold

# 🛠️ Tools & Technologies
- Python : Pandas, NumPy and Matplotlib


# 📈 Key Performance Indicators (KPIs)

The following KPIs were calculated:

1. Sales Price Per Unit

   Selling Price Per Unit = Sales​/Quantity Sold
​

Measures the average selling price of each unit sold.

2. Gross Profit Percentage

   GP% = ((Sales−Cost of Sales)/Sales)×100

Measures profitability after accounting for direct costs.

3. Gross Profit Per Unit

Evaluates profitability on a per-unit basis.

4. Price Elasticity of Demand

   PED=%ΔQuantity/%ΔPricePED ​

Measures customer responsiveness to price changes.

# 📊 Visualizations Included
## 1. Daily Sales Trend

Purpose
- Evaluate sales performance over time.
- Identify spikes and periods of strong demand.

### Key Insight

- Daily sales are highly volatile.
- Revenue peaks exceeded R800,000 during certain periods.
- 2014 recorded the strongest sales performance.

## 2. Daily Selling Price Trend

Purpose
- Track pricing strategy over time.

### Key Insight

- Selling prices increased from approximately R32 in 2014 to R44 in 2016.
- Multiple promotional pricing periods are evident.

## 3. Daily Gross Profit (%) Trend

Purpose
- Monitor profitability.

### Key Insight

- Gross Profit % fluctuates significantly.
- Several periods generated negative margins.
- Profitability improved considerably during 2016.

## 4. Monthly Revenue Trend

Purpose
- Assess long-term revenue performance.

### Key Insight

- Revenue fluctuates across months.
- Peak periods correspond with promotional activity.

## 5. Quantity Sold Trend

Purpose
- Evaluate customer demand.

### Key Insight

- Sales volume is highly responsive to pricing changes.
- Promotions typically increase quantities sold.

## 6. Price vs Quantity Sold Analysis

Purpose
- Determine demand elasticity.

### Key Insight

- A negative relationship exists between price and demand.
- Customers purchase more units when prices decrease.

## 7. Promotion Analysis

Purpose
- Evaluate promotional effectiveness.

### Key Insight

- Promotional pricing generally increases sales volume.
- Promotions must be carefully managed to protect margins.

## 8. Correlation Heatmap

Purpose
- Identify relationships among key business variables.

### Key Insight

- Revenue is highly influenced by quantity sold.
- Selling price has a measurable impact on demand.

# 🔍 Major Findings
1. Customer Demand is Price Sensitive
    - The analysis indicates that customer purchasing behavior is strongly influenced by price changes.
    - Lower product prices generally lead to higher sales volumes, suggesting elastic demand.

2. Promotions Increase Sales Volume
    - Promotional periods resulted in significant increases in quantities sold.
    - While promotions are effective in boosting demand, excessive discounting can negatively affect profitability.

3. Revenue Growth is Volume Driven
    - Revenue increases are primarily associated with higher quantities sold rather than higher selling prices.

4. Profitability Requires Improvement
    - The average Gross Profit Percentage remained low throughout several periods.
    - Negative gross margins indicate that certain promotions may have reduced profitability below sustainable levels.

5. Pricing Strategy Improved Over Time
    - The company gradually increased selling prices between 2014 and 2016, leading to improved profitability in later years.

# 📋 Business Recommendations
Recommendation 1: Continue Strategic Promotions
  - Promotions should remain part of the pricing strategy because they successfully stimulate customer demand.

Recommendation 2: Monitor Gross Margins
  - Track Gross Profit % alongside sales volume to ensure increased sales translate into higher profitability.

Recommendation 3: Optimize Pricing
  - Use price elasticity analysis to identify the optimal price point that maximizes both revenue and profit.

Recommendation 4: Investigate Loss-Making Periods
  - Review periods where Gross Profit % fell below zero to understand the root causes of losses.

Recommendation 5: Develop a KPI Dashboard
- Implement a dashboard that monitors:

    - Total Revenue
    - Quantity Sold
    - Average Selling Price
    - Gross Profit %
    - Monthly Sales Trend
    - Promotion Effectiveness
    - Price Elasticity

Sales Dashboard: https://case-study-companion-88.lovable.app/

# 📌 Conclusion

The analysis demonstrates that the product exhibits highly elastic demand, with customers responding strongly to changes in price. Promotional pricing effectively drives sales volume but can reduce profitability if not carefully managed.

A balanced pricing strategy that considers both customer demand and gross profitability will be critical to maximizing long-term business performance.

👨‍💻 Author

Boitumelo Ramogayane
| Data Analytics Enthusiast | Python | SQL | Power BI

# ⭐ Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Business Analytics
- Sales Performance Analysis
- KPI Development
- Data Visualization
- Python Programming
- Business Insights & Recommendations
