# Board_Games_Review_Prediction

Machine Learning Project for predicting the rating of a board games on various parameters.<br \>
Data set obtained from the github repo : [a link](https://github.com/ThaWeatherman/scrapers/blob/master/boardgamegeek/games.csv)<br \>
There are 81,000 entries and 20 parameters of which the useful ones are selected for training.<br \>
Linear Regression Model and Random Forest Regression used for training the models. <br />
The data set included fields which was rated by zero users. Such entries were removed to obtain the Normal Distribution. <br />
Seaborn Library is used to obtain the heatmap for visualizing the relationship among the variables.<br \>
Mean Squared Error obtained for Random Forest(1.489) was lesser than Linear Model(2.148). <br \>
