Zomato Hyderabad Restaurants: Python Data Analysis

Cleaning and exploring a messy Zomato dataset of 105 Hyderabad restaurants and about 10,000 customer reviews, using Python.

Dataset

"Zomato Restaurants Hyderabad" from Kaggle. It has two CSV files:

Restaurant names and Metadata.csv: 105 restaurants with cost, cuisines, collections and timings
Restaurant reviews.csv: 10,000 customer reviews with rating, reviewer info and date (May 2016 to May 2019)
Tools

Python, pandas, matplotlib, seaborn, Jupyter Notebook (VS Code)

What I did
Loaded and inspected both tables: size, data types, missing values and duplicates.
Cleaned the data (10,000 reviews became 9,961):
Removed duplicate rows
Dropped reviews with no rating and one invalid rating ("Like")
Converted Rating and Cost from text to numbers, and Time from text to dates
Split the reviewer info ("3 Reviews , 427 Followers") into two number columns
Left missing Collections and Timings values as they were, since the analysis doesn't use them
Joined the two tables on restaurant name.
Explored six questions with charts and wrote up what each one shows:
How are ratings distributed?
Which restaurants have the highest average rating?
Do pricier restaurants get better ratings?
Which cuisines are most common?
Have ratings changed over time?
Do experienced reviewers rate differently?
Key findings
Ratings are polarized: 5-star is the most common rating, but 1-star reviews outnumber 2-star ones.
Only restaurants with 50 or more reviews were ranked, so a few ratings couldn't push a restaurant to the top.
Pricier restaurants tend to rate a little higher, but the link is loose and does not show that price causes better ratings.
North Indian is the most common cuisine, listed by about 58% of restaurants, followed by Chinese.
Monthly ratings stayed fairly flat from late 2018 to early 2019. Months with fewer than 30 reviews were excluded.
Reviewer experience makes little difference to the rating given.
Files
zomato_analysis.ipynb: the full analysis with code, charts and notes
Restaurant names and Metadata.csv and Restaurant reviews.csv: the raw data
Author

Sai Krishna | LinkedIn
