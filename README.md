# Walmart-Sales-Data-Analysis-using-SQL
📊 **End-to-End Retail Data Analysis Project using MySQL**

This project focuses on analyzing Walmart Sales Data using Structured Query Language (SQL).
The goal is to extract valuable business insights about sales performance, customer behavior, and product profitability.


📁 **Project Overview**

In this project, I built a complete SQL-based data analysis pipeline — starting from database creation and data cleaning to feature engineering and exploratory analysis.

The analysis answers key business questions related to Product, Sales, and Customer performance, helping to identify trends, patterns, and areas for improvement.


🧱 **Database Design**

The dataset was obtained from the Kaggle Walmart Sales Forecasting Competition. This dataset contains sales transactions from a three different branches of Walmart, respectively located in Mandalay, Yangon and Naypyitaw. The data contains 17 columns and 1000 rows.

⚙️ **Approach Used**

**1️⃣ Data Wrangling**
	•	Built the database and table structure with all fields as NOT NULL to ensure data integrity.
	•	Checked for missing or null values.
	•	Ensured consistency in data types (decimal for monetary values, float for VAT, etc.).

**2️⃣ Feature Engineering**

To enhance the dataset for deeper analysis, new columns were created using SQL functions:

time_of_day - Derived from time column (CASE WHEN) - Classifies each sale into Morning, Afternoon, or Evening

day_name - Extracted using DAYNAME(date) - Identifies the day of the week for trend analysis

month_name - Extracted using MONTHNAME(date) - Helps analyze monthly revenue and COGS trends

These engineered features helped uncover temporal patterns in sales.

**3️⃣ Exploratory Data Analysis (EDA)**

EDA was performed through a series of SQL queries addressing Product, Sales, and Customer dimensions.

**Business Questions To Answer**

**Generic Question**

1. How many unique cities does the data have?
2. In which city is each branch?

**Product**

1. How many unique product lines does the data have?
2. What is the most common payment method?
3. What is the most selling product line?
4. What is the total revenue by month?
5. What month had the largest COGS?
6. What product line had the largest revenue?
7. What is the city with the largest revenue?
8. What product line had the largest VAT?
9. Which branch sold more products than average product sold?
10. What is the most common product line by gender?
11. What is the average rating of each product line?

**Sales**

1. Number of sales made in each time of the day per weekday
2. Which of the customer types brings the most revenue?
3. Which city has the largest tax percent/ VAT (Value Added Tax)?
4. Which customer type pays the most in VAT?
   
**Customer**

1. How many unique customer types does the data have?
2. How many unique payment methods does the data have?
3. What is the most common customer type?
4. Which customer type buys the most?
5. What is the gender of most of the customers?
6. What is the gender distribution per branch?
7. Which time of the day do customers give most ratings?
8. Which time of the day do customers give most ratings per branch?
9. Which day fo the week has the best avg ratings?
10. Which day of the week has the best average ratings per branch?




