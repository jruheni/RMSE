# Linear Regression with Different Tet-Train Splits & RMSE Analysis
## Description

The objective of this assignment is to evaluate the performance of a linear regression model on a historical temperature dataset of New York City using different train-test split ratios. By experimenting with various split ratios, we aim to understand the impact of training data size on the model’s prediction accuracy.

The dataset used is "ave_hi_nyc_jan_1895-2018.xls," which contains the average high temperatures in New York City for the month of January from 1895 to 2018. This data is suitable for time-series analysis and helps in assessing the model's ability to predict temperature trends over time.

By performing train-test splits with different ratios, we can observe how the model's performance varies with the amount of training data. This helps in identifying an optimal split that provides a balance between training accuracy and generalization to unseen data.

## Results
By observing the RMSE values for each train-test split ratio, we can evaluate the model's performance under different conditions:

| Size    | RMSE               |
|---------|--------------------|
| Default | 4.160742885627115  |
| 50:50   | 4.3948122242876    |
| 80:20   | 4.012353566125973  |
| 75:25   | 4.160742885627115  |
| 90:10   | 3.6657752651313316 |

The results indicate that the RMSE varies slightly across different train-test splits. The lowest RMSE of 3.6658 is achieved with a 90:10 split, suggesting that using more training data improves the model's prediction accuracy. Conversely, the highest RMSE of 4.3948 occurs with a 50:50 split, indicating that the model performs less accurately when less data is available for training.

These findings highlight the importance of selecting an appropriate train-test split ratio to achieve a balance between training and testing data, thereby optimizing the model's performance and generalizability.
