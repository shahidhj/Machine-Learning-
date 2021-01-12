# Machine-Learning-
Implementation of different machine learning algorithms using python on tabular data

**Data**: The dataset was obtained from [kaggle](https://www.kaggle.com/ervikassingh/useraddclickdata?select=advertising.csv). The goal is a to model a classification algorithm to predict if a user would click on a given advertisement or not based on a set of features. 

**Implementation**: The intial approach to this problem involved Data analysis to understand the different features present in the data.Feature engineering was carried to identify the most imporatant features that would help the problem followed by carrying out data wrangling. The steps for data wrangling involved:
1. Identifying most important features.
2. Identifying number of missing values and dealing with them. (Appraoch used invloving replacing missing values with mean value for that column).
3. Identifying any outliers.
4. Determining the distribution of different classes(check to see if data is balanced/imbalanced).
5. Implementing different Machine learning algorithms, (Logistic Regression, Random Forest)

**Result**: Classification report was interpretted to see the performance of the model. Between the different algorithms used, followed by hyper tuning the model, the best model was found to be Random forest with 20 estimators.
