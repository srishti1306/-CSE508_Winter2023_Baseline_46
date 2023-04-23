# MUSIC RECOMMENDATION SYSTEM
## Information Retrieval Course Project

By Bhavesh Sood, Isha Sehrawat and Srishti Singh Information Retrieval (CSE508) under the guidance of Dr. Rajiv Ratn Shah from Indraprastha Institute of Information Technology, Delhi.

## INTRODUCTION
* ### MOTIVATION
With the advent of new technology and platforms, the music industry has experienced significant growth over the years. There has been a revolution in the way people access and consume music. The distribution of music digitally, with the rise of platforms like Spotify, Apple Music, etc., has made it easier to connect artists with listeners globally. More and more users are joining online streaming platforms. The revenue from music streaming has also been increasing every year since 2010. To meet the needs of these platforms, it's important to focus on improving user experience, music discovery, and data analysis. Platforms can improve the user experience by providing personalized recommendations, curated playlists, better search functionality, and user-friendly interfaces. Music streaming platforms can enhance music discovery by providing users with better ways to find new music they will enjoy. This could include features such as genre-based recommendations, new release notifications, and more personalized recommendations.

* ### PROBELM STATEMENT
With the vast amount of songs in the streaming services database, it's overwhelming for users to be up to date with the newest releases and the songs matching their mood. While many music recommendation approaches are available, they rarely take into account the user’s emotions at the current time. They have underutilized the lyrics of the songs that the users have listened to in the past. We are planning to create a novel music recommendation system that takes emotions, user’s playing history as well as preferences and the lyrics of the music to recommend the most relevant songs and achieve user satisfaction.

* ### NOVELTY
Most of the papers we came across used features like audio, timestamp, user history, and lyrics content to perform recommendations. Lyrics, which have not been worked upon by almost all of the papers we found, are another crucial feature of songs that can be used to extract more information, like emotions associated with it. We utilized some new features to improve upon the recommendation quality. We made use of sentiment pertaining to the lyrics and used CNNs to get a more representative embedding for the lyrics.

## DATASET
We used the Million Song Dataset, which consists of the metadata and audio features of around 1M songs. We used either a subset of data spawned from this dataset for training and testing our model. We used Song_data.csv, 10000.txt and user_song_list_index_with_lyrics.csv. 

* The Song_data.csv is a csv file that contains song_id, title, release(album name), artist_name and year(of release). 
* The 10000.txt contains the count play of 10,000 songs, including the user ID, song ID, and the number of times each song was played by the user.
* The user_song_list_index_with_lyrics.csv consists of all these features present in the dataset obtained from merging 10000.txt and song_data.csv. It also contains lyrics of all the corresponding songs.

## INSTRUCTIONS
### USING DATASET 
From the Dataset folder in Github, copy the drive link. Make a shortcut in your MyDrive. It consists of the required datasets. Mount your Google Drive while running the code.

### RUNNING THE CODE
Download the .ipynb file and upload it on Colab. Run the code and mount your Google Drive. 

## MEMBERS
* Bhavesh Sood (2019355)
* Isha Sehrawat (2019046)
* Srishti Singh (2019114)
