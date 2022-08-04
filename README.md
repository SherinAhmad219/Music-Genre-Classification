# Music-Genre-Classification
This is competition to predict model made using python on jupyter notebooks in kaggle with Shai.

https://www.kaggle.com/competitions/shai-music-genre-classification

### Data Description:

Training dataset: 14395 rows with 18 columns
Column details: artist name; track name; popularity; ‘danceability’; energy; key; loudness; mode; ‘speechiness’; ‘acousticness’; ‘instrumentalness’; liveness; valence; tempo; duration in milliseconds and time_signature.
Target Variable: 'Class’ such as Rock, Indie, Alt, Pop, Metal, HipHop, Alt_Music, Blues, Acoustic/Folk, Instrumental, Country, Bollywood,
Test dataset: 3600 rows with 17 columns


#### Files:

- train(1).csv - the training set
- test(2).csv - the test set

#### Features

- artist: Name of the Artist.
- song: Name of the Track.
- popularity: popular the song.
- danceability: how suitable a track is for dancing
- energy: measure of intensity and activity.
- key: The key of the track .
- loudness: loudness of a track in decibels (dB). 
- mode: Mode (major or minor) of a track.
- speechiness: presence of spoken words in a track.
- acousticness: A confidence measure of the track.
- instrumentalness: Predicts a track contains no vocals. 
- liveness: Higher liveness values represent an increased probability that the track was performed live. 
- valence: describing the musical positiveness 
- tempo: the speed or pace of a given piece and derives directly from the average beat duration.
- duration in milliseconds :Time of the song
- time_signature : how many beats (pulses).


#### Evaluation Metric

The evaluation metric for this competition is Root Mean Squared Error (F1-score). The F1-score can be interpreted as a harmonic mean of the precision and recall.
F1 = 2 * (precision * recall) / (precision + recall)

