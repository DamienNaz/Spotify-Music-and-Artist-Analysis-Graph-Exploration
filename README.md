# Spotify Music and Artist Analysis - Graph Exploration

## 📌 Project Overview

This project explores Spotify music and artist data using **graph-based analysis**. By constructing and analyzing various types of graphs, we aim to uncover relationships between songs, artists, genres, and playlists. Additionally, we implement a **recommendation system** using the **PageRank algorithm** to suggest similar artists.

## 📂 Dataset Description

The dataset contains detailed information about Spotify tracks, including metadata, popularity metrics, and musical features. Some key attributes include:

- **Track Details:** `track_id`, `track_name`, `track_artist`, `track_popularity`
- **Album Details:** `track_album_name`, `track_album_release_date`
- **Playlist Details:** `playlist_name`, `playlist_genre`
- **Musical Features:** `tempo`, `acousticness`, `liveness`, `valence`, etc.

## 🔍 Graph Representations

We construct multiple graph structures to analyze different relationships:

- **Genre & Subgenre Graph:** Connects music genres and subgenres.
- **Artist & Playlist Genre Graph:** Links artists to the genres of playlists they appear in.
- **Artist Similarity Graph:** Represents similarity based on shared genres.
- **Artist & Song Graph:** Connects artists to their tracks.
- **Collaboration Graph:** Shows collaborations between artists.
- **Bipartite Artist-Genre Graph:** Links artists to their primary music genres.

## 📊 Key Analyses

- **Community Detection:** Using **Louvain** and **Spectral Clustering** to find music clusters.
- **Popularity Analysis:** Identifying the most popular songs and artists.
- **Graph Metrics:** Analyzing **PageRank, Betweenness Centrality**, and **Modularity**.
- **Recommendation System:** Suggesting similar artists using **PageRank-based ranking**.

## ⚡ Technologies Used

- **Python**, **NetworkX**, **Matplotlib**, **Pandas**, **Scikit-learn**
- **Graph Algorithms:** Louvain, Spectral Clustering, PageRank

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/DamienNaz/Spotify-Music-and-Artist-Analysis-Graph-Exploration.git
