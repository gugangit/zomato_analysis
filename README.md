# zomato_analysis
# Zomato Data Analysis (SQL)

Exploratory data analysis of a Zomato restaurant dataset (~9,551 records, 141 cities, 15 countries) using MySQL and MySQL Workbench.

## Objectives
- Inspect table structure and check RestaurantID for duplicates
- Clean the data: drop redundant columns, validate city names (TRIM, SOUNDEX, REGEXP)
- Map country codes to country names with a lookup table and JOIN
- Compute a rolling restaurant count per city using a window function
- Build statistical summaries and a rating-category column (CASE)
- Analyse country distribution, online delivery, Indian restaurants, top cities, cuisines, and table booking
- Recommend moderately priced, highly rated restaurants, including a Kolkata pick

## Key Findings
- India accounts for 90.59% of listings (8,652 restaurants); the US is second at 4.54%
- Online delivery appears only in the UAE (46.67%) and India (28.01%)
- New Delhi has the most listings (5,473), followed by Gurgaon and Noida
- About 63.56% of restaurants are rated average or poor; only 3.15% are excellent
- Connaught Place restaurants with table booking average 3.82 rating vs 3.61 without
- Top Kolkata recommendation: India Restaurant (4.6 rating, 1,219 votes)

## SQL Concepts Used
Aggregations, GROUP BY / HAVING, CASE expressions, JOINs, subqueries, window functions (running total), ALTER / UPDATE, string functions, REGEXP

## Tools
MySQL | MySQL Workbench

