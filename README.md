# Forecasting_Rainfall-Prediction

This is Binary classification problem, which also involves time forecating.

Task: To use the past 10 years of weather data to predict whether it will rain tommorow or not.

This Dataset is taken from kaggle.

# About the Dataset

Context
Predict next-day rain by training classification models on the target variable RainTomorrow.

Content
This dataset contains about 10 years of daily weather observations from many locations across Australia.

RainTomorrow is the target variable to predict. It means -- did it rain the next day, Yes or No? This column is Yes if the rain for that day was 1mm or more.

Source & Acknowledgements
Observations were drawn from numerous weather stations. The daily observations are available from http://www.bom.gov.au/climate/data.
An example of latest weather observations in Canberra: http://www.bom.gov.au/climate/dwo/IDCJDW2801.latest.shtml

Definitions adapted from http://www.bom.gov.au/climate/dwo/IDCJDW0000.shtml
Data source: http://www.bom.gov.au/climate/dwo/ and http://www.bom.gov.au/climate/data.

Copyright Commonwealth of Australia 2010, Bureau of Meteorology.


# Initial View On The Problem :
When I looked at the data I noticed there was a 'Date' column, this gave me an idea that this is a forecasting problem and I should divide the train/val/test
dataset based on timeline rather than random shuffle.

# Approach To The Problem :
- Divide the dataset into train/val/test datasets on the basis of the year of the data
- Perform **Exploratory Data Analysis** (Study relations between the features/columns)
- Study The Numerical/Categorical Columns separately
- **Imputing** and **Scaling** the Numerical columns
- **Encoding** the categorical columns
- Training The Models
- Study Model Accuracy and Other Metrics
- Tuning the Hyperparameters 
- Comparing the Model metrics
- Summarising/saving the Model

# Models :
1. LogisticRegression
2. Decision Tree
3. Random Foresst 
4. Gradient Boosting with XGBoost

# Libraries Used
- **sci-kit learn** library for all the ML tasks 
- matplotlib, seaborn , plotly.express for data analysis
- pandas and numpy for data handling and data cleaning

# Resources 
1. Jovian.ai course on machine learning 
2. https://www.kaggle.com/prashant111/extensive-analysis-eda-fe-modelling - notebook on kaggle


