Stock Market Forecasting

This project focuses on "time series analysis and forecasting of stock prices" using both statistical and deep learning models. Implemented as part of a Data Analytics internship at ZIDIO, the goal was to understand trends, seasonality, and future price behavior.

Project Objectives
- Perform exploratory data analysis (EDA) on stock price data
- Apply statistical models like ARIMA and SARIMA
- Implement deep learning with LSTM
- Use Facebook Prophet for flexible trend/seasonality modeling
- Evaluate and compare models for accuracy

Models Implemented
| Model              | Purpose                                  |
|--------------------|------------------------------------------|
| ARIMA              | Non-seasonal time series forecasting     |
| SARIMA             | Seasonal time series modeling            |
| Prophet            | Multiple seasonality + external factors  |
| LSTM               | Deep learning-based sequence modeling    |

Tech Stack
- Language:Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, pmdarima, Prophet, TensorFlow, Keras, Scikit-learn
- Notebook Environment: Jupyter Notebook / Google Colab

Project Structure
├── stock_forecasting.ipynb # Main notebook with code
├── stock_market_report.pdf # Final report
├── data
├── requirements.txt Python dependencies
└── README.md # Project overview

Evaluation Metrics
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- MAPE (Mean Absolute Percentage Error)

Results & Insights
- LSTM showed best performance for short-term, volatile patterns
- Prophet excelled in capturing trend + calendar effects
- SARIMA provided interpretable, consistent forecasts for stable segments

Team Members
- Sabahath Taj Z – ARIMA modeling, evaluation & tuning  
- Atharv Savai – Data preprocessing, Prophet & LSTM implementation  
- Riya Yadav – SARIMA modeling, report creation & visualization

Dataset
- Source: [Kaggle]
- Contains daily stock prices: Open, High, Low, Close, Volume

How to Use
1. Clone the repo
2. Install dependencies from `requirements.txt` (if included)
3. Open `stock_forecasting.ipynb` and run the cells
4. Read the report for detailed results and comparisons

Future Improvements
- Integrate external events or news sentiment for enhanced predictions
- Deploy a web-based visualization dashboard using Streamlit
- Automate daily retraining using updated stock feeds

License
This project is for educational purposes. For reuse or collaboration, please credit the contributors.

Made during my internship at ZIDIO.



