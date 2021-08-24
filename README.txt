Wine Quality Analysis and Prediction

Project- Applying Regression algorithm on a wine data set to predict the quality of the wine as per test reports 
Tools-Excel, Jupyter notebook, Pandas, Matplotlib, Seaborn, Scikit learn, PandasProfiling

Approach
•	Load the dataset in pandas in notebook
•	Gain insights of the data (size, unique values etc.)
•	Checked for null values and fill them if any
•	Get quick in depth insights using pandas profiling and get correlations 
•	Plotted graphs for better understanding
•	Done some basic feature engineering (changed data type)
•	Checked for outliers using IQR OR PERCENTILE method and treated them with suitable measures 
•	Using train test split Randomly splitting the data and keeping some test data aside for model to be later tested on 
•	Plotted Feature importance graph for final selection and details of important features
•	Testing all algorithms like (ridge, linear, logistic, decision tree ,Random Forest) for regression and calculated their score and errors(MAE,RMSE,MSE) and selected the best performing algorithm
•	Saved the model using pickle for further use 


Conclusion
Model is successfully ready. Consisting RANDOM FOREST REGRESSOR which proved to be the best in error metrics with score of 0.93
MAE: 0.4171135453088578
MSE: 0.320584555178264
RMSE: 0.5662018678689289

*(decision Tree Regressor Shown to be overfitted)



