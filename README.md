# CineMatch: Personalized Movie Recommendations using Deep AutoEncoders

## Overview
This repository contains a movie recommendation system built using autoencoders. The system leverages the **MovieLens** dataset to provide personalized recommendations based on user preferences.

## Dataset
The repository includes the **MovieLens 1M** and **MovieLens 100K** datasets, which contain anonymous ratings of movies provided by users.
- **MovieLens 1M:** 1,000,209 ratings from 6,040 users on 3,900 movies.
- **MovieLens 100K:** A smaller version containing 100,000 ratings from 943 users on 1,682 movies.

### Dataset Files
- **ratings.dat**: Contains user ratings in the format `UserID::MovieID::Rating::Timestamp`.
- **users.dat**: Contains user demographic information in the format `UserID::Gender::Age::Occupation::Zip-code`.
- **movies.dat**: Contains movie details in the format `MovieID::Title::Genres`.

## Source Code
- **MovieRecommendationSystemUsingAutoencoders_code.ipynb**: A Jupyter Notebook implementing the recommendation system using deep learning techniques.

## Features
- Collaborative filtering using autoencoders
- User and movie embedding representations
- Personalized movie recommendations

## Dependencies
Install the required libraries using:
```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommendation.git
   ```
2. Navigate to the directory:
   ```bash
   cd movie-recommendation
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook MovieRecommendationSystemUsingAutoencoders_code.ipynb
   ```
4. Follow the notebook steps to train and generate recommendations.

## Citation
If you use the MovieLens dataset, please cite:

> F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4, Article 19 (December 2015), 19 pages. [DOI:10.1145/2827872](http://dx.doi.org/10.1145/2827872)

## License
This project is licensed under the MIT License. The MovieLens dataset is provided under its own usage license from GroupLens Research.

## Acknowledgments
Special thanks to **GroupLens Research** at the University of Minnesota for making the MovieLens dataset publicly available.


