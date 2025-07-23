<h1>Power Consumption Prediction</h1>

### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Predicting power consumption accurately helps utilities and consumers optimize energy usage, reduce costs, and support sustainable energy management.

This project demonstrates:

- Loading and preprocessing real-world power consumption data
- Feature engineering from datetime values
- Training a Linear Regression model for next-day consumption forecasting
- Model evaluation with RMSE and R² metrics
- Visualization of actual vs predicted power consumption
- Predicting future power usage based on latest data

<br />

This repository contains a simple yet effective machine learning project to predict **next-day power consumption** based on historical power usage data. The project uses a Linear Regression model trained on time-series features extracted from daily power consumption data.

---
<h2> 📊 Code Summary</h2>

-Load CSV and convert datetime column to datetime type

-Create features like year, month, day, day of week

-Shift power consumption column to create the target for the next day

-Split data into training and testing sets

-Train Linear Regression model on the features

-Evaluate the model performance with RMSE and R² score

-Plot actual vs predicted power consumption for test data

-Predict power consumption for the day after the latest date in dataset

<h2>📈 Model Performance Metrics</h2>

-RMSE (Root Mean Squared Error): Measures average prediction error magnitude

-R² Score (Coefficient of Determination): Indicates how well the model explains variance in data (closer to 1 is better)


<h2>📈 🔮 Predicting Future Consumption</h2>

The model uses the most recent power consumption and date features to predict power consumption for the next day, supporting simple forward-looking energy management.

<h2> 🧰 Dependencies</h2>

-Python 3.x

-pandas

-numpy

-scikit-learn

-matplotlib

-seaborn

<br /><br />

Sending Commands from Mobile App: <br/>
<img src="https://i.imgur.com/YourMobileAppImageHere.png" height="80%" width="80%" alt="Bluetooth App"/>
<br /><br />

Receiving and Executing Serial Data: <br/>
<img src="https://i.imgur.com/YourArduinoRunImageHere.png" height="80%" width="80%" alt="Arduino Execution"/>
</p>
