# Predicting-Outcomes-of-NBA-Games
Project was done in Python and its purpose is to predict the outcome of NBA games using Machine Learning

Link to Kaggle Site: https://www.kaggle.com/datasets/nathanlauga/nba-games

There were 5 datasets in the Kaggle Site

- games.csv
  - Has data from every game starting from the 2003-2004 NBA Season and up until March 12, 2022
  - Has metrics like how many points/rebounds/assists/etc each team had in each game as well as who won the game
  
- games_details.csv
  - Has data regarding the details of each game at an individual player level
  - Has the stats of each player in each of the games from the games.csv dataset

- players.csv
  - Has data regarding the details of each player
 
- ranking.csv
  - Has data regarding the records/rankings of each team for every day
 
- teams.csv
  - Has data regarding the details of each team

- The `Combining Datasets.ipynb` file combines all of the datasets and the result is a finalized dataset at an individual player level with data from all of the original datasets

- The `Finalizing Dataset.ipynb` file groups the dataset created from the `Combining Datasets.ipynb` file at a game level, creates the metrics that will be used as input features into the Machine Learning models, and creates the `Dataset for ML Modeling.csv` file

- The `EDA and ML Modeling.ipynb` file does exploratory data analysis on the `Dataset for ML Modeling.csv` file, creates some Machine Learning models, and performs hyperparameter tuning on these Machine Learning models
