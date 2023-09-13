# Retail-Sales-Prediction-

![640px-Rossmann_Logo svg](https://user-images.githubusercontent.com/104754645/174442537-0a299233-58b6-4ebf-9208-a62f5a7d82c5.png)
# 📖PROBLEM STATEMENT
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied. My work includes various plots and graphs , visualizations , feature engineering , ensemble techniques , different ML algorithms with their respective parameter tuning , analysis and trends . Predictions are of 6 weeks of daily sales for 1,115 stores located across Germany.
# 📖ALGORITHMS USED:
### I. Linear Regression
### II. Linear Regression With Regularization
### III. Decision Tree
### IV. Ensemble Of Random forest.


# 📖Solution Strategy
My strategy to solve this challenge was:

Step 01: Data Description: Use statistics metrics to identify data distributions.

Step 02: Feature Engineering: Derive new attributes based on the original variables to better describe the phenomenon that will be modeled.

Step 03: Exploratory Data Analysis: Explore the data to find insights and better understand the impact of variables on model learning.

Step 04: Feature Selection: Selection of the most significant attributes for training the model.

Step 05: Machine Learning Modelling: Machine Learning model training.

Step 06: Hyperparameter Fine Tunning: hoose the best values for each of the parameters of the model selected from the previous step.

Step 07: Convert Model Performance to Business Values: Convert the performance of the Machine Learning model into a business result.

Step 08: Deploy Modelo to Production: Publish the model in a cloud environment so that other people or services can use the results to improve the business decision.
# 📖CONCLUSION
We originally performed EDA on each feature of our datset over the course of our investigation. Sales, our dependent variable, was first analyzed and converted. Next, we examined categorical variables and eliminated those that were dominated by a single class. We also examined numerical variables and used the corr() Function to determine their correlation, distribution, and relationship to the dependent variable. Finally, for multicollinearity, we used the VIF Function that we had developed. Additionally, we hot encoded the categorical variables and deleted several numerical characteristics with a large percentage of 0 values.

* As my observation Sales are highest during three month of the year i.e.,July, November and December and least sales are during the month of May.
* Sales increases year by year because of stores gives discount on productst.
* When School is closes Some stores sales droping but B type of store no effect on sales when school open or close.
* Mostly Sales of B type of Assortment (Extra things).
* Sales are maximum during the Public Holidays, where are during the religious occassions, like Easter or Christmas, the sales are lower , most of sales of B type assortment of all Holiday.
* As my ovservation the highest sales belonged to the store type A due to the high number of type a stores in our dataset. Store type a and c had a similar kind of sales and customer share.
* We can observe that most of the stores remain closed during State holidays. But it is interesting to note that the number of stores opened during School Holidays were more than that were opened during State Holidays.
* The R Squared score of all Liner Regression Algorithm with or without Regularization are quit good which is 0.82.
* the R Squared score of the Decision Tree Regressor model we got 0.95 on test set which is also good.
* The Random Forest regressor model perform very well amoung the others.
* The Gradient Boosting Regressor model perform well and give 0.82 R Squared on test set . After Applying GridSearchCV which is a optimal algorithm search tool improve our R Squared score from 0.94 to 0.96 which almost nearly the random forest regression model.
* There is no such over fitting seen.
* We can say that random forest regressor model is our optimal model and can be deploy.
# 📋 Execution Instruction
The given IPython Notebook can be either downloaded to be run on your local Jupyter Notebook or can be directly run on Google Colab.

# 📜 Credits
 Abhishek Rathore| Data Scientist | Machine Learning Engineer | Data Science enthusiast

Special thanks to AlmaBetter

Contact me for Data Science Project Collaborations



