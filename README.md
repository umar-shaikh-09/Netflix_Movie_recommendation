# Netflix Movie Recommendation System

## Overview
This project utilizes **collaborative filtering** and **matrix factorization** techniques to provide personalized movie recommendations. By analyzing user ratings and movie data, the system predicts which movies a user is likely to enjoy.

## Dataset Information
- **Dataset Name**: `Netflix_Users_Movies.csv`
- **Description**: Contains movie ratings, genres, and user preferences.
- **Key Columns**:
  - `UserID`: Unique identifier for each user.
  - `MovieID`: Unique identifier for each movie.
  - `Rating`: Rating given by the user.
  - `Genre`: Genre of the movie.
  - `Title`: Movie title.

## Features
- **Collaborative Filtering**: Recommends movies based on user similarity.
- **Matrix Factorization**: Decomposes user-item matrix for better predictions.
- **Evaluation**: Uses RMSE (Root Mean Squared Error) to measure model accuracy.

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `pandas`, `numpy`: For data manipulation.
  - `scikit-learn`: For building machine learning models.
  - `surprise`: For collaborative filtering and recommendation algorithms.
- **Tools**: Jupyter Notebook
