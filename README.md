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

Then After Extracting the data an excel file will be downloaded save it and move to google colab and then import spotipy
then paste this query
''' 
import spotipy
from spotipy.oauth2 import SpotifyClientCredentials

# Replace these with your Spotify Developer credentials
client_id = 'YOUR_CLIENT_ID'
client_secret = 'YOUR_CLIENT_SECRET'

# Authenticate
auth_manager = SpotifyClientCredentials(client_id=client_id, client_secret=client_secret)
sp = spotipy.Spotify(auth_manager=auth_manager)

# Search for a track (replace with your desired track name)
track_name = "Tum Hi Ho"
results = sp.search(q=track_name, type='track', limit=1)

# Extract album artwork URL for the first result
if results['tracks']['items']:
    track = results['tracks']['items'][0]
    album_images = track['album']['images']
    if album_images:
        artwork_url = album_images[0]['url']  # Usually 640x640
        print("Album artwork URL:", artwork_url)
    else:
        print("No album artwork found.")
else:
    print("No track found.")
'''
