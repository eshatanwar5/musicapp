# musicapp
 A Music App using Flutter that can provide lyrics of tracks using third party API services using  bloc pattern.
The homepage  load the list of Tracks for which the lyrics are
available in the backend with TRACK_ID.
After loading, User can select any track. Once the user selects a track,
TRACK_ID of that particular track will be passed on to the next screen.
The Tracks details must be shown to the customer once the app gets the
response from the backend.
You must handle the case in which if the internet is not working, you will
show a message "NO INTERNET CONNECTION".
