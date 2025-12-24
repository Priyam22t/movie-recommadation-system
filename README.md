# 🎬 Movie Recommendation System

## Overview
This project is a content-based movie recommendation system built using Python and machine learning techniques. It recommends movies similar to a selected movie by analyzing textual features such as genres, keywords, and movie overviews. TF-IDF vectorization and cosine similarity are used to measure how similar movies are and generate accurate recommendations.

## How It Works
- Loads a movie dataset
- Combines genres, keywords, and overview into one feature
- Cleans and preprocesses text using NLP techniques
- Converts text into numerical form using TF-IDF
- Computes similarity using cosine similarity
- Recommends the top similar movies

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- WordCloud

## Features
- Content-based recommendations
- Text preprocessing
- TF-IDF vectorization
- Cosine similarity matching
- Movie similarity search

## Project Structure
movie-recommendation-system/
├── movie_recommendation_system.py
├── movies.csv
└── README.md

## Example Usage
recommend_movies("Batman v Superman: Dawn of Justice")

## Future Improvements
- Add collaborative filtering
- Build a web interface
- Improve accuracy using embeddings
- Add user ratings

## Conclusion
This project demonstrates a simple and effective approach to building a movie recommendation system using natural language processing and machine learning.
