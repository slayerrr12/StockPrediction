# Stock Price Prediction using LSTM and Linear Regression

## Overview
This repository contains Python code for predicting stock prices using Long Short-Term Memory (LSTM) and Linear Regression models. The data is fetched from Yahoo Finance using the `pandas-datareader` library.

## Getting Started
1. Install the required dependencies:
pip install --upgrade pandas-datareader numpy pandas matplotlib tensorflow yfinance scikit-learn

2. Run the Jupyter Notebook:
jupyter notebook


3. Open the `Stock_Price_Prediction.ipynb` notebook and execute the cells step by step.

## Code Structure
- `Stock_Price_Prediction.ipynb`: Jupyter Notebook containing the main code.
- `model.pkl`: Pickle file containing the trained Linear Regression model.
- `lstm_model.keras`: Keras model file containing the trained LSTM model.

## Usage
1. Run the notebook to train the models.
2. Use the trained models for predictions.

## Models
- **LSTM Model**: Trained using historical stock price data.
- **Linear Regression Model**: Trained as a baseline model.

## Results
The predicted stock prices are compared with the actual prices, and the results are visualized using matplotlib.

## Contributors
- @slayerrr12

Feel free to contribute by opening issues or submitting pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.




