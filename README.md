# Movie Recommender System with Cosine Similarity and Streamlit Frontend

## Introduction

This Movie Recommender System is a collaborative filtering recommendation engine that suggests movies to users based on their preferences and similarities with other users. The system utilizes cosine similarity to measure the likeness between movies and provides a user-friendly interface using Streamlit.

## Collaborative Filtering and Cosine Similarity

Collaborative filtering is employed to predict user interests by finding similarities between movies. Cosine similarity is used to measure the similarity between two movies based on user ratings. The cosine similarity matrix is calculated to determine how alike different movies are.

## Streamlit Frontend

Streamlit is utilized to create a simple and interactive web interface for users to input their movie preferences and receive personalized recommendations. The frontend includes features like user input, recommendation display, and an engaging interface.

## System Workflow

1. **Data Collection:** Gather a dataset of user ratings for movies (e.g., MovieLens or IMDb datasets).
2. **Data Preprocessing:** Clean and organize the dataset, handling missing values.
3. **Cosine Similarity Calculation:** Compute the cosine similarity matrix between movies based on user ratings.
4. **User Input:** Allow users to input their movie preferences or select movies from a list.
5. **Recommendation Generation:** Generate a list of recommended movies based on user input and cosine similarity.
6. **Streamlit Integration:** Use Streamlit to create a web interface for user interaction.

## Streamlit App Features

- **User Input:** Section for users to input their movie preferences or select movies.
- **Recommendation Display:** Section displaying the recommended movies based on user input.
- **Interactive Interface:** Utilize Streamlit widgets for dynamic user experience.
- **Visualizations (Optional):** Include visual elements like movie posters or ratings distribution.
