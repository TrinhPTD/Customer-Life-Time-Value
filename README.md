# Customer-Life-Time-Value in Marketing Analytics

# Introduction
The goal of this project is to apply predictive models to predict the customer margin and the likelihood of their churn, and subsequently calculate customer future value. We are aims to answer three business questions as follow:
1/ How do we increase customer retention?
2/ How do we increase customer margin?
3/ Can we segment customers to utilize targeted marketing?

# Data Understanding
Data was consolidated from three main datasets:
1/ Churn data: 31 columns, 240,000 rows. The data includes purchase counts, amounts, types by time frames.
2/ Margin data: 97 columns, 240,000 rows. The data contains transactional costs.
3/ Demographic data: 11 columns, 240,000 rows. The data shows customer demographic data such as age, length of time, and income,..

# Data preparation
- Modify margin data to focus on annual numbers
- Eliminate dupplicate accounts
- Merge churn, margin and demographic data by account
- Create dummy variables for categorical variables
- Detect outliers and impute missing values

# Model building
- We use machine learning algorithm to produce churn and margin score.
- Calculate customer future value for each individual
- Perform customer profiling by using Quadrant analysis
<img src="https://github.com/TrinhPTD/Customer-Life-Time-Value/blob/main/Quadrant%20analysis.png">

# Result
- For each of segment, we recommened different strategies to retain customers such as upsell, cross sell and retention.
