# Life-Expectancy-Predictor-for-a-Region
The Machine Learning model uses XGBoost regression algorithm to predict the life expectancy of a definite region. 21 features were used in the dataset. 70% of the dataset was used to train the model and 30% to test the model for its performance. The model has an R2 score of 0.96(approx.), which indicates it works just fine<br> 
Feature Engineering was performed to hot encode the developing/developed status of a region. The metrics like Mean Absolute Error, Root Mean Squared Error(RMSE) , R2 score and adjusted R2 score were evaluated.<br>
The R2 score as mentioned above is really close to 1 and the adjusted R2 score was almost the same as R2 indicating all the features used were necessary and no unnecessary features were used avoiding overfitting.<br>
The average relative error was only 1.97%, indicating the high accuracy of the model.<br>
The MAE is 1.304 and RMSE is 1.304, RMSE being slightly higher indicates the model might predict with slightly higher error for some cases. But the Actual and Predicted values follow a reasonably Linear relationship. So the model performs overall very good
<img width="699" height="466" alt="image" src="https://github.com/user-attachments/assets/322244e9-0520-41ae-b74f-9eedc9622b42" />
