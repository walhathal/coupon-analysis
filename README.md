# coupon-analysis
Answering the question: Will the Customer Accept the Coupon?
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


# Key Findings

- Frequent restaurant-goers (>3 times/month) are more likely to accept restaurant coupons (~65%) compared to infrequent visitors (59%).

- High-income individuals ($100K+) who dine out frequently accept restaurant coupons at a higher rate (71%).

- Passengers without kids are more likely to accept restaurant coupons (61%).

- Frequent bar-goers (>1 time/month) accept bar coupons at a significantly higher rate (~77%).

- Younger drivers (<30) and frequent bar-goers accept bar coupons at the highest rate (~80%).

- Drivers with non-kid passengers and non-farming occupations were more likely to accept bar coupons.

# Link to Jupyter Notebook

Click here to view the notebook

# Author

Wael Alhathal - University of California, Berkeley - AI/ML Student
