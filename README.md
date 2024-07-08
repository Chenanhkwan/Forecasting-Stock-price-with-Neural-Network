# Neural-Network
Neural Network Model: Forecasting stock-price's movement 
This project aims to use a deep neural network to forecast stock-price's movement. 
NOTE: While many researches focus on predicting the stock's price, this project aim to judge whether the stock price will be moving upward or downward in the following period (depends on the type of data), hence, the output of the model are only 0-donwar and 1-upward. The trade is assumed to be traded on commission free platform. The stock used in this project will be walmart. 

<1> Firt step of model building is to select parameters an convert to valid inputs for the model:
  Here in this example, the historical data is collected directly from yahoo finance, and the additional parameters were calculated.
  Beside Adj Close price and volume; "H-L", "O-C", '3day MA', '10day MA', '30day MA', 'Std_dev', RSI, and William %R are calculated.
  Justification for parameter choosing:
    H-L: This measures the volatility of the stock within a single day. Since higher volatility may indicate potential trading opportunities, it is a potential parameter.
    O'C: This captures the day's price movement from opening to closing. Thus, it indicates intraday momentum, showing whether prices are moving upwards or downwards during the day.
    MA (Moving average): These smooth out price data over specified periods and helps identify trends by reducing noise. The averages over different periods also capture short, medium, and long-term trends.
    Std_ev (Standard Deviation):
    RSI (): 
    William %R: 
    
<2>j
<3>
<4>
<5>
<6>
