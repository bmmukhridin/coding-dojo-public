# Sales Predictions

## Performing analysis on Sales Prediction dataset and make prediction using machine learning models.

### Author: Mukhriddin Bakhramov

#### Business problem:

Uncover some potential KPI's (Key Performance Indicator) between store location, type, item-type and other data collected to accurately predict total sale of an item and ultimately improve revenue by providing data-driven-decision and make "what makes this item/store successful" reproducable for future business iteration.

### Methods
* remove all duplicates to avoid repeating data
* correct all data inconsistencies (mislabled, unnecessary extra character)
* Impute missing values to keep data integrity and avoid model prediction errors

Exploratory Data Analysis


* Quick glance of total of seles by Outlet eType:

![image](https://user-images.githubusercontent.com/73002669/231968123-05e46b46-d0b0-4061-a480-17ffc610dfd4.png)

Here we can see different distribution of stores and Maximum number of sales and get a better understanding of which store has higher sale count

![image](https://user-images.githubusercontent.com/73002669/231971192-ac4ac242-3812-4715-902b-1090f186cf0a.png)

Here we can see statistical summaries of various sales by size


### Models

* Linear Regression - Simple linear regression is a regression model that estimates the relationship between one independent variable and one dependent variable using a straight line.

* DecisionTree Regressor - A decision tree is a type of supervised machine learning used to categorize or make predictions based on how a previous set of questions were answered.

#### Recommendations:

* more data means more opportunity to find commonality for analysis and paterns for model predictions, we can't go wrong with adding more data in our dataset
* gather more relavant data like monthly sales to determine wheter a certain item is better suited as seasonal item or staple item in the store

Limitations & Next Steps:

* the use of simple machine learning model limits our capability to fine-tune our models to better understand patterns in our dataset
* next Step - Explore different and more complex machine learning models like RandomForest Regressor , Bagging Regressor , Elastic_Netto get a better feel and benchmark different model performance to one another.
