# Prediction-of-Scrabble-Player-Ratings

## Project Overview
Welcome to the Scrabble Player Rating Prediction project hosted on Kaggle! This project aims to develop a predictive model that accurately estimates the ratings of human players based on their gameplay in Scrabble matches. The dataset comprises approximately 73,000 matches played between human players and three different bots, each representing varying skill levels: BetterBot, STEEBot, and HastyBot.

## Dataset Overview (https://www.kaggle.com/competitions/scrabble-player-rating)
The dataset encompasses multiple components, each offering insights into different aspects of the games:
1. Games Metadata (games.csv): This file provides essential metadata for each Scrabble game, including unique game IDs, player information, time controls, game outcomes, and additional game settings like lexicon used and time limits.
2. Gameplay Data (turns.csv): Detailed turn-by-turn data is available in this file, documenting each move's specifics, including player racks, move locations, points scored, and turn types.
3. Player Scores and Ratings (train.csv and test.csv): These files are crucial for the model's training and evaluation. 'train.csv' comprises players' final scores and their ratings before the game, used for training the model. 'test.csv' includes similar data but lacks the players' pre-game ratings, which the model aims to predict.

## Scrabble Gameplay
Scrabble is a classic board game where players take turns placing letter tiles on a board to form words. The points are determined by the letters played and their positions on the board. The player with the highest points at the end of the game wins.

## Solution Overview
This project report outlines a systematic approach to solving the challenge. The process includes extensive data preprocessing and feature engineering to transform raw features into informative metrics. Visualization of player statistics aids in understanding and cleaning up the data, preparing it for modeling.

1. Data Preprocessing and Feature Engineering
- Cleaning and Normalization: Ensure data consistency by cleaning and normalizing the dataset.
- Feature Engineering: Create new features to better represent player skills and strategies.
2. Data Visualization and Analysis
- Explore Player Statistics: Utilize data visualization techniques to identify trends, outliers, and patterns in player behavior.
3. Refinement: Further refine and clean the dataset, ensuring high-quality input for the models.
4. Model Development and Comparison
- Random Forest, XGBoost, and LightGBM: Experiment with these machine learning models using optimized hyperparameters.
5. Model Selection: Choose the best-performing model for accurate player rating predictions.


## Getting Started
To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Download the dataset from the provided Kaggle competition link.
3. Refer to the Jupyter Notebooks for detailed insights into data preprocessing, feature engineering, and model development.
4. Contribution Guidelines: We welcome contributions to enhance the project. If you have improvements, updates, or innovative approaches, feel free to submit pull requests. We value collaboration within the data science community.

## Acknowledgments
We acknowledge Kaggle for hosting the competition and providing a platform for collaborative data science projects. Special thanks to the community for their engagement and contributions.

## Contributers of this project
Spencer Stromback, Jessica Cheng, Cindy Wang, Cody Ortloff, Yumi Yu

This README serves as a comprehensive guide to understanding the Scrabble Player Rating Prediction project, its goals, and the steps involved in data preprocessing, feature engineering, and model development.
