# DA_SSSD-Basketball-Players-Stats: UE18CS312-Data analytics project 
## Team members: Swaroop BS, Sudharmendra GV, Darshan Pirgal, Sujith K

# To run the code:
$ cd /required_directory

$ git clone https://github.com/Sujith1910/DA_SSSD-Basketball-Players-Stats.git

Requirements:
Software or Library | Version
------- | ---------
Python | 3.6 or greater
Numpy | 1.18.2
Pandas | 1.0.3
Seaborn | 0.10.0
Matplotlib | 3.2.1

The repository contains 3 main folders: 
1. datasets
2. models
3. preprocessing

The main datasets used for the project are taken from: https://www.kaggle.com/drgilermo/nba-players-stats

Contents of datasets:
1. Players.csv - used for visualization of player heights in /preprocessing/Visualization1.ipynb
2. Seasons_Stats.csv - used for data cleaning and preprocessing in /preprocessing/Season_stats_Preprocessing.ipynb (which creates the normalized_dataset.csv and modified_season_stats.csv

Contents of preprocessing:
1. Players_preprocessing.ipynb - used for cleaning the Players.csv
2. Season_stats_preprocessing.ipynb - used for cleaning the Seasons_Stats.csv which is later used for creating two linear regression models.
3. Visualization1.ipynb - used for visualizing the distribution of heights and weights of players and also plotting the colleges which produced the maximum players.
4. Visualization2.ipynb - used for visualizing the state-wise heights of players across the country.
5. Visualization3.ipynb - used for plotting various technical aspects of player's skills.

Contents of models:
1. Player_Efficiency_Rating_model.ipynb - used to predict the Player efficiency rating (PER) of a player for the 2017 season using Linear Regression.
2. Turnover_model.ipynb - used to predict the Turnover Value of a team for the 2017 season using Linear Regression.











