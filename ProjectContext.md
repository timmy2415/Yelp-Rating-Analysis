# Analyzing Yelp Restaurant Data

In this project, I analyzed restaurant data from Yelp using Python on Google Colab. The goal of this project was analyze relationships between the Yelp dataset and a chosen topic. I decided to analyze the relationship between restaurant star ratings/user engagement and crime rate. 

Business Question: How does crime rate in US states impact the Yelp ratings of businesses?

Hypothesis: States with higher crime rates tend to have lower yelp ratings and lower user engagement

This project shows how to:
1) Join datasets on primary and foreign keys
2) Conduct calculations (crime rate per state)
3) Aggregate data using group by functions on state
4) Create visualizations to analyze relationship between star ratings and crime rate by state

Conclusion: In the first scatterplot graph analyzing the relationship between star rating and crime rate, the "Top 3“ and "Bottom 3" states are scattered, not showing a clear trend. Likewise, there is a shallow trend line slope and the data points are spread out. In the second scatterplot graph analyzing the relationship between crime rate and user engagement (review count), the “Top 3” and “Bottom 3” states again do not show a clear trend. The data points are also very spread out, suggesting a weak correlation. Overall, we found no strong correlation between crime rates, yelp ratings and user engagements. That said, we failed to prove the main hypothesis.  


Refer to the "Crime_Yelp_DataAnalysis.ipynb" file to view the complete python script
