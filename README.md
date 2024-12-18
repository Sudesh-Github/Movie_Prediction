# Movie Audience Rating Prediction with Machine Learning

This project aims to predict audience ratings for movies using machine learning techniques. Below is an overview of the steps involved:

---

## 1. Data Acquisition and Preparation

**Dataset:**  
The project utilizes the `Rotten Tomatoes Movies3.xls` dataset (or a similar dataset containing movie information and audience ratings).

### Steps:
1. **Data Loading:**  
   We import libraries like `pandas` (`pd`) and read the data into a pandas DataFrame (`df`).

2. **Missing Value Handling:**
   Fill missing values for numerical columns with the mean and categorical columns with the mode.

3. **Feature Engineering:**
   Extract features like release_year and streamed_year from dates, encode categorical features, and log-transform numerical ones to reduce skewness.

## 2. Model Training and Evaluation

**Model:**
GradientBoostingRegressor is used to predict audience ratings.

### Steps:
1. **Data Splitting:**
    Split the dataset into training and testing sets.

2. **Model Training:**
    Train the Gradient Boosting Regressor on the training data.

3. **Model Evaluation:**
    Evaluate the model using R-squared and Mean Squared Error (MSE).


## 3. Prediction

Predict a New Sample:
Use the trained model to predict audience ratings for a new sample.

## 4. Running the Script
Save the script as movie_rating_prediction.py and run it from the command line:

```base
   python movie_rating.py
