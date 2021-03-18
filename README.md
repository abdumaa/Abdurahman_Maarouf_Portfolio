# [Project 1: Customer Churn Classification](https://github.com/abdumaa/Customer-churn-Classification)
* Kaggle-Dataset containing 3333 customers who either left (churn = 1) or stayed (churn = 0) in the company
* Dataset also included 10 features of the customers including contract details and consumer-behavior
* Exploratory Data Analysis of Dataset
* Main insight: Customers with high monthly charge and low data usage cancelled their service
* Build Machine-Learning-Models (such as Random Forest, XG-Boost) for the classification of customers in the two groups
* The classes were imbalanced so I tried Upsampling and Downsampling; Upsampling yielded the better results
* **Accuracy on Test-Data:** XG-Boost (Accuracy: 95,2 %, AUROC: 91,7 %), Random Forest (Accuracy: 91,1 %, AUROC: 93,4 %)
  
    
![](/scatterplot.png){:height="100%" width="100%"}



# [Project 2: Appartment Rent Predicition](https://github.com/abdumaa/Pred-Challange)
* Project of my University Subject "Machine Learning"
* Dataset contains 39240 different appartments in Germany with 13 variables
* Goal: Build prediction model for rent prices minimizing RMSE on unseen data
* Exploratory Data Analysis of Dataset
* Feature Engineering (splitting) of Postcode Variable: First two digits represent region, last three are the area in that region
* Build Machine-Learning-Models (such as Ridge, Lasso Regression and XG-Boost) to create a prediction model
* Used RandomizedSearchCV and GridSearchCV to find best parameters of Models
* **Accuracy on Test-Data:** XG-Boost (RMSE: 114,82)


![](/feature_importance.png){:height="100%" width="100%"}
  
    
   
# [Project 3: NBA Salary Prediction](https://github.com/abdumaa/NBA-Salary-Prediction)
* Crawled data from [Basketball Reference](https://www.basketball-reference.com)
* Data: Salary Details for NBA Players of the season 19/20, Multiple NBA Player Stats per game of the seasons 18/19 and 17/18
* Cleaned the data and prepared it for the analysis
* Exploratory Data Analysis of Dataset with only 431 Players
* Main Insight: Strong positive linear correlation between Salary and Points, Turnover and Assists per game 
* Build Machine-Learning-Models (such as Ridge, Lasso Regression and XG-Boost) to create a prediction model
  
  
![](/heatmap.png){:height="100%" width="100%"}
  
  
  
## There is more to come soon so stay tuned!

