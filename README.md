# 🍕 Pizza Sales Analysis (SQL Project)
A complete end-to-end SQL project analyzing pizza sales, revenue, ordering trends, and customer behavior using a relational database.
This project demonstrates data exploration, joins, subqueries, CTEs, and window functions.

# 🛠️ Tech Stack

SQL (MySQL)

• Relational database design
• Window functions
• CTEs
• Subqueries
• Joins & Aggregations

# 🧱 Database Schema

The project uses 4 main tables:

1. pizza_types – pizza categories & ingredients
2. pizzas – pizza sizes & prices
3. orders – order timestamps
4. order_details – quantity and pizza-level details

# 🎯 Objectives

✔ Perform data cleaning & exploration
✔ Analyse sales, pricing, and category behavior
✔ Generate insights on best/worst performing items
✔ Apply analytical SQL (CTE, Window Functions, Subqueries)

# 🔍 Analysis Highlights
# Phase 1 – Data Exploration
 
• List unique pizza categories
• Replace missing or NULL ingredients
• Identify pizzas missing prices
• Inspect orders on a specific date
• Explore price distribution of pizza sizes
 

# Phase 2 – Filtering & Business Queries

• Pizzas sold in specific price ranges
• Chicken-based pizzas using LIKE search
• Orders placed after peak hours (post 8 PM)
• Filter pizzas by sizes (L, XL)
• Orders on specific business dates


# Phase 3 – Sales Performance Analysis

• Total pizza quantity sold
• Average pizza price
• Total order value per order
• Sales by category
• Pizzas with zero sales
• Price comparison between pizza sizes (SELF JOIN)
• Revenue ranking using window functions

# 📊 Key Insights

🍕 1. Sales Volume Milestone

49,574 total pizzas sold → strong demand and stable daily operations.

💰 2. Effective Pricing Strategy

Avg. pizza price: $16.44
→ Mid-range pricing is the core driver of volume.

🏆 3. High-Value Opportunities

Orders #18845 and #10760 generated exceptionally high revenue.
→ Potential for corporate, bulk, or event-based order packages.

📉 4. Category Growth Potential

Chicken pizzas have the lowest sales volume.
→ But surprisingly, they generate the highest revenue through premium products.

✂️ 5. Inventory & Menu Optimization

Five pizzas had zero sales:

Big Meat (L, M)

Five Cheese (M, S)

Four Cheese (S)

→ Removing unused items will reduce inventory cost and improve menu clarity.

🏷️ 6. Pricing Opportunity

The Large Hawaiian ($16.50) is $4 cheaper than similar category pizzas.
→ A small price adjustment could increase annual profit significantly.

💎 7. Premium Product Strategy

XXL Greek ($35.95)

Brie Carre ($23.65)

These "luxury pizzas" help drive higher cart value.
→ Useful for premium combos or festive promotions.

📊 8. Top Sellers

Only two pizzas dominate Chicken category sales:

Thai Chicken

Southwest Chicken

→ Ads should highlight these winners instead of low-selling variants.

🍽️ 9. Customer Size Preferences

Small sizes → Heavy meat lovers

Large sizes → Flavor-rich pizzas like Thai Chicken

→ Dynamic website images based on size selection can improve conversions.

👑 10. Revenue Champions

Only 3 pizzas cross $40,000+ revenue:

Thai Chicken

BBQ Chicken

California Chicken

→ These are the core revenue drivers of the brand.



