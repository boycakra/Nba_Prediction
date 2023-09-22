# Nba_Prediction
# Predicting NBA Basketball Game Outcomes

Predicting the results of NBA basketball games is important for both fans and team management staff. The purpose of this study is to predict the outcomes of NBA basketball games using a multivariate quadratic polynomial method and compare it with standard linear regression. 

Two types of datasets were used in creating this prediction model to analyze how a team's total points are influenced by player scoring, successful 3-point shooting by players, successful free throws by players, and the last pass by a player before scoring. These datasets are named Dataset 18 and Dataset 22. Dataset 18 was used to build the first model, called Model 18, and Dataset 22 was used to build the second model, called Model 22. 

The results of the study indicate that the multivariate quadratic polynomial method used in Model 22 provided more accurate predictions, with an accuracy of 0.84278. These findings can be used as a tool for fans and team management staff to predict the outcomes of NBA basketball games.

## Keywords
NBA matches, Machine Learning, Pearson Correlation, Evaluation Metrics, Multivariate Regression, Linear Regression.

### Multivariate Polynomial

Regresi Polinomial can be applied to a single predictor variable regression called Simple Polynomial Regression or can also be calculated on multiple variable predictor regression as Multivariate Polynomial Regression (Multivariate Polynomial Regression).

Multivariate polynomial regression of degree 2 (Multivariate Quadratic Regression) can be represented as:

![Equation 1](![Capture 4](https://github.com/boycakra/Nba_Prediction/assets/48791469/df325775-a8af-44d1-8e18-d1925a1bc903))

Where:
1. $\beta_0 +\beta_1 x_{i1}+\beta_2 x_{i2}$ is the linear parameter effect form.
2. $\beta_{11}x_{i1}^2+\beta_{22} x_{i2}^2$ is the quadratic parameter effect form.
3. $\beta_{12} x_{i1}x_{i2}+e_{i}$ is the cross product or interaction parameter effect form.

### Evaluation Model Using \( R^2 \)

\( R^2 \) is a measure that shows how well the model predicts existing data. \( R^2 \) values range between 0 and 1, with higher values indicating that the model predicts the data better.

The formula for \( R^2 \) is as follows:

![Equation 2](![Capture 5](https://github.com/boycakra/Nba_Prediction/assets/48791469/06a442c4-c19b-44d5-8081-a1d32648c368))

Where:
1. \( y_i \) is the actual data.
2. \( \hat{y_i} \) is the prediction from the model.
3. \( \bar{y} \) is the average value of the actual data.
4. \( n \) is the number of data available.

### Evaluation Model Using Mean Absolute Error (MAE)

Mean Absolute Error (MAE) is an average error measure that measures how large the prediction error is made by the model. The mathematical formula for MAE can be written as:

![Equation 3](![Capture 6](https://github.com/boycakra/Nba_Prediction/assets/48791469/13c79406-243e-400c-8691-1eb1aa1e47f7))

Where:
1. \( y_i \) is the actual data.
2. \( \hat{y_i} \) is the prediction from the model.
3. \( n \) is the number of data available.
4. \( |y_i - \hat{y_i}| \) is the absolute error between actual data and prediction.


## Hasil Evaluasi Models 
![Capture 3](https://github.com/boycakra/Nba_Prediction/assets/48791469/01edff6e-1ce3-4372-b0f9-1f8fa5440924)

# Kesimpulan

Penelitian ini mengusulkan penggunaan **Multivariate Quadratic** untuk memprediksi hasil pertandingan bola basket di liga NBA, dibandingkan dengan regresi linier. Hasil pengujian menunjukkan bahwa Model 6 dengan menggunakan Dataset 22 memiliki tingkat keakuratan terbaik. Model ini hanya memprediksi total poin tim dengan tingkat keakuratan sebesar 0.84278 pada musim 2021/2022 dan 0.65686 pada bulan Oktober untuk musim 2022/2023. Metode Multivariate Quadratic juga lebih baik daripada regresi linier untuk semua model. Fitur-fitur yang berpengaruh besar terhadap performa termasuk poin pemain, tembakan 3 poin yang berhasil, tembakan bebas yang berhasil, dan umpan terakhir sebelum mencetak poin.

# Saran

Untuk penelitian mendatang, disarankan untuk memprediksi performa tim dengan menggunakan data 5 pemain pada tim bola basket NBA dalam satu baris, termasuk performa tim lawan. Data dapat diambil dari waktu bermain paling banyak dalam pertandingan dan diurutkan berdasarkan posisi. Penggunaan fitur selection juga dapat meningkatkan performa model, atau dapat digunakan metode lain dalam penelitian ini.


