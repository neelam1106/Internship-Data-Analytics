# -PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

COMPANY NAME : CODTECH IT SOLTIONS PVT.LTD

NAME :  NEELAM SURESH GUPTA

INTERN ID: CITS0D780

DOMAIN : DATA ANALYTICS 

DURATION : 8 WEEKS

MENTOR : NEELA SANTOSH 

DESCRIPTION: This task is about predicting house prices using Linear Regression in Python. I began by loading a dataset from a CSV file using the pandas library.
The dataset contains details about houses, such as the number of bedrooms, bathrooms, living area size, lot size, number of floors, whether the house is on the waterfront, 
view rating, and condition. My target is to predict the price of the house.

First, I performed Exploratory Data Analysis (EDA) to understand the dataset. I looked at the first few rows to get an overview, checked summary statistics like average values
and ranges, and identified any missing values. I also created a correlation heatmap to see how each feature relates to others, especially the price. Next, I selected specific
columns as features (X) and used the house price as the target variable (y). I split the dataset into a training set (80%) and a testing set (20%) using 
train_test_split so I could train the model and then test it on unseen data.

I used Linear Regression from scikit-learn to train the model. Once the training was complete, I predicted prices for the test data. To check the model’s performance, 
I calculated the Mean Squared Error (MSE) and the R-squared (R²) score. MSE helped me see how far my predictions were from the actual values, while R² showed me how well 
the model explains the variation in prices
