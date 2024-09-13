# Music EDA and Recommendation System

## Overview
This project involves an exploratory data analysis (EDA) of a music dataset and the development of a recommendation system. The dataset includes various features of songs, such as acousticness, danceability, energy, and popularity, spanning multiple decades. The goal is to analyze trends, visualize data, and build a recommendation system based on song features.

## Key Components
1. **Data Loading and Preprocessing**:
   - Load datasets: `data.csv`, `data_by_artist.csv`, `data_by_genres.csv`, `data_by_year.csv`.
   - Preprocess data by adding a "decade" column and categorizing features into technical and non-technical branches.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze and visualize trends over decades.
   - Examine popular artists and genres.
   - Correlation analysis of song features.

3. **Dimensionality Reduction and Clustering**:
   - Apply PCA and t-SNE for dimensionality reduction.
   - Use KMeans clustering to group similar songs.

4. **Recommendation System**:
   - Build a recommendation system using cosine similarity.
   - Provide functions to search for songs and get similar song recommendations.

## Technologies Used
- **Python**: Core programming language.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical operations.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning algorithms for clustering and dimensionality reduction.
- **Plotly**: Interactive visualizations.

## Visualizations

### Acoustic trends
![image](https://github.com/user-attachments/assets/3e8ada95-4473-4efb-a6a0-cf5242edda44)

### Correlation Matrix
![image](https://github.com/user-attachments/assets/25679326-240e-452f-9846-9a385582a2e2)

### Elbow Method to find optimal number of clusters
![image](https://github.com/user-attachments/assets/e89d98b6-24e1-49cd-aca2-e9cd550bed58)

### Recommended songs based on a given song
![image](https://github.com/user-attachments/assets/a8501b9c-a8fc-423e-bea1-240b398a9741)
  
## Conclusion
This project provides a comprehensive analysis of music data and demonstrates the use of machine learning techniques to build a recommendation system. The visualizations and insights derived from the EDA help in understanding the trends and characteristics of music over the years.

## How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/overlordiam/EDA-Music-Recommendation.git
   cd EDA-Music-Recommendation
   ```

3. **Run the Jupyter Notebook**:
   Open `Music-EDA.ipynb` in Jupyter Notebook and run the cells to see the analysis and recommendation system in action.

## Acknowledgements
- The datasets used in this project are sourced from [Spotify](https://www.spotify.com) and other music data providers.
- Special thanks to the open-source community for providing the tools and libraries used in this project.
