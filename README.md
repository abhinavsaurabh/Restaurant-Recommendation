
# Restaurant Recommendation System

This project develops a Restaurant Recommendation System utilizing collaborative filtering algorithms, including Alternating Least Squares (ALS), Singular Value Decomposition (SVD), and Stochastic Gradient Descent (SGD).

## Project Overview

The system analyzes user preferences and restaurant features to provide personalized dining recommendations.
By implementing and comparing various collaborative filtering techniques, the project identifies the most effective algorithm for accurate recommendations.

## Dataset

The Yelp dataset serves as the foundation for this project, focusing on restaurants in Austin and Portland due to their substantial data volume.

## Algorithms Implemented

- **SVD (Singular Value Decomposition):** A matrix factorization method that decomposes the user-item interaction matrix to predict missing entries.
- **Cosine Similarity:** Measures similarity between users or items based on their interaction vectors.
- **ALS (Alternating Least Squares):** A matrix factorization technique that alternates between fixing user and item matrices to minimize error.
- **SGD (Stochastic Gradient Descent):** An optimization algorithm that minimizes the error in predictions by iteratively updating model parameters.

## Results

The performance of each algorithm was evaluated using Mean Squared Error (MSE) for both Austin and Portland datasets:

| Model              | MSE (Austin) | MSE (Portland) |
|--------------------|--------------|----------------|
| SVD                | 17.73        | 18.15          |
| Cosine Similarity  | 17.73        | 18.22          |
| ALS                | 17.72        | 18.21          |
| SGD                | **2.52**     | **2.48**       |

The SGD algorithm achieved the lowest MSE, indicating superior performance in both cities.

## Conclusion

This project demonstrates the effectiveness of collaborative filtering algorithms in restaurant recommendation systems, with SGD providing the most accurate results.

## Repository Contents

- `Data_Preprocessing_Yelp_Dataset_.ipynb`: Notebook detailing data preprocessing steps.
- `Restaurant_Recommendation_System.ipynb`: Notebook containing the implementation of the recommendation system.
- `Project Presentation.pdf`: Slides summarizing the project.
- `README.md`: Project overview and documentation.

## License

This project is licensed under the MIT License.

For more details, visit the [GitHub repository](https://github.com/abhinavsaurabh/Restaurant-Recommendation).
