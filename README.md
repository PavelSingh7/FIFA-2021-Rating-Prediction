In this Project we will be analysing individual players abilities, skills and based on that will be looking for some insights.

# About the Dataset

The FIFA 2021 dataset consists of more than 17,000 active players around the world and more than 100 attributes for every player.
The dataset has been obtained online from Kaggle and is uncleaned and needs a lot of cleaning and preprocessing.
Among 107 attributes in the data, most of them are the skillsets of the players such as pace, jumping, attack, defence, speed, passing, shooting, dribbling etc. 
A few other attributes consist of Players information such as Name, country, club, contracts, photo, rating, potential etc.

There are a lot of attributes which are of no use during our analysis so during pre-processing we will be dropping them.

# OBJECTIVES FOR ANALYSIS

We will be working on a bunch of objectives for this project which will include data visualization and machine leaning models. 

## These are our objectives for this project:

•	  Top 5 highest rated players. 

•	  Which player has the highest potential in game?

•	  Top 5 players for every playing position.

•	  Team of the year according to every highest rated position.

•	  Most valuable player?

•	 Which players are highly valuable but still underpaid.

•	  Most preferred foot by players?

•	Longest stay in the Club

## Machine Leaning models objectives:

•	A regression model to predict rating based on skills of a player.

# Tools to be used for analysis:

•	Excel (Data understanding)

•	Python (Data preprocessing, ML models/Data Visualization)

•	Tableau (Data Visualization) 


# Machine Learning Problem
FIFA ratings can be affected by position of the player too. There are around 1500 goalkeepers in the dataset and rest are outfield players. We cannot predict the rating of an outfield player based on his GK skills. So this dataset is for outfield players (excluding goalkeepers).

Rating of players is mostly based on the skills of the players, there are around 35 attributes on whcih FIFA try to predict Overall Rating of a Player
Also players international reputation also plays a crucial role as based on stars ( 1 to 5) players recieve certain rating too ( for eg - a player with 1 or 2 stars wont get any points. A player with 5 stars and rating above 75 will get 3 rating points)

### We will be training the data based on 2 algorithms, Lasso regression and Gradient Boosting Regressor and compare the accuracy of the models.
These two algorithms work best for high-dimensionality dataset.

For Lasso Regression - Though are dependent variables are on the same scale but we will still Feature Scale our attributes to ensure that the model generalizes well to unseen data

For Gradient Boosting Regressor - no feature scaling is required

# Gradient Boosting Regressor is providing 97% accuracy and Lasso Regression is providing 89% 
 ## It is better than Lasso because Gradient Boositng Regressor works well for a data with Weak Linear Relationship

 # * NOTE ( Check the Final Result csv file for the affect on international repution on ratings) * 

