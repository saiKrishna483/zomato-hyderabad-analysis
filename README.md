# Zomato Hyderabad Restaurants: Python Data Analysis

Cleaning and exploring a messy Zomato dataset of 105 Hyderabad restaurants and about 10,000 customer reviews, using Python.

## Dataset
"Zomato Restaurants Hyderabad" from Kaggle (two CSV files: restaurant details and customer reviews).

## Tools
Python, pandas, matplotlib, seaborn, Jupyter Notebook

## What I did
1. Loaded and inspected both tables (size, data types, missing values, duplicates)
2. Cleaned the data: removed 36 duplicate reviews, handled missing and invalid ratings, converted Cost, Rating and Time to proper types, and split reviewer info into two number columns
3. Joined the two tables on restaurant name
4. Answered six questions with charts: rating distribution, top-rated restaurants, cost vs rating, popular cuisines, ratings over time, and reviewer experience

## Key findings
- I found that the frequent ratings of the restaurants are between the 4 to 5 and then 1 to 3 are seen only by about 20 percentage rarely the .5's are given
- And people prefer North Indian, Chines and Continental food compared to other food styles
- People prefer the food costs between the 0 to 1500 range is more rarely above the 1500    

## Files
- `zomato_analysis.ipynb`: the full analysis
- Two CSV files: the raw data

## Author
Sai Krishna | www.linkedin.com/in/sai-krishna-thotte-80253831b
