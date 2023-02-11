# Bike-Sharing-Demand-Prediction
**Project Summary -**

1. Rental bikes is a multi-billion dollar industry,whose popularity is increasing among masses for short distance travelling within cities.To keep up with the demand,it is important to predict the demand for rented bikes per hourly basis to increase the customer satisfaction by reducing the waiting time thus giving an edge over other competitors.
2. In this project we have built various regression models to predict the demand for rented bikes.Models used are Linear regression with lasso and ridge regularization,Decision tree,Random forest,Gradient Boosting and XG Boosting.Based on the R2 score,we have found Gradient Boosting model the most accurate model.Gradient Boosting seems to have generalised well on the given data.

**Problem Statement**

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The main aim of the project is to make prediction of rented bikes required at each hour for the stable supply of rental bikes.

**Conclusion**

Linear Regreesion with Lasso and Ridge regularization
1. Linear Regression gave underfitted model as the feature relation with the target variable was non-linear one.
2. Also the lasso and ridge were not helpfull as the model did not overfitted it underfitted due to non-linear relationship.

Decision Tree
1. Decision Tree gave good increase in R2 score as compared to linear regression.
2. Train R2=0.847 and Test R2=0.812 were obtained.

Random Forest
1. Gave little gain as compared to decision tree.
2. Train R2=0.856 and Test R2=0.831 were obtained.

Gradient Boosting and XGB Boosting
1. Both boosting techniques gave very good R2 score,better than any of the model.
2. The reason for choosing Gradient Boosting over XGB Boosting is because very small difference between (train R2=0.948 and test R2=0.897) for Gradient Boosting as compared to XGB Boosting which is (train R2=0.992 and test R2=0.899)
3. Even though XGB and Gradient Boosting performed equally due to relatively large difference between Train and Test error XGB was not not selected.
4. Gradient Boosting seems to have generalized well on the given data.
