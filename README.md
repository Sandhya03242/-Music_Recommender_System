🎶 Music Recommender System
This project is a Music Recommender System that suggests songs based on user input using natural language processing and machine learning techniques. It utilizes TF-IDF Vectorization and cosine similarity to find similar songs, and Spotify's API to retrieve album cover images.

📌 Table of Contents
Project Overview
Features
Dataset
Installation

🎯 Project Overview
This music recommender system:

Provides song recommendations based on the similarity of lyrics and metadata.
Fetches album cover images via the Spotify API.
Uses Streamlit to create an interactive user interface.
🚀 Features
Song Recommendation: Suggests similar songs based on lyrics.
Album Cover Display: Retrieves album cover images from Spotify's API.
User Interface: Interactive web app using Streamlit.
📄 Dataset
The project uses a subset of the "Spotify Million Song Dataset." The dataset is processed to remove unnecessary columns, and the 'text' field (lyrics) is transformed to lower case and stemmed for better matching.

🛠️ Installation
Requirements
Python 3.7 or higher
Spotipy
Streamlit
scikit-learn
NLTK
