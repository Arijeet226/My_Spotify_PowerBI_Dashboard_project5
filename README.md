# My_Spotify_PowerBI_Dashboard_project5
This is a very personal project done on my Spotify playlist. Hope you enjoy it !!
First and foremost I have extracted data from my Spotify account using Exportify.
1. Create a Spotify Developer Account and App
Go to the Spotify Developer Dashboard and log in with your Spotify account.
Click "Create an App". Fill in the app name and description.
Note your Client ID and Client Secret
Use your Client ID and Client Secret to request an access token via OAuth 2.0.

2.To get Client ID and Client Secret
Enter a name and description for your app, then click "Create".
On your new app’s page, you’ll find your Client ID and Client Secret listed clearly.
You can view the Client Secret by clicking “Show Client Secret” next to the hidden field
You will get a file Main_Tera_3.csv

Then After Extracting the data an excel file will be downloaded save it and move to google colab and then import spotipy
then paste the query as shown in above Spotify_API_Extraction_DataCleaning.ipynb You will get a new file of track_artworks.csv
then clear all the unnecessary data and then merged that 2 files Main_Tera_3.csv and track_artworks.csv and create a new file merged_data.csv

Column Name Descriptions
Track URI: The unique Spotify identifier for the song (Uniform Resource Identifier).

Track Name: The title of the song or track.

Album Name: The title of the album where the song appears.

Artist Name(s): The main performing artist(s) of the track.

Release Date: The official date when the track or album was released.

Duration (ms): Length of the song in milliseconds.

Popularity: A score (usually 0-100) representing how popular the track is on Spotify, based on factors like streams and recent plays.

Explicit: Indicates whether the track contains explicit content (such as strong language).

Added By: The Spotify user who added the track to a playlist.

Added At: The date and time when the track was added to a playlist.

Genres: Musical genres associated with the track or its artists.

Record Label: The company responsible for releasing the music.

Danceability: A score (often 0-1) that describes how suitable the track is for dancing.

Energy: A score (often 0-1) measuring intensity and activity (e.g., fast, loud, noisy).

Key: The estimated overall musical key of the track, coded as integers (often 0=C, 1=C♯/D♭, etc.).

Loudness: The overall loudness of the track in decibels (dB).

Mode: Indicates if the track is in a major (1) or minor (0) key.

Speechiness: A score describing the presence of spoken words in the track.

Acousticness: A score estimating whether the track is acoustic.

Instrumentalness: Predicts whether a track features no vocals.

Liveness: Detects the presence of an audience in the recording.

Valence: Describes musical positiveness (0=sad/angry, 1=happy/upbeat).

Tempo: The speed of the track in beats per minute (BPM).

Time Signature: Number of beats per bar (measure) in the track's rhythm.

Total 3 Dashboards are been made for this project 
**Screenshot of dashboard:**  
![Preview of Homepage](https://github.com/Arijeet226/My_Spotify_PowerBI_Dashboard_project5/blob/4ccb30b91b5d49001242c2b8d0a3e526cb8eb6fe/Assets/Screenshot%202025-11-01%20101505.png)

![Preview of dashboard](https://github.com/Arijeet226/My_Spotify_PowerBI_Dashboard_project5/blob/4ccb30b91b5d49001242c2b8d0a3e526cb8eb6fe/Assets/Screenshot%202025-11-01%20101524.png)

![Preview of dashboard](https://github.com/Arijeet226/My_Spotify_PowerBI_Dashboard_project5/blob/4ccb30b91b5d49001242c2b8d0a3e526cb8eb6fe/Assets/Screenshot%202025-11-01%20101539.png)

![Preview of dashboard](https://github.com/Arijeet226/My_Spotify_PowerBI_Dashboard_project5/blob/4ccb30b91b5d49001242c2b8d0a3e526cb8eb6fe/Assets/Screenshot%202025-11-01%20101558.png)

