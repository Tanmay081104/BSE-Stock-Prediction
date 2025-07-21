# BSE Stock Predictor 

A comprehensive stock prediction web application focused on the Indian Bombay Stock Exchange (BSE) using machine learning and deep learning algorithms.

## 🎯 Project Overview

This application empowers Indian retail investors with data-driven stock price forecasts, combining multiple ML/DL models to predict BSE stock movements with confidence intervals and actionable insights.

## 🚀 Key Features

- **Interactive Stock Selection**: Choose from BSE-listed stocks with real-time data
- **Multiple ML Models**: LSTM, GRU, ARIMA, Random Forest, Gradient Boosting
- **Real-time Predictions**: Forecast stock prices with customizable time horizons
- **Visual Analytics**: Interactive charts with historical trends and predictions
- **Performance Metrics**: MAPE, RMSE, MAE for model accuracy assessment
- **Support/Resistance Levels**: Automated technical analysis indicators
- **Model Explainability**: Understand prediction reasoning and feature importance

## 🏗️ Project Structure

```
bse-stock-predictor/
├── frontend/                 # Next.js/React frontend
│   ├── components/          # Reusable UI components
│   ├── pages/              # Application pages
│   ├── utils/              # Frontend utilities
│   └── styles/             # CSS/styling files
├── backend/                 # Python FastAPI backend
│   ├── api/                # API endpoints
│   ├── models/             # ML model implementations
│   ├── data/               # Data processing utilities
│   └── utils/              # Backend utilities
├── data/                   # Raw and processed datasets
├── models/                 # Trained model artifacts
├── notebooks/              # Jupyter notebooks for research
└── docs/                   # Project documentation
```

## 🛠️ Technology Stack

### Frontend
- **Framework**: Next.js/React
- **Styling**: Tailwind CSS
- **Charts**: Chart.js/Recharts
- **State Management**: Redux/Zustand
- **Deployment**: Vercel

### Backend
- **Framework**: FastAPI (Python)
- **ML Libraries**: scikit-learn, TensorFlow, PyTorch
- **Data Processing**: pandas, numpy
- **Time Series**: statsmodels, prophet
- **API**: RESTful with real-time WebSocket support

### Data Sources
- **BSE API**: Official BSE data feeds
- **Yahoo Finance**: Historical stock data
- **NSE/BSE**: Real-time market data
- **Economic Indicators**: RBI, Government data

## 🤖 ML/DL Models

### Time Series Models
- **LSTM**: Long Short-Term Memory networks for sequential patterns
- **GRU**: Gated Recurrent Units for efficient time series modeling
- **ARIMA**: Statistical time series forecasting
- **Prophet**: Facebook's robust forecasting tool

### Tabular ML Models
- **Random Forest**: Ensemble method for robust predictions
- **Gradient Boosting**: XGBoost/LightGBM for high performance
- **Support Vector Machines**: For non-linear pattern recognition

### Hybrid Approaches
- **Ensemble Methods**: Combine multiple models for improved accuracy
- **Feature Engineering**: Technical indicators, sentiment analysis
- **Multi-timeframe Analysis**: Short, medium, and long-term predictions

## 📊 Key Metrics & Evaluation

- **Accuracy Metrics**: MAPE, RMSE, MAE, R²
- **Financial Metrics**: Sharpe ratio, maximum drawdown
- **Directional Accuracy**: Prediction of price movement direction
- **Confidence Intervals**: Uncertainty quantification

## 🎯 User Stories

### Primary Users: Retail Investors
- **Stock Analysis**: "I want to analyze RELIANCE stock performance and get 30-day predictions"
- **Model Comparison**: "I want to compare LSTM vs Random Forest predictions for HDFC Bank"
- **Risk Assessment**: "I want to see confidence intervals and risk metrics for my investment decisions"

### Secondary Users: Analysts
- **Batch Processing**: "I want to run predictions for my watchlist of 50 BSE stocks"
- **Custom Parameters**: "I want to adjust model hyperparameters for specific market conditions"

## 🚀 Getting Started

### Prerequisites
- Node.js 16+ and npm
- Python 3.8+
- BSE/NSE API access (optional for real-time data)

### Installation

1. **Clone Repository**
   ```bash
   git clone <repository-url>
   cd bse-stock-predictor
   ```

2. **Setup Backend**
   ```bash
   cd backend
   pip install -r requirements.txt
   python -m uvicorn main:app --reload
   ```

3. **Setup Frontend**
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

4. **Access Application**
   - Frontend: http://localhost:3000
   - Backend API: http://localhost:8000

## 📈 Sample Predictions

The application provides:
- **Price Forecasts**: Next 1, 7, 30, 90 days
- **Trend Analysis**: Bullish/Bearish signals
- **Technical Levels**: Support and resistance zones
- **Volatility Metrics**: Expected price ranges

## 🎓 Academic Value

This project demonstrates:
- **Full ML Pipeline**: Data collection → preprocessing → modeling → deployment
- **Real-world Application**: Addressing actual investor needs
- **Technical Depth**: Multiple algorithms and evaluation methods
- **Software Engineering**: Production-ready web application
- **Data Visualization**: Meaningful charts and dashboards




