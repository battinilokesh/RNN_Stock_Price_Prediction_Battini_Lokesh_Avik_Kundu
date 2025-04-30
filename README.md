# RNN_Stock_Price_Prediction_Battini_Lokesh_Avik_Kundu
This model predicts stock prices of four leading tech companies using a recurrent neural network for accurate future market trend analysis.

## OBJECTIVE
This assignment aims to predict stock prices using historical data from IBM (IBM), Google (GOOGL), Amazon (AMZN), and Microsoft (MSFT). Since all four belong to the technology sector, incorporating their data may enhance model performance and capture broader market trends.

## PROBLEM STATEMENT
Using historical stock prices of Amazon, Google, IBM, and Microsoft over a specific timeframe, forecast their future stock values beyond that period by analyzing trends and market patterns for accurate predictions.

## PROFITABILITY FACTOR
Stock market data inherently aligns with RNN-based modeling due to its sequential structure. Daily fluctuations—including opening, closing, and peak prices—form extensive time-series datasets, enabling pattern recognition for forecasting future price movements. Beyond intellectual curiosity, this analysis carries substantial financial significance, as precise predictions can yield substantial profits by capitalizing on emerging market trends.


## Data Understanding
This programming assignment involves developing an RNN-based Python model to predict stock prices. It requires importing essential libraries, understanding the dataset, and handling null values to maintain data integrity. By leveraging the sequential nature of stock market data, the model identifies patterns and trends, enabling accurate forecasting. This process enhances financial analysis, aiding strategic investment decisions for better market insights and profitability.
  
## Data Preparation
- Load and preprocess data – Prepare the dataset by cleaning and formatting it for analysis.
- Split into training and testing sets – Ensure effective model training and evaluation by dividing the data.
- Visualize sample window sizes – Examine different timeframes for stock price predictions.
- Visualize sample window sizes – Examine different timeframes for stock price predictions.
  
## Model Building
- Developing and optimizing SimpleRNN for single-stock predictions – Build, train, and evaluate the model using optimal hyperparameters.
- Constructing and fine-tuning LSTM for single-stock analysis – Train and test the model for enhanced forecasting accuracy.
- Optional: Implementing SimpleRNN for multi-stock predictions – Extend the model to multiple stocks with hyperparameter optimization.
- Optional: Applying LSTM for multi-stock forecasting – Train and refine the model for broader stock analysis.
- Comparative evaluation of SimpleRNN and LSTM – Assess performance across single and multi-stock predictions to determine the best approach.

 
## Conclusions:
-LSTM models outperform SimpleRNN – Predictions are highly accurate and closely aligned with actual values, exhibiting lower Mean Squared Error (MSE).

  - MSE comparison – LSTM models achieve nearly half the error rate of SimpleRNN models, ensuring better forecasting precision.
  - GOOGL performance – Effectively captures overall market trends but shows minor lag during high volatility, especially around peaks and valleys.
    
- GOOGL: The model captures the overall trend well but lags slightly during some volatile periods (noticeable deviations around peaks and valleys).

- MSFT accuracy – Predictions closely match actual stock prices, with minimal under/overshooting, resulting in strong model performance.

- AMZN reliability – Forecasting aligns very closely with actual prices, even during volatile market shifts.

- AMZN: The model tracks actual prices very closely, even during volatility.
 
  
## Acknowledgements

- This project draws inspiration from the ML-AI course at UpGrad and IIIT-B, which provided valuable insights and foundational knowledge. References from UpGrad and IIIT-B were instrumental in shaping the methodology, as their content is well-structured and highly informative.
