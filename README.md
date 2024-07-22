# Stock Price Prediction Project

This project is designed to analyze and predict the stock prices of Companies using various machine learning algorithms. The project includes data acquisition, visualization, preprocessing, model training, evaluation, and optimization.

## Project Structure

1. **Data Acquisition**

   The project starts by importing necessary libraries and acquiring stock data for Facebook from Yahoo Finance. It retrieves data for the last 300 days and saves it to a CSV file.

2. **Data Visualization**

   Candlestick charts are created to visualize the stock price movements with a 5-minute interval.

3. **Data Preprocessing**

   The data is split into training and testing sets, and standardization is applied.

4. **Model Training and Evaluation**

   Various regression models are trained and evaluated using the R² score.

5. **Model Optimization**

   Hyperparameter tuning is performed using GridSearchCV for the SVR model.

## Dependencies

Ensure you have the following libraries installed:

- `plotly`
- `pandas`
- `datetime`
- `yfinance`
- `seaborn`
- `scipy`
- `mplfinance`
- `matplotlib`
- `sklearn`
- `xgboost`

You can install these libraries using pip:

```bash
pip install plotly pandas yfinance seaborn scipy mplfinance matplotlib scikit-learn xgboost
```

## Running the Project
1. Ensure you have all dependencies installed.
2. Run the script in a Python environment.
3. Review the results printed in the console and the visualizations displayed.

## Conclusion

This project demonstrates how to use various machine learning models to predict stock prices. The results from the models are compared using the R² score, and the SVR model is further optimized using GridSearchCV to find the best hyperparameters.

Feel free to customize and extend this project for other stocks or additional features.

