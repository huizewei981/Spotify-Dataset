# Spotify-Dataset


## Project Overview:

In this project, we'll be looking in to potential factors that may contribute to the popularity of a given song on spotify. Also, finding the music trends throughout years.

## Data Source:
There are more than 170,000 songs have been collected in this dataset, including 78 variables and released years between 1921 and 2020. Each song has it's unique id generated by spotify. 

#### Numerical:
acousticness (Ranges from 0 to 1)
danceability (Ranges from 0 to 1)
energy (Ranges from 0 to 1)
duration_ms (Integer typically ranging from 200k to 300k)
instrumentalness (Ranges from 0 to 1)
valence (Ranges from 0 to 1)
popularity (Ranges from 0 to 100)
tempo (Float typically ranging from 50 to 150)
liveness (Ranges from 0 to 1)
loudness (Float typically ranging from -60 to 0)
speechiness (Ranges from 0 to 1)
year (Ranges from 1921 to 2020)
#### Dummy:
mode (0 = Minor, 1 = Major)
explicit (0 = No explicit content, 1 = Explicit content)
#### Categorical:
key (All keys on octave encoded as values ranging from 0 to 11, starting on C as 0, C# as 1 and so on…)
artists (List of artists mentioned)
release_date (Date of release mostly in yyyy-mm-dd format, however precision of date may vary)
name (Name of the song)

#### Acknowledgements:
Thanks to Yamac Eren Ay for creating the dataset using Spotify Web API, Spotipy (Python module for Spotify web servers).
Data can be found at: https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks


## Summary 

The graph shows the distribution of songs been published from each year. The number of published songs was not stable until around 1950, and in 2018 it reached the historically highest point which is 2,103 number of songs published. 

(Fun Fact: Rock & Roll dominated popular music in the mid 1950s and late 1950s.)

Here we can see the popularity ranking by artists:

Dashboard -1 

<a href="https://ibb.co/NSrpwtS"><img src="https://i.ibb.co/Src0q5r/Screen-Shot-2020-12-30-at-10-26-11-PM.png" alt="Screen-Shot-2020-12-30-at-10-26-11-PM" border="0"></a>







