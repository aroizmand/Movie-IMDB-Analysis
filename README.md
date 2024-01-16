# Actor Collaboration Network Analysis

## Introduction

This Jupyter Notebook provides an in-depth analysis of actor collaboration networks, utilizing a comprehensive dataset of movies and TV shows. Our primary focus is on deciphering the complex web of actor collaborations and uncovering insights into the social structure of the film industry. The dataset encompasses a variety of details such as movie titles, genres, cast members, directors, IMDb scores, and other pertinent attributes.

## Objectives

- Conduct a detailed network analysis to explore actor collaboration patterns within the industry.
- Identify influential actors and key communities within the network using graph theory metrics.
- Examine the relationship between actor collaborations and movie ratings and revenues.
- Employ machine learning models to predict IMDb ratings for future movies based on various features, including actor collaboration networks.

## Dataset Source

The dataset is compiled from IMDb and includes various aspects of movies and TV shows. source: (https://github.com/victoramsantos/netflix-backend/blob/master/movie-scraper/resources/dataset/IMDB-Movie-Data.csv)

## Key Analyses and Visualizations

- **Network Graphs**: Visualization of the actor collaboration network, highlighting the most connected actors and significant communities.
- **Centrality Measures**: Analysis of the actors' roles in the network, utilizing metrics such as degree centrality, eigenvector centrality, and betweenness centrality.
- **Community Detection**: Identification of closely-knit actor groups within the network.
- **Influence of Actors on Movie Ratings and Revenues**: Investigation into how actor collaborations impact a movie's commercial success and critical reception.
- **Machine Learning Models**: Development of predictive models to forecast IMDb ratings for new movies, integrating insights from the actor collaboration network analysis.

## Tools and Libraries Used

- `NetworkX`: For constructing and analyzing the network graph.
- `Pandas` and `NumPy`: For data manipulation and analysis.
- `Matplotlib` and `Seaborn`: For data visualization.
- Machine learning libraries (like `scikit-learn`) for predictive modeling.
