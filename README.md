# Music-Reccomendation-System
A Python-based Music Recommendation System built using Pandas and NumPy, implementing both Popularity-Based and Item Similarity-Based Collaborative Filtering techniques. This project uses the Million Song Dataset to generate personalized and non-personalized music recommendations.
# Project Description
Music streaming platforms rely heavily on recommendation systems to improve user engagement.
This project implements two commonly used recommendation techniques:
Popularity-Based Recommendation – suggests trending songs
Item Similarity-Based Recommendation – provides personalized recommendations based on user listening history
The system is built using Python, Pandas, and NumPy, and is executed in a Jupyter Notebook environment.
# Recommendation Techniques
1️⃣ Popularity-Based Recommender
Recommends the most popular songs across all users
Based on total listening frequency
Same recommendations for every user
Useful for new or cold-start users
2️⃣ Item Similarity-Based Recommender
Personalized recommendation system
Finds songs similar to those a user has already listened to
Uses co-occurrence and similarity scores
Produces user-specific ranked recommendations
# Dataset
This project uses a subset of the Million Song Dataset.
Files:
triplets_file.csv
user_id
song_id
listen_count
song_data.csv
song_id
title
release
artist_name
year
# Technologies Used
Python 🐍
Pandas
NumPy
Jupyter Notebook
# Project Workflow
Load user listening data
Load song metadata
Merge datasets using song_id
Preprocess data and create song identifiers
Build popularity-based recommender
Build item similarity-based recommender
Generate song recommendations for users
