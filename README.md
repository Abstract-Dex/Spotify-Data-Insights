# Spotify Data Insights

[View Notebook Here](https://nbviewer.org/github/Abstract-Dex/spotify_data_insights/blob/main/main.ipynb)

<!-- ## About Dataset

This is a dataset of Spotify tracks over a range of 82 different genres. Each track has some audio features associated with it.

### Column Descriptions

- `genre` - The genre of the track

- `track_id` - The Spotify ID of the track

- `track_name` - The name of the track

- `popularity` - The popularity of the track

- `year` - The year the track was released

- `danceability` - Danceability describes how suitable a track is for dancing based on a
  combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable

- `duration_ms` - The duration of the track in milliseconds

- `energy` - Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy

- `loudness` - The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks

- `mode` - Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0

- `key` - The estimated overall key of the track. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on

- `acousticness` - A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic

- `speechiness` - Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value

- `instrumentalness` - Predicts whether a track contains no vocals. “Ooh” and “aah” sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly “vocal”. The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content

- `liveness` - Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live

- `valence` - A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry)

- `tempo` - The overall estimated tempo of a track in beats per minute (BPM)

- `time_signature` - An estimated overall time signature of a track. The time signature (meter) is a notational convention to specify how many beats are in each bar (or measure)

## Usage

The dataset is used to predict the popularity of a track based on its audio features. The dataset is also used to find the most popular genres and artists.

### Setup

1. Clone the repository
2. Install the dependencies using `pip install -r requirements.txt`
3. Run `jupyter notebook` in the terminal to start the notebook server

### Running the Notebook

1. Open the notebook in Jupyter Notebook
2. Run the cells in order -->

# Spotify Tracks Genre Prediction

## Introduction

This repository contains a dataset of Spotify tracks across various genres, complete with audio features. The goal is to predict track popularity based on these features and gain insights into the most popular genres and artists.

## Prerequisites

Before you begin, ensure you have the following requirements in place:

- Python 3.x
- Libraries listed in `requirements.txt`. Install them using `pip install -r requirements.txt`.

## Installation

1. Clone this repository to your local machine:
   git clone https://github.com/yourusername/spotify_data_insights.git

2. Navigate to the project directory:
   cd spotify_data_insights

3. Install the dependencies:
   pip install -r requirements.txt

## Usage

To get started, open the Jupyter Notebook provided in this repository. Follow the instructions below:

1. Open the notebook in Jupyter Notebook
2. Run the cells in order to load and preprocess the dataset, perform exploratory data analysis (EDA), train machine learning models, and visualize the results.

## Data Description

Here's a breakdown of the dataset columns:

- `genre`: The genre of the track.
- `track_id`: The Spotify ID of the track.
- `track_name`: The name of the track.
- `popularity`: The popularity of the track.
- `year`: The year the track was released.
- `danceability`: A measure of how suitable the track is for dancing.
- `duration_ms`: The duration of the track in milliseconds.
- `energy`: A measure of intensity and activity.
- `loudness`: The overall loudness of the track in decibels (dB).
- `mode`: Indicates the modality (major or minor) of the track.
- `key`: The estimated overall key of the track.
- `acousticness`: A confidence measure of whether the track is acoustic.
- `speechiness`: Detects the presence of spoken words in a track.
- `instrumentalness`: Predicts whether a track contains no vocals.
- `liveness`: Detects the presence of an audience in the recording.
- `valence`: A measure describing the musical positiveness conveyed by a track.
- `tempo`: The overall estimated tempo of a track in beats per minute (BPM).
- `time_signature`: An estimated overall time signature of a track.

## Exploratory Data Analysis (EDA)

The Jupyter Notebook includes comprehensive EDA, highlighting key insights and visualizations to help understand the dataset better.

## Project Structure

- `Spotify_Tracks_Popularity_Prediction.ipynb`: The Jupyter Notebook for the project.
- `data/`: Directory containing the dataset (`spotify_tracks.csv`).
- `requirements.txt`: List of Python dependencies for the project.
