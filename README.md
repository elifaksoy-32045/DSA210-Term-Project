# DSA210-Term-Project
## Description
Sabanci University DSA210 Introduction to Data Science Course Fall 2024-2025 Term Project.
This project will be an analysis on my Spotify listening habits and summer 2024 gym routine.

## Motivation
While brainstorming project ideas, I realized that two activities heavily influence my daily life: listening to music on Spotify and following my gym routine. During the summer of 2024, I had a consistent gym routine, making it an ideal period to analyze. After school starts, my gym routine becomes irregular, so I decided to focus solely on my summer data.

This project aims to analyze my Spotify music history and summer 2024 gym routine data to uncover insights into how my choice of music—such as energetic or calm tracks—aligns with different aspects of my gym activities. Through data visualization and analysis, I hope to understand how music impacts my workouts and potentially optimize my playlists for better performance.

## Data Sources
### Spotify Music History

The primary source of my music data comes from Spotify, which includes:

-  Tracks I listened to (title, artist, and album).
-  Time of playback.
-  Audio features of the tracks (energy, tempo, danceability, etc.) obtained using Spotify’s Web API.
  
### Gym Routine

The gym-related data will be manually logged and will include:

-  Dates and times of gym sessions.
-  Types of exercises performed (e.g., cardio, weightlifting).
-  Duration and intensity of workouts.

This manually collected data will serve as a key part of the analysis, providing insights into workout patterns and their relationship to music preferences.

## Research Questions
1.  What are the most common audio features (e.g., energy, tempo, pop) of the music I listen to during gym sessions?
2.  Are there specific times of the day (morning vs. evening) where my music preferences change during workouts?
3.  How consistent are my music choices during workouts compared to non-workout listening?

## Data Analysis
The analysis will proceed through the following stages:
### Data Collection:
**1.  Spotify Music Data:**
-  Playback history exported from Spotify as .json files.
-  Audio features (e.g., energy, tempo, valence) retrieved via Spotify Web API and saved as .csv.
  
**2.  Gym Routine Data:**
-  Manually logged gym session details, including date, time, workout type, intensity, and energy levels, saved as .csv.
### Data Cleaning:
-  Removing incomplete or inconsistent records.
-  Standardizing timestamps to align music playback with gym sessions.
-  Filtering out non-relevant data (e.g., music played outside workout times).
### Exploratory Data Analysis (EDA):
-  Visualizing trends in music features (e.g., energy, tempo, pop) during workouts.
-  Analyzing workout intensity and music preferences for different exercise types.
-  Investigating correlations between music features and workout performance.

## Tools and Methodology
**Programming Languages:** Python, Jupyter Notebook.

**Data Retrieval:** Spotify Web API for audio features, manual logging for gym routine data.

**Data Processing and Analysis:** Pandas, NumPy for data manipulation; Matplotlib, Seaborn, Plotly for visualizations.

**Modeling:** Scikit-learn for clustering and pattern analysis.

**File Management:** Spotify data in .json and .csv formats, gym routine data in .csv.


