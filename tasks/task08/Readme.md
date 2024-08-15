# Joke Recommendation System Using Cosine Similarity

## Overview

This project focuses on building a joke recommendation system using collaborative filtering with cosine similarity. The system recommends jokes to users based on their preferences and the preferences of similar users.

## Objectives

- **Data Preprocessing**: Combine user ratings datasets, handle missing values, and prepare the data for similarity computation.
- **Cosine Similarity Calculation**: Compute the cosine similarity matrix to identify users with similar preferences.
- **Joke Recommendation**: Develop a function to recommend jokes based on the aggregated ratings of similar users.
- **Evaluation**: Test the recommendation system and display example recommendations for a specific user.

## Achievements

1. **Data Loading and Initialization**:
    - Successfully loaded the jokes dataset and user ratings datasets.
    - Initialized necessary libraries for data processing and similarity computation.

2. **Data Preprocessing**:
    - Combined multiple user ratings datasets into a single dataframe.
    - Filled missing values in the ratings data with the mean rating for each joke.
    - Split the data into training and testing sets for evaluation.

3. **Cosine Similarity Calculation**:
    - Computed the cosine similarity matrix to measure the similarity between users.
    - Identified users with similar preferences based on their ratings.

4. **Joke Recommendation**:
    - Developed a function to recommend jokes by aggregating the ratings of similar users.
    - Generated a list of top-rated jokes for each user based on the preferences of similar users.

5. **Evaluation and Example**:
    - Tested the recommendation function by providing joke recommendations for a specific user.
    - Displayed the top recommended jokes, demonstrating the system's effectiveness.

## Why These Achievements Matter

- **Personalized Recommendations**: By leveraging the preferences of similar users, the system provides personalized and relevant joke recommendations.
- **Collaborative Filtering**: The use of collaborative filtering ensures that recommendations are based on the collective preferences of the user community, leading to more accurate and enjoyable suggestions.
- **Data-Driven Insights**: The system uses data-driven methods to understand user preferences and make recommendations, enhancing the user experience.
