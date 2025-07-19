🎬 Movie Recommendation System

📌 Objective
To develop a Movie Recommendation System that accurately suggests movies to users based on their preferences and viewing history, enhancing user experience by reducing search time and increasing personalized content discovery.

🗂️ Dataset
movies.csv
Contains movie information such as movieId, title, and genres.

ratings.csv
Contains user ratings data with columns userId, movieId, rating, and timestamp.

📍 Source: MovieLens Dataset

📝 Approach
Data Loading & Exploration
Loaded both datasets to understand their structure and distribution.

Data Preprocessing

Merged movies and ratings datasets on movieId.

Cleaned missing or duplicate values if any.

Model Building

Collaborative Filtering (Memory-based) using Cosine Similarity or Pearson Correlation to find similar users and recommend movies based on ratings.

Content-Based Filtering using genres to recommend similar movies.
