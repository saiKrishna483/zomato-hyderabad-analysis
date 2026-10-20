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
- Ratings are mostly positive: about 63% of reviews are 4 stars or higher, and over a third are 3 stars or lower. Half-star ratings such as 4.5 are rare.
- North Indian, Chinese and Continental are the most common cuisines among the restaurants.
- Most restaurants charge under ₹1,500 for two, and only a few charge more.
- Pricier restaurants tend to rate a little higher, but the link is loose and does not show that price causes better ratings.   

## Files
- `zomato_analysis.ipynb`: the full analysis
- Two CSV files: the raw data

## Author
Sai Krishna | www.linkedin.com/in/sai-krishna-thotte-80253831b
