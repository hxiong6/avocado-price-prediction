# avocado-price-prediction

The objective of this project is to make prediction of the price of avocado based on the season of year, type of avocado (regular, or organic), region, quantity sold and etc. 

This is a school project for course: data mining. 

- Visualized fluctuation of avocado price throughout the year using catplot, violinplot and etc.

- Data pre-processing (standardization for numerical values, one-hot encoding and etc.) before **regression** model training 

-	Built prediction model using common machine learning algorithms, such as KNNregressor, DecisionTreeRegressor, RandomForestRegressor and etc. 
	
- Tuned for optimal hyperparameters using RandomizedSearchCV. Improved R2 score from 0.83 to 0.87 for RandomForestRegressor

- feedback/improvement for the project 

 1) use **adjested R square score** instead to address the issue of too many variables used in the model (after pd.get_dummies(), 77 variables) that the model could potentially pick up noise in the dataset. Use adjusted R square score to determine the optimal number of predicators
