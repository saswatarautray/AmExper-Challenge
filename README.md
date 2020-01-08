# Repository for AmExpert Challenge organized by AnalyticsVidhya and American Express
The objective was to predict the probability of a click on an ad for a specific web session belonging to a specific user using his characteristics and parameters which categorizes the product displayed.
1) Firstly, I performed data analysis to identify overlap of users and product types, between train, test and history data.
2) I applied the cross-validation strategy, as nearly 60% of the train set were also available in the test data. Then I performed feature engineering.
3) I obtained the final probability by taking the mean of probabilities predicted using gradient boosting machines techniques namely 5-
fold CV in lightGBM and XGBoost.
