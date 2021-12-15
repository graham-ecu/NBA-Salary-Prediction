![image](https://user-images.githubusercontent.com/87883702/146094291-3785ec19-5072-4165-80e8-74684474fccf.png)
# NBA Salary Prediction

NBA organizations have been signing professional basketball players to increasingly lucrative deals in recent years and many have been disappointed by underperforming players. In other cases, the players themselves are forced to wonder why they are not being paid more when it seems like they are playing well and contributing to the team’s success. Both the team and the players want to make a deal that helps them win and earn money.

*How can NBA organizations and player agents predict player value so that a fair deal for both parties can be reached? What features drive value? Is there a way to accurately predict contract value based on prior performance?*

## Data
Three datasets were used in this analysis:
> * Player per 36 statistics
> * Player contract information
> * Team value

## Data Cleaning
*This section includes merging datasets, cleaning up strings, filling missing values, identifying repeat rows, etc.*

The full data cleaning notebook is available for review (https://github.com/graham-ecu/NBA-Salary-Prediction/blob/main/NBA%20Data%20Wrangling.ipynb).

## Exploratory Data Analysis (EDA)
*This section is all about visualizing the data, searching for trends and correlations, and understanding what the data really represents before diving into the model.*

The full EDA notebook is available for review (https://github.com/graham-ecu/NBA-Salary-Prediction/blob/main/NBA%20Data%20EDA.ipynb).

## Data Pre-processing
*In this section I split the data into train/test sets, standardize the numerical data, and create dummy features for the cateogrical data.*

The full pre-processing notebook is available for review (https://github.com/graham-ecu/NBA-Salary-Prediction/blob/main/Pre-processing%20and%20Training%20Data%20Development.ipynb).

## Model Development
*Finally, several models are trained and the results are compared using some simple scoring metrics.*

The full modeling notebook is available for review (https://github.com/graham-ecu/NBA-Salary-Prediction/blob/main/NBA%20Modeling.ipynb).

# Future Improvements
The main shortcoming of this proejct was the inaccuracy in predicting high contract values. This is due in large part to the scarcity of data for high earning players in this dataset.  I see the potential for great improvement if data from past years was included.  Some monetary adjustements would need to be made to account for inflation, but adding more datapoints would help to produce more accurate predictions in all areas. Though I ultimately decided that Random Forest was the best model to use with this dataset, KNN showed great potential and the addition of more data would give the model closer neighbors to work with for the data points it was least accurate at predicting.
