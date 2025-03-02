#Restaurant Data Analysis

Overview

This analysis explores restaurant data to answer key questions regarding online vs. offline service availability, restaurant popularity, and preferred price ranges for couples dining out. The dataset used is sourced from "Zomato data.csv" and contains attributes such as restaurant names, online order availability, table booking options, ratings, votes, approximate costs, and restaurant types.

Key Questions Addressed

Do more restaurants offer online delivery compared to offline services?

What types of restaurants are the most popular?

What is the preferred price range for couples dining at restaurants?

Data Preparation

The dataset was loaded using Pandas.

The rate column was cleaned by converting ratings from string format (e.g., "4.1/5") to float values.

The dataset summary was explored using dataframe.info() to understand the data types and structure.

Findings

1. Online vs. Offline Ordering

A count plot was generated to analyze the online_order column.

Conclusion: Most restaurants do not accept online orders.

2. Most Favored Restaurant Types

The listed_in(type) column was explored using a count plot.

The number of votes per restaurant type was plotted to determine popularity.

Conclusion: Dining restaurants are the most preferred by the public.

3. Restaurants with the Most Votes

The restaurant receiving the highest votes was identified.

Conclusion: "Empire Restaurant" had the maximum votes, indicating high customer preference.

4. Ratings Distribution

A histogram was created to examine the rating distribution.

Conclusion: The majority of restaurants have ratings between 3.5 and 4.

5. Price Range Preferred by Couples

The approx_cost(for two people) column was analyzed using a count plot.

Conclusion: Most couples prefer restaurants where the approximate cost for two is around 300 rupees.

6. Online Orders vs. Offline Orders - Ratings Comparison

A box plot was created to compare ratings for online vs. offline orders.

Conclusion: Restaurants that accept online orders tend to have higher ratings compared to offline-only establishments.

7. Heatmap Analysis of Online Orders vs. Restaurant Type

A heatmap was generated to analyze the relationship between restaurant type and online ordering availability.

Conclusion: Dining restaurants mostly operate offline, while cafes primarily receive online orders. This indicates that customers prefer dine-in at restaurants but favor online ordering for cafes.

Summary

The analysis provides valuable insights into customer preferences, restaurant popularity, and service trends. The findings can help restaurant owners and food delivery platforms optimize their services to align with customer expectations.

