# Movie-Recommendation-System

This project is a Movie Recommendation System built using collaborative filtering techniques. It recommends movies to users based on their previous ratings and preferences. The system uses the MovieLens dataset for training and testing purposes.

## Features
1. Collaborative Filtering: Recommends movies based on user ratings.
2. Matrix Factorization: Implements a matrix factorization approach using Singular Value Decomposition (SVD) to decompose the user-movie rating matrix.
3. Performance Evaluation: Evaluates the recommendation accuracy using Root Mean Squared Error (RMSE).
4. Tuning Hyperparameters: Uses iterative processes like stochastic gradient descent for optimizing hyperparameters.
5. Visualization: Provides visual insights into the dataset distribution, rating patterns, and model performance.

## Dataset
The project uses the MovieLens dataset provided by MovieLens, which contains millions of user ratings for movies.

## Model Overview
1. SVD for Matrix Factorization: Uses SVD to decompose the user-item interaction matrix.
2. Evaluation: The model performance is evaluated using RMSE.
3. Tqdm: Implements progress bars for better tracking of the training process.

## Libraries Used
Pandas: For data manipulation and preprocessing.

NumPy: For numerical computations.

Scikit-learn: For matrix factorization and performance evaluation.

Matplotlib: For visualizing rating distributions and model performance.

Tqdm: For progress tracking.
