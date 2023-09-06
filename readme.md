# DPrice

A data analysis project on diamond prices with linear regression using R. The MSE (mean squared error) value is reduced to 487594.9, compared to the performance of the dummy model 1227713. Compared to the random forest model, the error of the linear regression model is only increased by 20%, while the model keeps the interpretability and shows some physical meaning.

This project aims to build accurate predictive models for diamond prices using regression models.
It is crucial for diamond sellers and buyers to determine competitive prices and make informed
decisions, respectively. Factors such as carat weight, cut quality, color grade, clarity, and physical
dimensions impact a diamond's price. The project uses a dataset from Kaggle, with data on these
characteristics for 53,909 diamonds.
The analysis encompasses three regression models and handles multi-collinearity among predictors
and prevents model overfitting. A range of techniques like visualization, exploratory data analysis,
model diagnostics, and train-test split are used to ensure the models' reliability. The selected model
achieves 0.9848 in $R^2$ and 449681.2 in MSE.,
The results demonstrate high accuracy in predicting diamond prices based on these properties.
However, there's an acknowledgment that the models might not account for all potential factors, like
market demand or economic conditions. Future work could explore additional variables, advanced
regression techniques like Lasso or Elastic Net regression, broader datasets, or sentiment analysis of
customer reviews to further improve the model.
