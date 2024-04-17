<h1>Predictive Modeling for NBA Games: 2023-2024 Season</h1>

<h2>Description</h2>
This project encompassed the prediction of total offensive rebounds, game spread, and total points for the last 58 games of the 2023-2024 NBA Season. We started by gathering data, scraping boxscores from the 2023-2024 NBA season using the nba_api in python. From there, previous season data was collected on Kaggle from Nathan Luaga and additional game statistics spanning from the 2002-2003 and 2023-2024 seasons utilizing the nbastatR package. Data cleaning was necessary to merge and format this data into a one-row-per-game format. We calculated other metrics that we viewed to have possible importance in our models. We employed many high level modeling techniques including Random Forest, Stepwise, Lasso Regression, Gradient Boosting Machine modeling, Regression Trees, and Poisson regression.

<br />
<br />

We used cross-validation as our main form of analysis. This encompassed creating a train and a test dataset in order to calculate mean squared errors and mean absolute errors for each model. Ultimately, we opted to employ the mean absolute error as the criterion for selecting the final model for each category (Offensive Rebounds, Spread, and Total). We selected the mean absolute error due to its resilience to outliers and its ease of interpretation. To generate final predictions, we utilized the 2023-2024 season averages as inputs into the chosen model for each category.
<br />
<br />
The training dataset, testing dataset, 2023-2024 season average for all variables in our dataset, and our final predictions for the last 58 games are all attached. 
<br />
<br />
The full paper can be found in the link below:
<br />

### [Full Paper](https://acrobat.adobe.com/link/review?uri=urn:aaid:scds:US:88b47033-1a06-3406-8a91-cf99f1142bd2)

<br />
