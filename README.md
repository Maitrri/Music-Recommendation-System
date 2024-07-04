# Music-Recommendation-System
Description
This project features a music recommendation system that uses two main approaches to suggest songs:

Popularity-based Algorithm: Recommends universally popular songs to all users based on overall listen counts.
Collaborative Filtering: Provides personalized recommendations by leveraging user preferences and similarities. It includes:
User-based Collaborative Filtering: Recommends songs based on similarities between users.
Item-based Collaborative Filtering: Recommends songs based on similarities between items (songs).
These methods work together to enhance the accuracy and personalization of song recommendations.

Implementation
The project is implemented in Python using the following steps:

Data Preparation:

Load and merge datasets containing user-song interaction and song metadata.
Create new features combining song titles and artist names.
Aggregate listen counts and calculate song popularity.
Popularity-based Recommender:

Create a popularity-based model that ranks songs by listen counts.
Recommend top songs based on their popularity scores.
Collaborative Filtering Recommender:

Implement user-based and item-based collaborative filtering.
Construct a co-occurrence matrix to capture user-song interactions.
Generate recommendations based on user similarity and item similarity.
Usage
Install Dependencies:
pip install recommenders
