# Diwali Sales Exploratory Data Analysis (EDA)

## 📌 Project Overview
The objective of this project is to analyze a Diwali sales dataset to uncover demographic purchasing patterns, evaluate regional and occupational sales performance, and provide actionable, data-driven recommendations to optimize future targeted marketing campaigns and inventory planning.

## 🛠️ Tools & Methodology
* **Tech Stack:** Python, Pandas, NumPy, Matplotlib, Seaborn.
* **Data Cleaning:** Standardized column names, handled null values, and removed irrelevant columns to ensure mathematical accuracy.
* **Feature Engineering:** Applied **Median Target Encoding** to categorical variables (such as Product Category and State) to translate text labels into financial weights, enabling accurate correlation matrix calculations.
* **Visualizations:** Deployed multivariate visualizations including boxplots to identify spending outliers and dual-axis combo charts to simultaneously compare total revenue against order volume.

## 📊 Key Business Insights
1. **The Volume vs. Value Dynamic:** The IT Sector, Healthcare, and Aviation dominate overall sales volume. However, the Chemical sector yields the highest average amount per individual order.
2. **Demographic Dominance:** Un-married females are the core customer base, driving the vast majority of total sales. However, median individual spending remains highly consistent across all genders and marital statuses. The revenue gap is driven entirely by transaction volume, not individual purchasing power.
3. **Age & Spending Behavior:** The 26-35 age group is the most lucrative segment. Boxplot distributions reveal that while baseline median spending is uniform across age groups, high-ticket outlier purchases are primarily driven by younger and middle-aged demographics.
4. **Category & Regional Leaders:** Food, Clothing, and Electronics lead total sales. Geographically, Uttar Pradesh, Maharashtra, and Karnataka are the highest-performing states.

## 💡 Business Recommendations
* **Targeted Ad Spend:** Marketing budgets should be heavily weighted toward un-married women aged 26-35 working in IT, Healthcare, and Aviation. 
* **Premium Upselling:** Design "premium" product bundles specifically targeted at professionals in the Chemical sector to capitalize on their high average order value.
* **Supply Chain Focus:** Prioritize warehouse inventory for Food, Clothing, and Electronics in fulfillment centers servicing Uttar Pradesh and Maharashtra.

