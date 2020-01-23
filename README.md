# predict_future_sales
Notebook for competition https://www.kaggle.com/c/competitive-data-science-predict-future-sales

There are 3 notebooks attached in this work. 
First notebook does EDA and Feature generation and prepare the training data and save it to disk.

# EDA+Train Data Preparation: 
In this exploratory data analysis has been done and if there are patterns are explained. After that featue engineering is done and training data is prepared
# Simple XGBOOST: 
This is 2nd notebook and not part of this notebook. This reads the data prepared in 1st notebook and train xgboost regression learner and serialize the model and saves the test data. Finally it generate submit.csv file. 
[This step requires to train the model, so if you want to save the time run 3rd notebook]
# Simple Submission: 
This is most simple and fastest result reproducible notebook. Just use the learnt model and run through test data as provided with submission and generate the csv file for submission.
##### REQUIRED LIBRARIES
pickle

joblib

matplotlib

seaborn

pandas

numpy

xgboost

sklearn

statsmodels

itertools

tqdm

************
******************
