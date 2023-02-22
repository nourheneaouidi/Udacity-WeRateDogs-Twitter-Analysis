# Udacity-WeRateDogs-Twitter-Analysis

## Overview
WeRateDogs is a popular Twitter account with over 8 million followers that posts and rates pictures of dogs. The account is known for its humorous and non-serious ratings, often with numerators higher than denominators. In this analysis, I looked at WeRateDogs' archive as of August 1, 2017, using data provided by Udacity. The dataset includes information on each tweet's text, timestamp, and user engagement metrics such as retweets and favorites. Additionally, Udacity ran the images on WeRateDogs' account through a neural network to generate three predictions for each image.

## Questions
I aimed to answer the following questions with this analysis:

What is the distribution of dog ratings given by WeRateDogs?
How do favorites and retweets correlate with the dog rating?
What is the monthly trend of interactions with WeRateDogs' posts?
Data Cleaning
Before conducting the analysis, I cleaned the data to include only original content with images. I removed retweets, replies, and tweets without images. Additionally, I extracted the dog breed predictions from the neural network's output and created a new column for the predicted breed.

##Analysis
Dog Ratings
I first analyzed the distribution of dog ratings given by WeRateDogs. The ratings are typically in the form of a fraction with the numerator higher than the denominator, such as "13/10." I plotted a histogram of the ratings and found that they were skewed to the right, with the most common rating being 12/10.

Favorites and Retweets
Next, I looked at the relationship between favorites, retweets, and the dog rating. I plotted scatterplots of each metric against the dog rating and found a positive correlation between all three variables. As the dog rating increased, the number of favorites and retweets also increased.

Monthly Trends
Finally, I analyzed the monthly trends of interactions with WeRateDogs' posts. I plotted a line chart of the monthly mean favorites and retweets and found that both metrics had a positive trend over time, with a peak in late 2016. However, the number of tweets posted per month had a negative trend, indicating that WeRateDogs was posting less frequently as the account grew in popularity.

## Conclusion
This analysis provides insight into the popularity and engagement of WeRateDogs on Twitter. The dog ratings are skewed to the right, and the number of favorites and retweets is positively correlated with the rating. Additionally, WeRateDogs' posts have a positive trend in engagement over time, despite a negative trend in the number of tweets posted per month.
