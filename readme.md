# Presently Surprised: A Gift Recommender Model

#### Introduction
Presently Surprised Co. Ltd. is an online retailer of gifts. 
The company did well this year, sales grew by 20% (December peak to peak), but there is a issue of customer retention. Also, due to large number of products in our portfolio, and a survey of customers report painpoints of difficulty in navigating the website.

Management has tasked the Data Science Team to find solutions to improve customer experience and we are proposing to develop a recommender model that predicts the top 10 products a customer would buy on a particular day.

Data source: “Online Retail Data Set” from the UCI Machine Learning Repository

#### Methodology
Test data would be defined as the atest invoice per customer in the dataset

We would be using rule based recommender systems and evaluate it according to prediction hit rate and sum of revenue predicted.
- Model 1: Ranking based on total sales
- Model 2: Personalized ranking model
- Model 3: Adaptive Nearest Neighbour
- Model 4: Customer Kmeoids clustering with SVM
- Model 5: Trending machine
