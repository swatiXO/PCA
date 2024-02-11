# PCA
Download heart disease dataset heart.csv and do following, (credits of dataset:
https://www.kaggle.com/fedesoriano/heart-failure-prediction)

1. Load heart disease dataset in pandas dataframe
2. Remove outliers using Z score. Usual guideline is to remove anything that has Z score &gt; 3
formula or Z score &lt; -3
3. Convert text columns to numbers using label encoding and one hot encoding
4. Apply scaling
5. Build a classification model using various methods (SVM, logistic regression, random forest)
and check which model gives you the best accuracy
6. Now use PCA to reduce dimensions, retrain your model and see what impact it has on your
model in terms of accuracy. Keep in mind that many times doing PCA reduces the accuracy but
computation is much lighter and that&#39;s the trade off you need to consider while building models
in real life
