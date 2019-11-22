# House_Price_Prediction
# Dataset used : Kaggle.com   lINK : https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data
Problem Statement : 
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

Goal : House Price Prediction using Machine Learning 
Prediction Technique : Regression
Problem Statement :
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

steps Followed : 
1. Understand the data.
2. Data Cleaning and Feature Selection (Using Co-relation Matrix / IV score . Here i have used Co-relation Matrix.)
3. Data Exporation and Transformation
  i)Data Identification - Identify data types and category of these variables.
  ii)Missing value Treatment - (Statistical Methods - Continuous Variables -(mean, median), Categorical Variables- (Mode) ) , Delete missing value rows (If required - but loss of data is also possible)
  iii) Outlier Treatment - Find outlier using Box- Plot Technique or Scatter plot, Handel using Binning method/ Statistical technique.
  iv) Variable Transformation - (Its a process to make data meaningful - Feature Engineering)
4. Visualize the data and find the dependency of the variable.
5. Data is ready then apply the Prediction Model (Regression Model- Random Forest, XG Boost)
6. Accuracy : check it by MSE (Mean Square Error) MSRE(Mean Square Root Error)

