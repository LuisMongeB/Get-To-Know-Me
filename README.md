# Get-To-Know-Me

This project was born out of curiosity after I discovered I could ask Spotify for my streaming data of the past year. 
It also became a vehicle in which to put some of the skills that have been maturing into practice. 

To recreate this for yourself follow these steps:

1. Sign-up to Spotify Developers and follow the tutorial to create tokens and project
    - Pragya Verma has a nice tutorial here: https://medium.com/analytics-vidhya/spotify-music-data-analysis-part-1-c8457bfc53a
2. Save the required information in the Config.json file and then open ExtractFeatures.ipynb. This will populate your directory with the files needed. It can take a while, be  patient :)
3. After this you are free to use the EDA and Clustering Notebooks to explore your own music, hopefully adding your own functionalities. 

In this project the following aspects were covered:

- Interacting with APIs
- EDA including descriptive analytics and visualization
- Basic Cosine Similarity to find similar artists
- Clustering to form pseudo-playlists

Data Manipulation Libraries: Pandas, Numpy
Visualization Libraries: Matplotlib, Seaborn
Machine Learning Libraries: Sklearn
Feature Extraction and API: Requests, JSON, Spotipy
