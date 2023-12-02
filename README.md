# big-data-bowl-2024-nfl-player-classifier
Predicting the Position of a NFL Player using engineered features from the big data bowl dataset and a Decision Tree Classifier

Dataset: https://www.kaggle.com/competitions/nfl-big-data-bowl-2024/data

Exploration:
Interceptions were not recorded in this dataset
Quarterback Sacks were not recorded in this dataset
Incomplete passes were not recorded in this dataset
Could consider over sampling since our dataset is not balanced
Some Birthdates are missing from the dataset

Data Cleaning:
Group similar NFL positions

Model Features:
BMI
Jersey Number
Top Speed
Maximum Acceleration
Aggression Score
Passes Caught
Scrambles (QB)
Penalty Records (dictionary)
Ball Carries

Model Tuning:
Grid Search Cross Validation (Cost Complexity Pruning, random state, criterion, max_depth)