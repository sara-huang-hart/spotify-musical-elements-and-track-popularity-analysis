# 📌 Project Background  
In the age of digitalization, music streaming services have become a fundamental part of how listeners experience and engage with music. In 2023, Spotify had a global market share of 31.7% with over 350 million users worldwide. In this project, we tried to answer the question, "Can music be simplified to a formula? Specifically, are there certain musical elements, like song duration, significant factors in determining a track's overall success?". To answer this question, we looked at the Spotify [dataset](https://www.kaggle.com/datasets/sanjanchaudhari/spotify-dataset) posted on Kaggle.  

<i>In collaboration with Yilu Chen, Andrew Gatchalian, Hsuan-Yi Lin, and Rakesh Venkata Subramaniyan.</i>  

# 🎵 Data Overview  
The dataset that was used for this project contained over 18,000 tracks from Spotify. The data provided insight into artists, tracks, albums, streams received, and audio features. For each track, there are various audio feature attributes. For this project, we focused on the danceability, duration_min, energy, tempo, loudness, instrumentalness, and valance attributes.  

According to Spotify's developer documentation...    
- Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. This is a value between 0 and 1, where 0 is the least danceable and 1 is the most danceable.
- Duration_min is the duration of the track in milliseconds. This is an integer value that is greater than 0.
- Energy represents a perceptual measure of intensity and activity. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy. This is a value between 0 and 1, where 0 is the lowest energy and 1 is the most energy.
- Tempo is the overall estimated tempo of a track in beats per minute (BPM). This is a value that is typically greater than 60, where the lower the value the "slower" the track.  
- Loudness is the overall loudness of a track in decibels (dB). This value typically ranges between -60 and 0, where -60 dB is the lowest loudness and 0 dB is the highest loudness. In this dataset, the value is averaged across the entire track to provide a single value.
- Instrumentalness predicts whether a track contains vocals or no vocals. In this context, "ooh" and "aah" sounds are not treated as vocals, whereas rap or spoken words are considered vocals. This is a value between 0 and 1, where 0 represents tracks with the greatest amounts of vocal content and 1 represents highly instrumental tracks.
- Valance describes that musical positiveness is conveyed by a track. This is a value between 0 and 1, where 0 is the most "positive" and 1 is the most "negative".         
