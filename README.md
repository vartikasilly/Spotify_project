# Spotify_project

To make this I started with a Kaggle dataset :

Enriched the dataset using ChatGPT Code generation
Python to call Spotify's Web API to get images
Powerpoint for the Glassmorphism layout

Project execution flow:

The entire data pipeline is designed to be automated and scheduled to run daily. The AWS Lambda Function responsible for data extraction is triggered by Cloud Watch on a daily basis. This ensures that the latest data from the Spotify API is fetched regularly.

Upon successful extraction, the transformation process is triggered automatically for the newly uploaded data. The transformed data is then moved to their respective folders, and the raw data is removed to keep the data clean and organized.

Conclusions:

By implementing this fully automated data pipeline, we ensure that new data from the Spotify API is efficiently processed and made available for analysis.
