Movie Recommender System

This is a Streamlit-based Movie Recommender System that provides personalized movie recommendations based on user input. The system uses a custom-trained recommendation model and fetches movie posters using the TMDB API.

Features

Recommends 5 movies similar to the selected movie.

Displays movie posters fetched dynamically from the TMDB API.

User-friendly interface built with Streamlit.

Requirements

To run the application, ensure you have the following installed:

Python 3.7+

Streamlit

Requests

Pandas

ustom Model

The recommendation system uses a custom-trained model to calculate similarity scores between movies.

The model processes user-selected movies and generates recommendations based on their relevance.

The similarity matrix (similarity.pkl) is derived from this custom model.

