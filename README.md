# Movie Recommender System

This is a movie recommender system built using Streamlit. The application suggests movies similar to a selected movie from a dropdown list and displays their posters fetched from the TMDb API.
![Screenshot 2024-06-24 144540](https://github.com/ummefahad/Recommender_system/assets/110823502/9ebdbb9f-f259-4dec-a4c2-52f8cf20b606)


## Features

- Select a movie from a dropdown list.
- Get recommendations for similar movies.
- Display the posters of the recommended movies.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/ummefahad/Recommender_system.git
   cd movierecommender
## Run the Streamlit application:

## streamlit run app.py
Open your browser and navigate to http://localhost:8501.

Select a movie from the dropdown list and click on "Show Recommendation" to see the recommended movies and their posters.

## Data
movie_dict.pkl: A pickle file containing a dictionary with movie titles and IDs.
similarity.pkl: A pickle file containing a similarity matrix for the movies.

## API
This project uses The Movie Database (TMDb) API to fetch movie posters. Make sure to replace the api_key in the fetch_poster function with your own TMDb API key.
