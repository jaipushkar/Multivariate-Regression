# Multivariate-Regression

**Home Prices Prediction using Multivariate Linear Regression**
This project demonstrates the use of multivariate linear regression to predict home prices based on multiple features: area, number of bedrooms, and age of the house.

**Dataset**
The dataset homeprices.csv contains the following columns:
**area:** The area of the house in square feet.
**bedrooms:** The number of bedrooms in the house.
**age:** The age of the house in years.
**price:** The price of the house in US dollars.

**Steps**
**Data Loading and Preparation:**
Loaded the dataset into a DataFrame.
Filled missing values in the bedrooms column with the median number of bedrooms.

**Model Training:**
Trained a linear regression model using the features (area, bedrooms, age) to predict the target (price).
Extracted the model coefficients and intercept to understand the relationship between features and the target.

**Prediction:**
Predicted the price of houses given their features using the trained model.
Calculated the predicted prices manually using the linear regression equation to verify the model's predictions.

**Exercise: Salary Prediction using Multivariate Linear Regression**
This exercise involves predicting salaries based on experience, test scores, and interview scores.

**Dataset**
The dataset hiring.csv contains the following columns:
**experience:** The years of experience of the candidate.
**test_score(out of 10):** The test score of the candidate out of 10.
**interview_score(out of 10):** The interview score of the candidate out of 10.
**salary($):** The salary of the candidate in US dollars.

**Steps**
**Data Loading and Preparation:**
Loaded the dataset into a DataFrame.
Filled missing values in the experience column with 'zero' and converted the text to numerical values.
Filled missing values in the test_score(out of 10) column with the median test score.

**Model Training:**
Trained a linear regression model using the features (experience, test_score(out of 10), interview_score(out of 10)) to predict the target (salary($)).

**Prediction:**
Predicted the salary of candidates given their features using the trained model.

**Dependencies**
pandas
numpy
scikit-learn
word2number
