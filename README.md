# coupon-analysis
Answering the question: Will the Customer Accept the Coupon?

# Project Overview

This project explores customer behavior in accepting restaurant and bar coupons using Python, Pandas, and Seaborn. The dataset, sourced from the UCI Machine Learning Repository, contains survey responses about driving scenarios where participants were offered coupons.

The goal is to analyze which factors influence coupon acceptance and provide actionable insights for businesses looking to optimize their promotional strategies.

# Dataset
The dataset includes:
User attributes: Age, income, occupation, marital status, etc.

Contextual attributes: Weather, time of day, presence of passengers, etc.

Coupon attributes: Type of coupon (restaurant, bar, coffee house, etc.), expiration time, etc.

Target variable: Whether the coupon was accepted (Y = 1) or rejected (Y = 0).

# Methodology

1. Data Cleaning & Preprocessing:

- Removed unnecessary columns (e.g., car column with excessive missing values).


- Handled missing values by replacing them with 'Unknown'.


- Categorized features for better analysis.


2. Exploratory Data Analysis (EDA):

- Investigated missing values, distributions, and correlations.


- Used Seaborn for visualizing categorical and numerical distributions.


- Analyzed coupon acceptance rates by user behavior.


3. Key Comparisons:

- Restaurant vs. Bar coupon acceptance

- Effect of visit frequency (e.g., bar-goers visiting >3 times per month)

- Influence of age, income, passengers, and marital status on coupon acceptance

# Differences Between Customers Who Accepted vs. Rejected Coupons

Accepted Coupons (Y=1):

- More likely to be frequent diners (restaurant-goers >3 times/month).

- Higher acceptance rates among high-income individuals ($100K+).

- Younger drivers (<30) are more likely to accept bar coupons.

- More common among drivers without kid passengers.

- Higher acceptance for bar-goers who visit more than once a month.


Rejected Coupons (Y=0):

- More common among infrequent diners and lower-income individuals.

- Drivers with kid passengers are less likely to accept restaurant coupons.

- Older individuals (30+) are less likely to accept bar coupons.

- Less acceptance among drivers who do not frequently visit bars or restaurants.


# Key Findings

- Frequent restaurant-goers (>3 times/month) are more likely to accept restaurant coupons (~65%) compared to infrequent visitors (59%).

- High-income individuals ($100K+) who dine out frequently accept restaurant coupons at a higher rate (71%).

- Passengers without kids are more likely to accept restaurant coupons (61%).

- Frequent bar-goers (>1 time/month) accept bar coupons at a significantly higher rate (~77%).

- Younger drivers (<30) and frequent bar-goers accept bar coupons at the highest rate (~80%).

- Drivers with non-kid passengers and non-farming occupations were more likely to accept bar coupons.

# Next Steps & Recommendations

- Target frequent diners and high-income customers for restaurant promotions.

- Offer bar coupons to younger, socially active customers who frequently visit bars.

- Avoid targeting customers with kid passengers, as they show lower coupon acceptance.

- Further explore time-of-day and weather influences on coupon acceptance.

# Link to Jupyter Notebook

Click here to view the notebook
https://github.com/walhathal/coupon-analysis/blob/main/coupon-analysis.ipynb

# Author

Wael Alhathal - University of California, Berkeley - AI/ML Student
