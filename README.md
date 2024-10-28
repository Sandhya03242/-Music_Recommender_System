# 🎶 Music Recommender System

This project is a Music Recommender System that suggests songs based on user input using Natural Language Processing (NLP) and Machine Learning techniques. It utilizes TF-IDF Vectorization and cosine similarity to find similar songs, and Spotify's API to retrieve album cover images.

## 📌 Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)

## 🎯 Project Overview

This music recommender system:
- Provides song recommendations based on the similarity of lyrics and metadata.
- Fetches album cover images via the Spotify API.
- Uses Streamlit to create an interactive user interface.

## ✨ Features
- **Song Recommendation**: Input a song title to receive recommendations for similar songs.
- **Album Cover Display**: Displays album covers for recommended songs.
- **Interactive Web App**: Built using Streamlit for a user-friendly interface.

## 📄 Dataset

The dataset used for this project is the [Spotify Million Song Dataset](https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset). The dataset is processed to remove unnecessary columns, and the 'text' field (lyrics) is transformed to lowercase and stemmed for better matching.

## 🛠️ Installation

### Requirements:
- Python
- Pandas
- NLTK
- Scikit-learn
- Streamlit
- Spotipy (Spotify API Wrapper)
- Pickle (for model persistence)

### Installation Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/Sandhya03242/music-recommender-system.git
   cd music-recommender-system
   ```
2. Install the required packages:
   ```bash
   pip install pandas nltk scikit-learn streamlit spotipy
   
3. Download the dataset from Kaggle and place it in the project directory.
4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
## 🎧 Usage

1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```
2. Access the application: Follow the instructions displayed in your terminal to access the application in your web browser.


