
# Project 5


## Problem Statement

In the expansive domain of Spotify[Spotify](https://www.spotify.com/), a platform that serves as a hub for global music communities and boasts a diverse repertoire of genres, the objective is to predict the popularity using songs released prior to 2019. This entails analyzing song features within Spotify's structure to anticipate their acclaim. Utilizing Spotify's vast database and insights into each song's characteristics, the aim is to discern the elements contributing to a song's success. Exploring factors such as genre, danceability, valency, and tempo etc, this predictive analysis seeks to unveil prevalent patterns and trends in the music landscape up to 2018. Ultimately, this exploration offers a means to comprehend and forecast the resonance of songs within Spotify's diverse and dynamic ecosystem.


## Data Dictionary


|Feature|Type|Description|Range|
|---|---|----|---|
|acousticness|*float*|A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.|0 - 1|
|danceability|*float*|Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.|0 - 1|
|duration_min|*float*| The duration of the track in minutes.|
|energy|*float*|Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy.|0 - 1|
|instrumentalness|*float*|Predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly "vocal". The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content.|0 - 1|
|key|*integer*|The key the track is in. Integers map to pitches using standard Pitch Class notation. If no key was detected, the value is -1.|-1 - 11|
|liveness|*float*|Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.|0 - 1| 
|loudness|*float*|The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Values typically range between -60 and 0 dB.|-60 - 0 dB |
|mode|*integer*|Mode indicates the modality (major or minor) of a track, represented by 1 for major and 0 for minor.|0 - 1|
|speechiness|*float*|Speechiness detects the presence of spoken words in a track.|0 - 1|
|tempo|*float*|The overall estimated tempo of a track in beats per minute (BPM).|   | 
|time_signature|*integer*|An estimated time signature, ranging from 3 to 7.|3 - 7|
|track_href|*object*|A link to the Web API endpoint providing full details of the track.|     | 
|type|*object*|The object type, which must be "audio_features". |string|        |                         
|valence|*float*|A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track.| 0 - 1|