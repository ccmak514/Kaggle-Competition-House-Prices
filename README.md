## House Prices - Advanced Regression Techniques (Kaggle Project)
This is a Kaggle project: House Prices - Advanced Regression Techniques <br>
In this project, I achieved score: 0.12149 <br>
<img width="966" alt="Score" src="https://user-images.githubusercontent.com/101066418/157860486-6666a72d-c4ff-431d-8dea-9857281d7e90.png"><br>
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. Here is the outline of my notebook:<br>
#### 1. Checking Data 
#### 2. Cleaning Data
#### 3. Combine Train and Test
#### 4. Features and Target Transformation
#### 5. Encoding and Standardization
#### 6. Split the Combine Set
#### 7. Hyperparameter Tuning
#### 8. Modeling and Prediction
=======================================================================
## 1. Checking Data
- Checking data type
- Checking missing values in train and test sets
## 2. Cleaning Data
- Adjust the data type of 'MSSubClass'
- Fill categorical values
- Fill numerical values 
## 3. Combine Train and Test
- Combine two sets
## 4. Features and Target Transformation
- Checking the skewness of features and target
- Apply logarithmic transformation
## 5. Encoding and Standardization
- Categorical data encoding
- Numerical data standardization
## 6. Split the Combine Set
- Split the combine set after section 4 and 5
## 7. Hyperparameter Tuning
- XGBRegressor 
- Optuna (hyperparameter tuning)
## 8. Modeling and Prediction
- Build the model based on the parameters found in Section 7
- Apply exponential function to prediction as the final prediction for submission
