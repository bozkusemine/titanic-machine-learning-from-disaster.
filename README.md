# Predicting the Survival of Titanic Passengers

**Table Of Content**

  1. Import Libraries

  2. Reading the Data

  3. Data Exploration

  4. Feature Engineering

  5. Model Building

Problem description: To frame the ML problem elegantly is very much important because it will determine our problem spaces. What algorithms we will select, what performance measure we will use to evaluate our model, and also how much effort we should spend tweaking it? The test set should be used to see how well our model performs on unseen data. For the test set, the ground truth for each passenger is not provided. It is our job to predict these outcomes. For each passenger in the test set, we use the trained model to predict whether or not they survived the sinking of the Titanic. We will use Cross-validation for evaluating estimator performance. We've two datasets are available, a train set and a test set. We'll be using the training set to build our predictive model and the testing set will be used to validate that model. This is a binary classification problem. To solve this ML problem, topics like feature analysis, data visualization, missing data imputation, feature engineering, model fine-tuning and various classification models will be addressed for ensemble modeling.

**Describing the data**

*pclass: Ticket class*

*sex: Sex*

*Age: Age in years*

*sibsp: # of siblings / spouses aboard the Titanic*

*parch: # of parents / children aboard the Titanic*

*ticket: Ticket number*

*fare: Passenger fare*

*cabin: Cabin number*

*embarked: Port of embarkation*
