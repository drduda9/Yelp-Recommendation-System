# yelp_rec_sys
2nd Capstone Project - Springboard Career Track

For this project, I utilized the Yelp dataset from the Yelp Challenge. It is an 8gb file and can be downloaded from the Yelp challenge site. 

https://www.yelp.com/dataset

Yelp provides a challenge for people to conduct research or analysis using their dataset and is currently in the 13 round of the challenge. For this iteration, they’ve updated the dataset and it includes information about 156,000 local businesses in 12 metropolitan areas. For this capstone project, I will build a restaurant recommendation system for users utilizing a combination of two methods: content-based filtering and collaborative filtering. 

An example of a question being explored could be: “what is the best steakhouse to recommend to a user?” Using content-based filtering, we can recommend a steakhouse based upon that user’s previous reviews and preferences. But what if we have a brand new user to Yelp? Using collaborative filtering, we can recommend a steakhouse based upon similar user’s ratings. 

This recommender system will provide insight from current users to recommend restaurants to both new and current users.

UPDATE: 

Due to the size of the data and sparsity, I took a different approach for my project using the Yelp dataset. My goal is to create a recommender system that would give us insight as to whether a user would like a restaurant (greater than 3 stars) and if a user would give a rating greater than the business’ average star rating.
