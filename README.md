# NFL Predictions

#### Background Information
The NFL is the most watched sport in America and with this years season set to start on Thursday, September 8, 2022, I wanted to train, test and run a model that would be able to predict wins and losses for each team based on previous results and a variety of stats compiled for each team on a game-by-game basis as well as season totals. There has to be some sort of variable that all of the great teams have in common whether it be salary cap based, performance based or predicted rankings for players and teams. We are trying to find a highly effective and efficient way to win more games and assemble a premier team year in and year out.

#### The Dataset
I am using a dataset titled ‘NFL Team Stats 2002-2021 (ESPN)’ that was scraped from ESPN containing 5357 rows and 39 columns. I will need to clean the data, find and replace null or missing values, rename columns, combine columns and determine the most important feature variables. Then, calculate overall win/loss and win percentage for each team based on the home/away results in the dataset. I will also be sorting the data by each year as well as by each team in order to properly run statistical analysis on both seasonal and team-by-team basis.

#### Modeling Techniques
Data visualization will be important for understanding trends in the data, especially for people who do not have a great knowledge of football and what each statistic means. Using seaborn and matplotlib for regression and linear graphs, pie charts and others will provide quality visuals. Supervised learning will be utilized in the form of similarity models, random forests, support vector machines (SVMs) and gradient boosting. Dimensionality reduction will be key in eliminating some of the 39 columns.

#### Challenges
Some of the challenges faced in this prediction would include off season acquisitions, retiring players and players who got injured either before or after the season starts. For further evaluation, creating a better model for prediction would be to use player and team rankings provided by a variety of sources. Determining the efficiency with player rankings incorporated would lessen or even eliminate a lot of the challenges faced. You can also add a player salary variable to check for positional contract trends impact on winning percentage.

#### Usefulness
Ways that this project could be useful would be for sports betting, fantasy football and general managers. Being able to fit the right blend of players together to create a team mathematically proven to have the best chance of succeeding would give teams a blueprint of what's currently winning as well as determine weaknesses that need to be accounted for is invaluable information. It will need to be adjusted every year to account for trends with play style.
