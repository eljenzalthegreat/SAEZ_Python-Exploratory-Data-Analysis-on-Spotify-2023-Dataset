## SAEZ_Python-Exploratory-Data-Analysis-on-Spotify-2023-Dataset

# Spotify 2023 Dataset Analysis
#### This project provides an in-depth analysis of the 2023 Spotify dataset using Pandas for data manipulation and Matplotlib and Seaborn for data visualization. Key areas of investigation include general dataset statistics, trends over time, top-performing artists and tracks, as well as relationships between musical attributes and streaming counts.


## Basic Descriptive Statistics
![image](https://github.com/user-attachments/assets/d4915a6b-ce42-44ae-8ffb-6940a7a4b3e8)
#### The distribution of release years shows that music from the 20th century is less represented, likely because tracks were only accessible through physical media like vinyl and CDs, rather than digital platforms.

![image](https://github.com/user-attachments/assets/472f244a-ac86-4f03-9593-1d50c391bbda)
#### The artist count distribution reveals that most tracks are produced by single artists, while tracks with multiple artists are outliers.

## Streams Column
#### Mean of streams: 514137424.93907565
#### Median of streams: 290530915.0
#### Standard deviation of streams: 566856949.0388832

## Released Year and Artist Count
#### Released Year Distribution: The highest number of releases occurred in 2022, followed by 2023, then 2021.
#### Artist Count: Generally low across tracks, with a few outliers.

# Top Performers
#### Which track has the highest number of streams? Display the top 5 most streamed tracks.
#### Who are the top 5 most frequent artists based on the number of tracks in the dataset?

## Most Streamed Tracks: The top 5 tracks by streams are:

![image](https://github.com/user-attachments/assets/80ae656b-60aa-42c0-a252-dd76fb2f933b)


## Most Frequent Artists (Based on track frequency in the dataset)

![image](https://github.com/user-attachments/assets/cf8877d9-d10a-4d54-9a97-d9809016b955)


# Trends
#### Analyze the trends in the number of tracks released over time. Plot the number of tracks released per year.
#### Does the number of tracks released per month follow any noticeable patterns? Which month sees the most releases?

## Yearly Release Trends:

![image](https://github.com/user-attachments/assets/2ed8e013-1837-46ff-9ccb-b65d614a85de)

#### The highest number of releases occurred in 2022, with a slight decline in 2023.

## Monthly Release Patterns:

![image](https://github.com/user-attachments/assets/49612532-9c5b-498e-9a96-40832755cff4)

#### The month with the most releases is January (133 tracks), with a general trend of peaks and valleys in other months. August has the lowest release count, followed by an increase in November and a decrease in December.

## Genre and Music Characteristics
![image](https://github.com/user-attachments/assets/cb000ae3-1e75-4005-8754-4ba423f9bc4d)

## Which attribute influences the number of streams the most?
We can observe that Danceability % influences the number of streams the most.

## Information we can get from the graphs above:
#### • As the Danceability percentage rises, the number of streams tends to increase as well. However, this relationship is not strictly linear, meaning that Danceability alone does not fully determine a track's streaming popularity.¶
#### • There doesn't appear to be a clear or linear correlation between the number of streams and BPM (beats per minute). This suggests that BPM is not a strong predictor of a track's popularity.

## Platform Popularity

## Advanced Analysis
![image](https://github.com/user-attachments/assets/c69edfa9-3bcd-4746-bc64-3053e064603d)

#### Based on the streams data, tracks in major keys generally attract more streams compared to those in minor keys. This trend suggests that songs in major keys tend to be more popular or appealing, though this pattern is not universally applicable. Tracks in major modes (such as C Major) often have an upbeat or happier tone, which might make them more suitable for mainstream listeners, while minor modes (like B Minor) typically evoke a more melancholic or emotional feel.

## Genre and Artist Appearances in Playlists and Charts
From the data, it's clear that certain pop artists such as Taylor Swift, The Weeknd, Harry Styles, NewJeans, Latto, and Jungkook frequently appear across platforms, consistently garnering more listeners both in playlists and on charts. These artists tend to dominate the mainstream music scene, as evidenced by their presence in major Spotify playlists and charts.

#### In addition, Latino artists like Feid, Karol G, and Bad Bunny are also high up in the rankings, showing strong international appeal, especially in Latin genres. These artists continue to gain momentum and popularity, indicating the growing influence of Latin music on global platforms.

#### Overall, the trend suggests that a combination of genre popularity (like pop and Latin music) and artist longevity (such as Eminem) leads to more frequent appearances in playlists and charts
