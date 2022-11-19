# Used Car Price Prediction

This project was a requirement for one of my classes during my Master's Data Science program at Bellevue Univeristy.

#### -- Project Status: `In-Progress`

## Project Intro/Objective
The primary purpose of this project is to train a predictive analytics model utlizing a used car dataset. The trained model would be provided to prospective car buying customers so that they would have a better understanding of the prices they should be paying based on the desired characteristics of the vehicle they want.

### Methods Used
* Machine Learning (Sci-kit Learn: Linear Regression, Decision Tree, Random Forest)
* Data Visualizaiton (Matplotlib, Seaborn)
* Summary Statistics

### Technologies Used
* Python (Pandas, NumPy)
* DataSpell (Data Science IDE)

## Project Description
The data for this project was collected from University of California-Irvine's Machine Learning Repository [Automobile Data Set](https://archive.ics.uci.edu/ml/datasets/automobile). The data contained just over 200 observations and 25 features and one target variable, `price`. The primary programming language used in this project is Python which provides access to a plethora of machine learning tools. There were some minor data cleansing and pre-processing steps required before the data was in a format fit to model training. The models that were chosen to be trained included a simple linear regression model, a decision tree regressor, a k-neighbors regressor, as well as a random forest regressor. Once the models had been fitted to the training data, they were validated using a holdout validation set of data. Then, using the mean-squared-error and coefficient of determination (r2) performance metrics, the predictive power of the models were assessed. Within the repo are detailed write-ups and a presentation that summarizes my findings and project methodology.
