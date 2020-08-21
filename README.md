# Movie_Revenue_Prediction
Prediction of movie revenues using boosting algorithms.
# Dataset
 The dataset has been taken from the kaggle competition by TMDB for movie revenue prediction. It contains data for around 7000 movies. The atrributes of the dataset are as follow:
* id
* belongs_to_collection
* budget
* genres
* homepage
* imdb_id
* original_language
* original_title
* overview
* popularity
* poster_path
* production_companies
* production_countries
* release_date
* runtime
* spoken_languages
* status
* tagline
* title
* Keywords
* cast
* crew
* revenue

# Data Cleaning
 After data cleaning and feature engineering, the number of columns were extended upto 149. Note that not all of these columns were neccesary for model fitting

# Exploratory Data Analysis
 Relationship among different attributes and target attribute were shown in the for of graphs using matplotlib and seaborn.

# Model Fitting
Following algorithms have been used for making predictions
* Gradient Boosting with scikit-learn
* XGBoost
* LGBM
* Catboost
Methods such as gridsearch cv were applied for tuning and for finding the best model possible.
