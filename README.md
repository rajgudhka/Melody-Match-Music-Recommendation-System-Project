# Melody Match: A Dynamic Music Recommendation System

## Project Overview
**Domain**: Recommendation Systems

## Dataset
- [Spotify Million Song Dataset](https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset)

**Description**: Melody Match is a content-based music recommendation system built using Python, Streamlit, and NLP techniques. The project utilizes a Kaggle dataset refined for optimal performance, combined with Spotify API integration to deliver song recommendations with album visuals, enhancing the user experience.

![image](https://github.com/user-attachments/assets/33a19f09-b801-4318-824f-ea0292f51774)


## Key Features
- **Content-Based Recommendations**: Developed a system that leverages lyrical analysis to recommend songs based on user input.
- **Efficient Data Handling**: Utilized a Kaggle dataset containing 57,650 songs, refined to a sample of 5,000 rows for optimized data processing using **pandas**.
- **Data Preprocessing**: Employed **pandas** for data manipulation, cleaning, and structuring, alongside **nltk** for tokenization and stemming to standardize lyrics and improve feature extraction.
- **Feature Extraction and Similarity Calculation**: Implemented **scikit-learn's TF-IDF Vectorizer** to transform lyrics into numerical features and used **cosine similarity** to calculate the similarity between songs.
- **Spotify API Integration**: Integrated **spotipy** by creating a Spotify Developer account, utilizing **client ID** and **client secret** to fetch album cover images, adding visual appeal to the recommendations.
- **Interactive Web Interface**: Deployed the project using **Streamlit**, creating a user-friendly interface that allows users to input a song and receive personalized recommendations with album art.

## Libraries and Technologies Used
- **Python**
- **Streamlit**: For building the interactive web interface.
- **pandas**: For data manipulation and preprocessing.
- **nltk**: For tokenization and stemming of song lyrics.
- **scikit-learn**: For feature extraction using TF-IDF Vectorizer and similarity computation.
- **spotipy**: For accessing the Spotify API and fetching album cover images.






