# House-price-prediction
- We have a dataset of houses in the shrubs of *Boston, Massachusetts*.
- My goal was to create a model which will predict the price for any house.

## Dataset Information
| Column  | Description                                                           |
|---------|-----------------------------------------------------------------------|
| CRIM    | per capita crime rate by town                                         |
| ZN      | proportion of residential land zoned for lots over 25,000 sq. ft.     |
| INDUS   | proportion of non-retail business acres per town                      |
| CHAS    | Charles River dummy variable (= 1 if tract bounds river; 0 otherwise) |
| NOX     | nitric oxides concentration (parts per 10 million)                    |
| RM      | average number of rooms per dwelling                                  |
| AGE     | proportion of owner-occupied units built prior to 1940                |
| DIS     | weighted distances to five Boston employment centres                  |
| RAD     | index of accessibility to radial highways                             |
| TAX     | full-value property-tax rate per $10,000                              |
| PTRATIO | pupil-teacher ratio by town                                           |
| B       | 1600 (Bk - 0.63)*2 where Bk is the proportion of blacks by town       |
| LSTAT   | % lower status of the population                                      |
| MEDV    | Median value of owner-occupied homes in $1000's                       |

## Performance Measure
Since this is a regression problem, I chose *root mean squared error (RMSE)* as the way to evaluate the model.

## Project Structure
- **Data Exploration:** Exploratory Data Analysis (EDA) was conducted to gain insights into the dataset.
- **Data Visualisation:** Histograms were created to visualize the relationships between different attributes.
- **Data Cleaning:** Removed the null and duplicate values.
- **Model Building:** Regression (Linear) and tree-based machine learning model (Decision Tree, Random forest) were trained and evaluated for prediction.
- **Model Testing:** Results of the models were tested using the performance measure.
- **Model Deployment:** The model was saved and deployed using the *joblib* library.

## Result
Using the Random Forest model, I was successfully able to predict the prices of houses with an RMSE of 2.88.
