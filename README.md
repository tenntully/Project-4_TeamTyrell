# Project-4_TeamTyrell

GT Bootcamp - Data Analytics and Visualization
Project 4
July 13, 2023

House Tyrell - Music and Song Recommendations
Colin Brooks, Michael Goff, Jason Hanlin, Steve Kennedy, Fatima Mumin, Kara Simone, Julie Tang, Manxuan Zhang, Ershad Ziaei

Project Proposal Summary and Description: https://docs.google.com/document/d/14TwDHvHHMMMj558k9QlshFJPQO9ONtRWM081qaVnqYs/edit

Project Presentation: https://docs.google.com/presentation/d/1bz4mXErbr8wp7ZEbuq8oBB230UqjeUh18s2WIa7eomE/edit#slide=id.p

Github Repository: https://github.com/tenntully/Project-4_TeamTyrell.git

Repository Files:
Project4-MusicML-GenrePrediction.ipynb (This file is the ML model classification and analysis code for the genre prediction. Output is modeling results and a RandomForest model - rfModel_genre.joblib and scaler scaler_genre.joblib. These must be run to export the files to the directory in order to use the Spotify Predictor App.)
Project4-MusicML-DecadePrediction.ipynb (This file is the ML model classification and analysis code for the decade prediction. Output is modeling results and a RandomForest model - rfModel.joblib and scaler scaler.joblib. These must be run to export the files to the directory in order to use the Spotify Predictor App.)
Spotify_Predictor_App.ipynb (This is predictor app.  It uses the ML models and scalers from the previous code. Output can be run in a cell but ideally should use Voila for a formatted app that is locally hosted.  To use Voila: pip install voila)
SKLearn - Song Recommendations.ipynb (This file is the ML clustering code to provide song recommendations from the Spotify songs sample.)
Project4 - Postgres SQL Setup.ipynb  (This file is the Postgres SQL Setup code to add to the ML modeling files in case a database setup is desired.  This can be added if the music_spofity or music songs will be added or changed to the sample over time.)
resources/music_spotify.csv (big spotify sample 170k songs)
resources/data.csv (alternate big spotify sample 170k songs)
resources/music.csv (MachineHack Hackathon sample dataset)

Tableau Visualizations: https://public.tableau.com/app/profile/fatima.mumin/viz/SPOTIFYTEMPODANCEABILITYPROJECT4/Dashboard1

Enjoy!
