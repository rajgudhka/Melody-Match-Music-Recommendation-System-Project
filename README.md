# Melody-Music-Recommendation-System-Project

Project Overview:-

Domain: Music/Entertainment, Recommendation Systems

Description: This project recommends similar songs based on audio data and textual features using the Spotify API. It takes a song as input and returns a list of recommended songs along with their album covers, enhancing the user experience by offering visuals alongside the recommendations.


![image](https://github.com/user-attachments/assets/861e540f-05aa-4b9c-b49d-3c88064e56e6)

Steps to Create the Project

1. Data Preparation:

Load and preprocess the dataset (spotify_millsongdata.csv).

Handle missing values and apply text cleaning techniques.



2. Text Tokenization and Stemming:

Convert text to lowercase and remove unnecessary characters.

Tokenize and stem words in the song descriptions to standardize vocabulary.



3. Feature Extraction:

Use TfidfVectorizer to extract textual features for each song and create a similarity matrix using cosine_similarity.



4. Building the Recommendation Function:

Implement a function to locate the input song, calculate similarities, and return the top similar songs.



5. Spotify Album Cover Retrieval:

Use spotipy to retrieve album covers based on song and artist names.



6. User Interface (UI):

Create a Streamlit UI for user interaction, allowing users to select a song and see recommendations.


Libraries and Technologies Used:-

spotipy: Spotify API wrapper for retrieving song and album details.

pandas: Data manipulation and analysis.

nltk: Tokenization and stemming.

scikit-learn: Text feature extraction and similarity calculation.

streamlit: Web interface for user interaction.



