# Sales Forecasting Using Holt-Winters Method

Replication code for the document “`WOUF: Supply Chain Optimization`”, part of the Final Thesis Project for the Master’s in Operations Management and SCM in EADA Business School.

+ Authors: Boronat, M, Dulanto, H. M., Gálvez, M. A., Ramirez, C. C., and Riaño, A.
+ Code: [Renato Vassallo](https://www.linkedin.com/in/renatovassallo/).

This version: July 2024.

In this project, we use time series techniques to model and forecast the demand for various products of a fashion industry company. The `Holt-Winters Method` is particularly useful for capturing seasonality and trends in sales data, providing accurate predictions that can inform inventory and marketing strategies.

### Pseudo out-of-sample forecasting

To evaluate the predictive accuracy of the model, we use a pseudo out-of-sample forecast strategy. We have weekly sales data from 2018 to 2024. We follow these steps:

1.	Use data from 2018 to 2021 to train the model.
2.	Make forecasts for 2022.
3.	Compare the forecasts for 2022 with the actual sales data from 2022 to evaluate the model.
4.	Then, use data up to 2022 to make forecasts for 2023 and continue the evaluation process.
