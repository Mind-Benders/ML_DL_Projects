<div align = 'center'>
  <h1>Computer Price Prediction</h1>
</div>

### Problem Statement

Build the Regression model which predicts Price of the Computer accurately by using features Speed, HD, Ram, CD, Screen, Premium, ADS, Trend, Multi, etc.
- Categorical Features: Premium, ADS
- Numerical Features: Speed, HD, Ram, CD, Screen, Trend, Multi 

### Dataset

The dataset for this project is taken from the Kaggle. 
Here is the link for the dataset: https://www.kaggle.com/datasets/kingburrito666/basic-computer-data-set that was used.

### What Have I Done?

- Imported all the required libraries and dataset for this project.
- Visualized the patterns based on the features
- Encoded the categorical values to numerical values
- Splitted the Dataset into Training & Testing
- Scaled/Normalized the independent variables
- Built the Following Models and trained using training data:
  - Multiple Linear Regression model
  - Support Vector Regression model
  - Decision Tree Regression model
  - Random Forest Regression model
- Predicted the Price using testing data
- Checked the R2 score
- Checked the MSE

### Libraries Used:

- pandas
- plotly
- numpy
- sklearn

### Accuracies and Errors

Model 1: Multiple Linear Regression model
- R2 score: 0.7842770001633781
- MSE: 75557.18562442459

Model 2: Support Vector Regression model
- R2 score: 0.3750107154651787
- MSE: 218903.09063306998

Model 3: Decision Tree Regression model
- R2 score: 0.9094708364822558
- MSE: 31707.92552261217

Model 4: Random Forest Regression model
- R2 score: 0.9267796193988391
- MSE: 25645.507863152478

## Conclusion

By observing the above accuracies of the models, we can conclude that the Random Forest Regression model is highly accurate and better than the other models.

### Author

Code Contributed by: Ganesh Utla

Github: [ganesh-utla](https://github.com/ganesh-utla)
