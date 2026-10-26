# Swiggy Restaurants EDA

Exploratory data analysis of ~140k Swiggy restaurant listings across India.

Dataset: [Swiggy Restaurants Dataset (Kaggle)](https://www.kaggle.com/datasets/rrkcoder/swiggy-restaurants-dataset)
Tools: Python, Pandas, Matplotlib, Seaborn

What I did
- Cleaned the data: removed duplicates, converted ratings and prices from text to numbers, handled missing values
- Removed 751 rows with implausible prices (e.g. a ₹1.99 lakh entry)
- Analyzed cities, cuisines, pricing, and ratings

Key findings
- Goa and Hyderabad are the most expensive cities for dining out
- Chinese and North Indian dominate the cuisine listings
- Price and pure-veg status have little effect on ratings

Limitations
- City listings appear capped at about 2,000, so counts are not comparable
- Number of ratings is a lower bound (e.g. "500+" is stored as 500)
