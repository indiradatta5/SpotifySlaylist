# SpotifySlaylist


## Overview

This project is a Spotify recommendation system built using the Spotify API. It allows users to get song recommendations based on a list of input songs. The recommendations are generated using the Spotify API's recommendation endpoint, which provides personalized song suggestions based on the provided seed tracks.

## Features

- Fetches and displays recommendations based on user-provided songs.
- Utilizes Spotify's recommendation engine to suggest new songs.
- Analyzes song features and tracks from Spotify's database.

## Requirements

- Python 3.x
- Spotipy library
- Pandas
- NumPy

## Setup

1. **Install Dependencies**:
    ```bash
    !pip install spotipy pandas numpy
    ```

2. **Setup Environment Variables**:
    Define your Spotify API credentials directly in the Colab notebook or set up environment variables.

    ```python
    import os
    SPOTIFY_CLIENT_ID = 'your_client_id'
    SPOTIFY_CLIENT_SECRET = 'your_client_secret'
    ```

3. **Run the Colab Notebook**:
    Execute the notebook cells to run the recommendation system and fetch results.

## Usage

1. **Define Seed Songs**:
    Specify the list of songs you want to use as seed tracks.

    ```python
    song_list = [
        {'name': 'Come As You Are', 'year': 1991},
        {'name': 'Smells Like Teen Spirit', 'year': 1991},
        # Add more songs as needed
    ]
    ```

2. **Get Recommendations**:
    Call the function to get song recommendations.

    ```python
    recommended_songs = recommend_songs(song_list, spotify_data)
    print(recommended_songs)
    ```

## Contact

For questions about the dataset or the project, please contact me at [indiradatta5@gmail.com](mailto:indiradatta5@gmail.com).
