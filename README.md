# Spotify-Music-Popularity-Analytics

## Executive summary
* As more and more people switch away from traditional music platforms (such as radio and CD player), Spotify, the digital music streaming giant, is looking to grow their subscriber base by understanding and predicting what kind of content is going to be popular.
* This project will analyze the music available on Spotify, including artist, albums, tracks, market, genre, lyrics, etc.

## Why our project/analysis is needed
* Spotify wants to find the next favorite music. Therefore, our analysis will help Spotify understand the various music trend around the world and the track popularity. This insight will help in deciding what to invest on next.

## What stakeholders want to know.
* Stakeholders want to know which genre has the highest popularity, which music are similar, which artist has the highest followers, and which music has the highest market availability.

## Brief description of proposed analyses/reports to accomplish the business case.
* The business case will be accomplished through the analysis of music popularity, artist with the highest popularity, the average market availability per track/album.

## Data Source:
https://www.kaggle.com/datasets/saurabhshahane/spotgen-music-dataset

## Spotify database:
* SpotGenTrack Popularity Dataset
* The data was collected from Spotify and Genius throughout their respective API's.


## Spotify database:
*773.84 MB: Separated csv files with the corresponding information of the following elements: Tracks, Artists and Albums.
* Album ranges from 0 to 75,510, without gaps. Artist ranges from Juliano Cezar to Something For Kate.
* Attributes including artist, album type, music title, available markets, country, release date, track popularity, etc.

## Tools:
### Python
* data cleaning: treating the nulls, treating the duplicates
* pre-processing: dropping, feature engineering
### MySQL
* normalization until third normal form (3NF)
* denormalization for populating desired tables
### Tableau
* exploratory data analysis
* visualization
