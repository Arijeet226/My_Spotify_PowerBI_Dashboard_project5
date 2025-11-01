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
