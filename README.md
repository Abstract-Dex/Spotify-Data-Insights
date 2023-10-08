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

The Jupyter Notebook includes comprehensive EDA, highlighting key insights and visualizations to help understand the dataset better. [View Notebook Here](https://nbviewer.org/github/Abstract-Dex/spotify_data_insights/blob/main/main.ipynb)

## Project Structure

- `Spotify_Tracks_Popularity_Prediction.ipynb`: The Jupyter Notebook for the project.
- `data/`: Directory containing the dataset (`spotify_tracks.csv`).
- `requirements.txt`: List of Python dependencies for the project.

## Results

The exploratory data analysis revealed that the most popular genres were Pop, Hip-Hop, and Rock. The most popular artists were NewJeans, Elley Duhe and Rema. The most popular tracks were Shakira: Bzrp Music Sessions, Die For You - Remix and Calm Down (with Selena Gomez).
Some of the charts generated during the EDA are shown below:

![output2](https://github.com/Abstract-Dex/spotify_data_insights/assets/90722648/cb84710a-fd7c-4a30-9bd2-1453558feb97)

![output1](https://github.com/Abstract-Dex/spotify_data_insights/assets/90722648/15f496b4-d3e2-4da6-8f72-143275ffc7a7)

![output](https://github.com/Abstract-Dex/spotify_data_insights/assets/90722648/a97aa1e8-5ef5-4e1e-83d4-515fe599d1fd)

The best performing model was a Random Forest Regressor with a mean absolute error (MAE) of 9.5. Another model, was then trained on the important features identified by the Random Forest Regressor. This model was also a Random Forest Regressor, and it achieved a MAE of 0.49.
