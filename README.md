# Spotify Songs Exploratory Data Analysis (EDA)

 Project Overview
Comprehensive exploratory data analysis of Spotify songs dataset, uncovering patterns in audio features, popularity trends, and genre characteristics. This project demonstrates end-to-end data analysis workflow from data cleaning to insight generation.

Objectives
1. Understand distributions of key audio features
2. Identify correlations between song characteristics
3. Analyze popularity trends over time
4. Compare audio features across genres
5. Discover patterns through clustering analysis

 Dataset
- **Source**: [Spotify Tracks Dataset on Kaggle](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset)
- **Size**: ~114,000 tracks
- **Features**: 21 columns including audio features, popularity, artist, and genre information
- **Time Period**: 1921-2020

 Technologies Used
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Jupyter Notebook**: Interactive analysis and visualization
- **Git**: Version control
- **GitHub**: Portfolio presentation

 Key Insights

 1. Audio Feature Distributions
- Most songs have moderate danceability (0.5-0.7) and high energy (0.6-0.9)
- Acousticness shows a bimodal distribution with peaks at both extremes

 2. Strong Correlations
- Loudness and energy are strongly positively correlated (r ≈ 0.75)
- Acousticness and energy show strong negative correlation (r ≈ -0.67)

 3. Popularity Trends
- Songs from the 1960s-1990s show highest average popularity
- Recent decades show more variability in popularity scores

 4. Genre Analysis
- Pop and Rock dominate the dataset
- Electronic music shows highest danceability scores
- Classical music has highest instrumentalness scores

 5. Clustering Results
- 4 distinct song clusters identified:
  - **Cluster 0**: High energy, high danceability (party songs)
  - **Cluster 1**: Acoustic, low energy (chill/acoustic)
  - **Cluster 2**: High speechiness, low instrumentalness (rap/hip-hop)
  - **Cluster 3**: High valence, moderate tempo (happy/uplifting)ECT-001
