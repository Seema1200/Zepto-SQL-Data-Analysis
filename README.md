📦 Zepto Data Analysis: My First SQL Project 🎉

Hi there! 👋
Welcome to my first end-to-end data analysis project using SQL.
I built this project to practice my SQL skills and uncover meaningful insights from a realistic dataset inspired by Zepto, a quick grocery delivery platform.

📝 Project Overview

Objective:
To extract actionable business insights from Zepto product data using SQL, helping understand product trends, pricing strategies, and inventory patterns.

Dataset Columns:

sku_id (Primary Key)

category

name

mrp

quantity

discountPercent

availableQuantity

discountedSellingPrice

weightInGms

outOfStock

📄 Presentation of Results:
Zepto_Business_Insights.pdf

⚙️ What I Did (Step by Step)

Set Up the Database

Created a SQL table to hold product data (name, price, category, quantity, weight, etc.)

Data Exploration

Understood data structure

Checked for missing or duplicate values

Counted products by category

Data Cleaning

Removed products with invalid MRP (₹0)

Converted prices from paise to rupees

Handled NULLs and duplicate entries

Analysis with SQL Queries

Top 10 best-value products (highest discounts)

Products with high MRP but out of stock

Revenue estimation by category

Categories with highest average discount

Price per gram comparison for products >100g

Weight categorization (Low / Medium / Bulk)

Total inventory weight by category

📁 Main SQL Script:
zepto_analysis.sql

📊 Key Insights

🛒 Discount Patterns:
Fruits & Vegetables and Meats, Fish & Eggs get higher discounts due to perishability, while premium essentials maintain low discounts to protect margins.

💰 Revenue Trends:
Cooking Essentials, Munchies, and Personal Care bring in the highest estimated revenue, while fresh items contribute the least.

⚖️ Inventory Weight:
Cooking Essentials and Munchies dominate total inventory weight, while Meats, Fish & Eggs are lightest — important for storage planning.

⚡ Best Value:
Staple items like salt and onions have the lowest price per gram, making them the most cost-effective for customers.

📦 Weight Categorization:
Most products are light (<1000g), making them easier and faster to deliver.

💡 What I Learned

Writing SQL queries (SELECT, WHERE, GROUP BY, ORDER BY, CASE, JOIN)

Cleaning and preparing real-world-like data

Performing basic data analysis using SUM, AVG, COUNT

Thinking like an analyst — not just querying, but asking impactful business questions

👩‍💻 About Me

Hi, I’m Seema Kumari — an aspiring Data Analyst who loves solving puzzles and discovering stories hidden in data.
I’m looking for opportunities to learn and grow as a junior data analyst.

📧 Email: seemakri136@gmail.com

💼 LinkedIn: linkedin.com/in/seema-kumari-375763308

💻 GitHub: github.com/Seema1200

✨ Thank you for checking out my project!
I hope it shows my excitement for learning and my potential to contribute as a data analyst.
