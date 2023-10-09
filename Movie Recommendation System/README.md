# Movie Recommendation System

Welcome to the Movie Recommendation System project! This project aims to build a movie recommendation system that suggests similar movies based on user input. The recommendation system uses natural language processing (NLP) techniques and cosine similarity to provide movie suggestions.

## Introduction

In the age of streaming services and vast movie libraries, finding the right movie to watch can be challenging. This movie recommendation system aims to alleviate this issue by suggesting movies similar to a user's input. It utilizes a dataset of movie information, including genres, keywords, cast, and crew, to make recommendations.

## Dataset

The project uses the TMDb (The Movie Database) dataset sourced from [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata), containing information about thousands of movies. The dataset includes details like movie titles, overviews, genres, keywords, cast, and crew. This data is essential for building the recommendation system.

## Project Overview

- **Data Loading**: We load the TMDb dataset into Pandas data frames.
- **Data Preprocessing**: We clean, transform, and prepare the data for model training.
- **Model Building**: We build a recommendation system using NLP techniques and cosine similarity.

## Data Preprocessing

- We clean the dataset, remove missing values, and handle duplicate entries.
- We convert string representations of lists of dictionaries into specific values.
- We extract the names of the top actors and the movie director.
- We perform text preprocessing, including tokenization and stemming.
- We create a 'tags' column by combining relevant movie information.

## Model Building

- We use the CountVectorizer to convert text data into numerical vectors.
- We calculate cosine similarity between movie tags to find similar movies.
- We create a 'recommend' function to suggest similar movies based on user input.

## Contributing
Contributions to this project are welcome! If you have suggestions, improvements, or bug fixes, please open an issue or submit a pull request.
