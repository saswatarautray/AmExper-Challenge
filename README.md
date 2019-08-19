# Repository for the AmExpert Challenge by AnalyticsVidhya and American Express
Predict the probability of a click on an ad for a specific web session belonging to specific user with his characteristics
and parameters categorizing the product displayed.
1) Performed data analysis to identify overlap of users, products types, between train, test and history data.
2) Applied cross validation strategy, as nearly 60% from train set were also available in the test, followed by feature engineering.
3) Obtained final probability by taking mean of probabilities predicted using gradient boosting machines techniques such as 5-
fold CV in lightGBM and XGBoost.
