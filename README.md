# Nba_Prediction
## Predicting NBA Basketball Game Outcomes

Predicting the results of NBA basketball games is important for both fans and team management staff. This study aims to predict NBA basketball game outcomes using a multivariate quadratic polynomial method and compare it with standard linear regression.

Two types of datasets, Dataset 18 and Dataset 22, were used to create prediction models. These models analyze how a team's total points are influenced by player scoring, successful 3-point shooting, successful free throws, and the last pass before scoring.

### Keywords
NBA matches, Machine Learning, Pearson Correlation, Evaluation Metrics, Multivariate Regression, Linear Regression.

## Multivariate Polynomial

Multivariate polynomial regression of degree 2 (Multivariate Quadratic Regression) can be represented as:

![Equation 1](https://github.com/boycakra/Nba_Prediction/assets/48791469/df325775-a8af-44d1-8e18-d1925a1bc903)

Where:
1. $\beta_0 +\beta_1 x_{i1}+\beta_2 x_{i2}$ is the linear parameter effect form.
2. $\beta_{11}x_{i1}^2+\beta_{22} x_{i2}^2$ is the quadratic parameter effect form.
3. $\beta_{12} x_{i1}x_{i2}+e_{i}$ is the cross product or interaction parameter effect form.

## Evaluation Model Using \( R^2 \)

\( R^2 \) is a measure that shows how well the model predicts existing data. The formula for \( R^2 \) is as follows:

![Equation 2](https://github.com/boycakra/Nba_Prediction/assets/48791469/06a442c4-c19b-44d5-8081-a1d32648c368)

Where:
1. \( y_i \) is the actual data.
2. \( \hat{y_i} \) is the prediction from the model.
3. \( \bar{y} \) is the average value of the actual data.
4. \( n \) is the number of data available.

## Evaluation Model Using Mean Absolute Error (MAE)

Mean Absolute Error (MAE) is an average error measure that measures how large the prediction error is made by the model. The mathematical formula for MAE can be written as:

![Equation 3](https://github.com/boycakra/Nba_Prediction/assets/48791469/13c79406-243e-400c-8691-1eb1aa1e47f7)

Where:
1. \( y_i \) is the actual data.
2. \( \hat{y_i} \) is the prediction from the model.
3. \( n \) is the number of data available.
4. \( |y_i - \hat{y_i}| \) is the absolute error between actual data and prediction.

## Hasil Evaluasi Models 
![Capture 3](https://github.com/boycakra/Nba_Prediction/assets/48791469/01edff6e-1ce3-4372-b0f9-1f8fa5440924)

# Kesimpulan

This study suggests the use of **Multivariate Quadratic** to predict NBA basketball game outcomes compared to linear regression. The results indicate that Model 6, using Dataset 22, achieves the highest accuracy. Model 6 predicts the total team points with an accuracy of 0.84278 for the 2021/2022 season and 0.65686 for October in the 2022/2023 season. The Multivariate Quadratic method outperforms linear regression for all models. Key influential features include player points, successful 3-pointers, successful free throws, and the last pass before scoring.

# Saran

For future research, it is recommended to predict team performance using data from 5 NBA basketball players in a single row, including opponent team performance. Data can be selected based on the most playing time in the game and sorted by position. Feature selection may also improve model performance, or other methods can be explored in this research.
