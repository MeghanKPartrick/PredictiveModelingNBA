<h1>Predictive Modeling for NBA Games: 2023-2024 Season</h1>

<h2>Description</h2>
This project encompassed the prediction of total offensive rebounds, game spread, and total points for the last 58 games of the 2023-2024 NBA Season. We started by gathering data, scraping boxscores from the 2023-2024 NBA season using the nba_api in python. From there, previous season data was collected on Kaggle from Nathan Luaga. The last data collected from outside sources include all available game statistics between the 2002-2003 and 2023-2024 seasons. We utilized the nbastatR package to retrieve game logs for every target season. Data cleaning was performed in order to combine the data sets and format this data into a one-row-per-game format. We calculated other metrics that we deemed important in order to use these in our models. High level modeling techniques were used, including, Random Forest, Stepwise, Lasso Regression, Gradient Boosting Machine modeling, Regression Trees, and Poisson regression.

<br />
<br />

Our main form of analysis for these models was cross-validation. We used a train and a test dataset in order to calculate mean squared errors and mean absolute errors for each model. We ultimately chose to use the mean absolute error to choose the final model for each category (Offensive Rebounds, Spread, and Total). We chose to use the mean absolute error as it is less susceptible to outliers and is easier to interpret. In order to calculate final predictions, we input 2023-2024 season averages into the selected model for each category. 
<br />
<br />
The training dataset, testing dataset, 2023-2024 season average for all variables in our dataset, and our final predictions for the last 58 games are all attached. 
<br />
<br />
The full paper can be found in the link below:
<br />

### [Full Paper](https://acrobat.adobe.com/link/review?uri=urn:aaid:scds:US:88b47033-1a06-3406-8a91-cf99f1142bd2)

<br />
