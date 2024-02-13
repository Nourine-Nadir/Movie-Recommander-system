# Movie-Recommander-system
A Movie Recommender System implemented in Python using collaborative filtering and content-based filtering techniques. The system processes a dataset of 10,000 movies, extracting features such as keywords, genres, cast, and crew information to generate movie recommendations based on user input.


## Overview

The recommender system processes a dataset of 10,000 movies, combining information such as keywords, genres, cast, and crew details. The features are used to calculate cosine similarity scores, enabling the system to generate relevant movie recommendations.

## Key Features

- **Data Preprocessing**: The dataset, consisting of movie and credits information, is loaded and merged to create a final dataset.
- **Text Processing**: String lists in the dataset are converted into Python lists using the `ast` module.
- **Feature Extraction**: Relevant features like keywords, genres, cast, and crew are extracted from the dataset and processed for further analysis.
- **TF-IDF Vectorization**: The movie tags are vectorized using TF-IDF (Term Frequency-Inverse Document Frequency) to represent the importance of each term in the dataset.
- **Collaborative Filtering**: The system employs collaborative filtering to calculate cosine similarity scores between movies, enabling personalized recommendations.
- **User Interaction**: Users can input a movie name, and the system finds a close match using the `difflib` library. Recommendations are then generated based on the selected movie.

## Usage

To use the Movie Recommender System:

1. Clone the repository.
2. Run the provided Python script.
3. Input a movie name when prompted.

The system will output a list of recommended movies based on the collaborative filtering approach.

Feel free to explore and enhance the recommender system according to your preferences and dataset.

## Dependencies

- Python 3.x
- NumPy
- pandas
- Matplotlib
- scikit-learn

## Author

[Nourine Mohammed Nadir]


