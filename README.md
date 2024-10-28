🎶 Music Recommender System

   This project is a Music Recommender System that suggests songs based on user input using Natural Language Processing (NLP)
   and Machine Learning techniques. It utilizes TF-IDF Vectorization and cosine similarity to find similar songs, and Spotify's API to retrieve album cover images.

📌 Table of Contents

   - Project Overview
   - Features
   - Dataset
   - Installation
  
🎯 Project Overview

   This music recommender system:
   
   - Provides song recommendations based on the similarity of lyrics and metadata.
   - Fetches album cover images via the Spotify API.
   - Uses Streamlit to create an interactive user interface.
    
✨ Features

   - Song Recommendation: Input a song title to receive recommendations for similar songs.
   - Album Cover Display: Displays album covers for recommended songs.
   - Interactive Web App: Built using Streamlit for a user-friendly interface.
    
📄 Dataset

   The dataset used for this project is the Spotify Million Song Dataset. The dataset is processed to remove unnecessary
   columns, and the 'text' field (lyrics) is transformed to lowercase and stemmed for better matching. You can download the
   dataset from Kaggle.
   
   Kaggle Dataset: https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset

🛠️ Installation

   Requirements:
   - Python
   - Pandas
   - NLTK
   - Scikit-learn
   - Streamlit
   - Spotipy (Spotify API Wrapper)
   - Pickle (for model persistence)


