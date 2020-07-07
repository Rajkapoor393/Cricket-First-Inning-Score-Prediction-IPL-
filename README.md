# Cricket First inning Score Prediction(IPL) - Deployment 
![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![scikit-learnn](https://img.shields.io/badge/Library-Scikit_Learn-orange.svg)
• This repository consists of files required to deploy a ___Machine Learning Web App___ created with ___Flask___ on ___Heroku___ platform.

• If you want to view the deployed model, click on the following link:<br />
Deployed at: _https://ipl-first-innings-score.herokuapp.com

• Please do ⭐ the repository, if it helped you in anyway.

• A glimpse of the web app:

 
 ## Problem Statement:
 Build a model to predict the score(in terms of range) of any IPL match
 
 ## Dataset :
 The dataset 'ipl.csv' consists of ball-to-ball informations about every match of IPL from  **Season 1 to 10**i.e(2008 to 2017)
Dataset consists following columns:
- mid: Unique match id.
- date: Date on which the match was played
- venue: Stadium where match was played.
- bat_team: Bating team name
- bowl_team: Bowling team name
- batsman: Batsman who faced that particular ball
- bowler: Bowler who bowled that particular ball.
- runs: Runs scored by the team till that point of instance
- wickets: Number of Wickets fallen of the team till that point of instance.
- overs: Number of Overs bowled till that point of instance.
- runs_last_5: Runs scored in previous 5 overs.
- wickets_last_5: Number of wickets that fell in previous 5 overs.
- striker: max(runs scored by striker, runs scored by non-striker).
- non-striker: min(runs scored by striker, runs scored by non-striker).
- total: Total runs scored by batting team at the end of first innings.
## Dependencies:
- Python - 3.6
• Scikit-Learn
• Pandas
• Numpy
• Matplotlib
• Seaborn
• Google Colaboratory

## Algorithms Used:
- Linear Regression
- Ridge Regression
- Lasso Regression

## Future Scope:
- Implement this problem statement using Artificial Neural Network
- Implement the role of Venus for the prediction of score
- Add columns in dataset of top batsmen and bowlers of all the teams.
