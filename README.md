# House_Price_Prediction

Problem:
A linear regression problem, building a model which can predict price of a house.

This was my semester project. But now I am improving it.

- Trying to identify outliers.
  By identifying outliers the accuracy (R^2) jumped to 0.9078 from 0.8425
- Trying out different regession models.
  So far I could not decide which model should I use, Tried 16 models but most of them are almost same in scores.
- Tried taking log of target (SalePrice) Column
  Taking log of the target column resulted in improved R^2 score of 0.9232
- Hyperparameter tuning.
  Tried hyperparameter of `RandomForestRegressor` but no improvement in score.
