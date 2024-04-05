# SPY Prediction using LSTM Neural Network

Helped my friend's research at New York University to gather 3 years worth of minute-by-minute data on the SPDR S&P 500 ETF Trust, code has many manual calls due to API limits

Data starts on March 22, 2023 and ends on Feburary 29, 2024

Link to csv file: https://drive.google.com/file/d/1DE0GOk1oDgjyS-VnlnS7PRX4zwW0UDFW/view?usp=sharing

- Resampled and scaled data with Scikit-Learn, prepared data for training with numpy and deque
- With TensorFlow of multiple layers, we used the LSTM Neural Network and sequential model to output 3 days of predicted price.

Resources used:
- Alpha Vantage API
- Pandas
- MatPlotLib
- TensorFlow
- Scikit-Learn
- Numpy

Our predicted prices for the next 3 days are 508.36, 507.33, 508.01, as we can see, its relatively close to the actual price.
![image](https://github.com/ExtraMediumDev/SPY-Prediction-using-LSTM-Neural-Network/assets/69373081/16e99daa-c74e-49cf-a338-d56a9f3d5fa6)
