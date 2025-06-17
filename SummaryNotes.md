This pages uses summary notes
feature = input
label = output 

### Evaluation Metrics
Regression Model 
Mean Absolute Error (MAE): Measures the average absolute difference between predicted and actual values. It is easy to interpret as it tells how much the model's predictions deviate on average from the true values.

Mean Squared Error (MSE): Calculates the average of the squared differences between predicted and actual values. It is useful for optimization because it is differentiable, but the squared units can be less interpretable.

Root Mean Squared Error (RMSE): The square root of MSE, which brings the error metric back to the same unit as the target variable, making it more intuitive for humans.

Mean Absolute Percentage Error (MAPE): Expresses the average error as a percentage, which can be more interpretable in some contexts.

R-squared (Coefficient of Determination): Indicates the proportion of variance in the dependent variable explained by the model. It is commonly used to assess goodness of fit.

Adjusted R-squared: Adjusts the R-squared value by penalizing the addition of unnecessary variables, helping to avoid overfitting
