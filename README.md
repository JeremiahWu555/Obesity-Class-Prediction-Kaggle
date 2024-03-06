# Obesity-Class-Prediction-Kaggle

This intends to do 2 things:
- A rough eda to understand the features
- A machine learning model


The eda will involve understanding the features both nummerically and categorically 
The machine model intends to preprocess the features based on the eda done, before going to a model to be trained 

# EDA
- The eda was broken down into numerical and categorical
- Numerical data was visualsied via kde plots and boxplots
- Categorical data was visalised via boxplots and value_counts()

# ML Model
- The dataset was pre processed via:
  - min max scaler for numerical data
  - ordinal and one hot encoding for categorical data

- The model of choice was gradient boosting classifier and catboosting classifier

# Results
- The metric used for this evaluation is accuracy
- Accuracy is used to detemrine how accurate the classification is based on:
  - number of correct predictions
  - total number of prediction to be made
 
- The ingested data into the preprocess and the model, gave rise to an accuracy of 88%
- Relative good for a baseline model without hyper parameter tuning

# Future Plans
- The model can be can be changed
- Doing hyper tuning of parameters
- Doing a more comprehensive preprocess flow
- Make it a full MLP model so it can be used by others
