# Movie Recommendation System
This project implements different recommendation systems for movies using Python. Multiple machine learning and matrix factorization techniques are leveraged to provide personalized movie suggestions based on user preferences and browsing history.

## Algorithms Implemented
The following recommendation algorithms are used:

Content-based Filtering
Calculates similarity between movies based on genre, cast, director etc.
Recommends movies similar to what user has liked in the past
Collaborative Filtering
Memory-based
User-User
Finds similar users and recommends movies they have liked
Item-Item
Finds similarity between movies based on user ratings and recommends most similar movies
Model-based
Matrix Factorization with SVD
Decomposes user-movie rating matrix to find latent preferences
SVD++
Incorporates implicit feedback along with explicit ratings for predictions

## Hybrid Recommender
Combines Content-based and SVD Matrix Factorization models to leverage benefits of both systems.

## Evaluation Metrics
Root Mean Squared Error
Mean Absolute Error
Hit Ratio
Precision and Recall

## Datasets
The MovieLens 100K dataset has been used containing:

100,000 ratings
9,742 movies
610 users

## Usage
The Jupyter notebooks showcase step-by-step implementation, evaluation and comparison of each algorithm.

The recommender.py module provides helper functions to build and evaluate models.

## Installation
The project requires Python 3 and the following libraries:

Pandas
NumPy
SciPy
scikit-surprise
Matplotlib
Install the dependencies using pip install -r requirements.txt

## Future Work
Some ideas for extending the project:

Incorporate additional metadata like movie posters, descriptions, reviews etc.
Add functionality for new users with sparse profiles
Develop a full-fledged web application with API
Containerize models with Docker for easy deployment
