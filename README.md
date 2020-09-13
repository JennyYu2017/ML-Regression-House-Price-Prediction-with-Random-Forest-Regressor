# Machine-Learning---House Price Prediction with Random Forest Regressor 

In this project, I use the Random forest algorithm to build the house price prediction model on a dataset with 16 features and 4600 samples from Kaggle(https://www.kaggle.com/shree1992/housedata). 

Random Forest Regressor will be an optimal algorithm in this problem because it works well on both categorical and numerical features. Moreover, it is robust to missing values, new entries, and outliers and will save us the effort to normalize the data considering each feature’s scale varies a lot.  

The experiment shows that feature engineering using Recursive Feature Elimination does help improve model performance. Comparing the model trained on all features, the model trained on the 7 optimal features improves the R2 score from 0.4904 to 0.5435 while reducing the Mean absolute error from 134490.3 to 131453.1. 

![](/plots/Feature%20Ranking.png)


