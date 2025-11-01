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
artwork_url: Contain the images of the album

Total 3 Dashboards are been made for this project 
**Screenshot of dashboard:**  
![Preview of Homepage](https://github.com/Arijeet226/My_Spotify_PowerBI_Dashboard_project5/blob/4ccb30b91b5d49001242c2b8d0a3e526cb8eb6fe/Assets/Screenshot%202025-11-01%20101505.png)

![Preview of dashboard](https://github.com/Arijeet226/My_Spotify_PowerBI_Dashboard_project5/blob/4ccb30b91b5d49001242c2b8d0a3e526cb8eb6fe/Assets/Screenshot%202025-11-01%20101524.png)

![Preview of dashboard](https://github.com/Arijeet226/My_Spotify_PowerBI_Dashboard_project5/blob/4ccb30b91b5d49001242c2b8d0a3e526cb8eb6fe/Assets/Screenshot%202025-11-01%20101539.png)

![Preview of dashboard](https://github.com/Arijeet226/My_Spotify_PowerBI_Dashboard_project5/blob/4ccb30b91b5d49001242c2b8d0a3e526cb8eb6fe/Assets/Screenshot%202025-11-01%20101558.png)

## INSIGHTS
Listening Diversity and Preferences
Your Spotify account showcases a diverse taste, spanning over 2,000 tracks and featuring 552 unique artists, which highlights your curiosity and openness to different musical styles. Major modes dominate your playlist (58.21%), suggesting a preference for upbeat or mainstream tracks, while almost 42% are in minor mode, indicating that you also enjoy moody or contemplative tunes.​

Engagement Patterns
Most of your music activity spikes during the mid-year months, with average song popularity peaking in June (61) and August (60). This could hint at a seasonal pattern—perhaps you listen more during holidays, summer breaks, or find certain months more inspiring musically. August stands out with the highest number of tracks added (219), possibly connecting to a period of discovery or project work where music played a big part in your routine.​

Artist and Label Leanings
T-Series is the dominant record label in your library (38.75%), followed by Sony Music (24.48%) and YRF Music (23.41%). The most frequent artist is Pritam with 65 songs, followed closely by Arijit Singh, showing a deep engagement with Bollywood and contemporary Indian music creators. The top played song by popularity is "Saiyaara" with a whopping 1,136 popularity score, indicating a strong emotional or nostalgic connection.​

Playlist and Track Characteristics
Your average track duration is about 4.42 minutes, suggesting a liking for full-length songs rather than short snippets or interludes. While explicit content is rare in your collection (only 8 out of 1,639 tracks), your selections cover a wide thematic ground. Tracks with high danceability scores and a mix of both highly popular and niche tracks indicate thoughtful curation—balancing crowd-pleasers with hidden gems.​

Evolving Tastes
The "count of songs released by year" graph shows a major ramp-up in recent years, aligning with current musical trends and your evolving interests. You seem to lean toward newer releases but keep classics in regular rotation, as seen by consistent engagement with songs from the late '90s to the present day.

# --THANK YOU--
