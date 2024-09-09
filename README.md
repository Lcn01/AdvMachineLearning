# AdvMachineLearning
This is my code notebook and bank churn CSV file for my Advanced Machine Learning course from UT Austin's Postgraduate Certification in AI/ML: Business Applications. In this project, I built a classification model for a bank using ensemble methods that would enable the bank to accurately predict credit card user churn.

The data was loaded into Python, where extensive exploratory data analysis was performed (using visualization modules from Seaborn), any missing values were imputed, and the data split into train, validation, and test sets. After that, I proceeded to build the machine learning model using ensemble methods, using recall as the metric to optimize, as it is most important to the bank to identify any customers who are at risk of attrition.

In my model, I utilized bagging, random forest, gradient boosting, adaboost, decision tree, and XGBoost. All models were tested using the base data, then retested again with both undersampled and oversampled data. After compiling recall scores for all models and data, I chose the three models with the highest recall score on their validation data and began hyperparameter tuning on each one.

Once each model was tuned appropriately, they were all tested once more and the final model was chosen (which turned out to be XGBoost with undersampled data). Upon running the test data set on the final model, the final recall score was .994, and business insights and conclusions were given based on the exploratory data analysis, model feature importances, and results.
