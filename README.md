# Project : Amazon Product Recommendation System 
*Recommendation Systems*<br>
In an era of exponential information growth, consumers often face the challenge of information overload, leading to decision fatigue. 
To combat this, our goal is to develop a sophisticated recommendation system for Amazon that offers personalized product suggestions based on individual user preferences and past ratings.<br>
 <br>
 ## Goal
 By leveraging a collection of labeled Amazon product reviews develop a robust recommendation system that leverages machine learning to analyze user ratings and preferences from a comprehensive dataset of Amazon product reviews.
 We aim to create an intelligent system that not only enhances user engagement but also drives sales by delivering relevant and timely recommendations

## Process
1. First, we installed the necessary libraries, including Surprise, pandas, matplotlib, and seaborn, to facilitate data handling and analysis.
2. Next, we loaded the dataset and conducted exploratory data analysis (EDA) to check for missing values, understand the distribution of ratings, and identify the number of unique users and items.
3. Following the EDA, we built three distinct recommendation models:
* Rank-Based Recommendation System: We established a simple model that provides recommendations based on average ratings.
* Collaborative Filtering Recommendation System: Utilizing the Surprise package, we implemented both user-user and item-item similarity-based models to generate recommendations based on the interactions of similar users or items.
* Model-Based Collaborative Filtering: We employed matrix factorization techniques, specifically Singular Value Decomposition (SVD), to derive latent factors that capture user preferences and item characteristics.

## Insights
* A key metric in achieving these goals is precision, which measures the proportion of recommended items that are relevant to users. High precision is crucial, as it ensures that recommendations directly impact sales and enhance user satisfaction. By focusing on items with a higher likelihood of purchase, we can significantly improve performance in these areas.
* The Singular Value Decomposition (SVD) model has proven to be a robust choice for this dataset. Its ability to accurately predict ratings—even in sparse data scenarios—without relying on fallback methods demonstrates its effectiveness.
* The optimized SVD model achieved the highest precision scores, along with strong results in RMSE and F1 metrics, confirming its status as the preferred recommendation approach.
