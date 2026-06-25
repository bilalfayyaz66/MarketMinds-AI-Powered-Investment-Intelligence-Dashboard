# MarketMinds — AI-Powered Investment Intelligence Dashboard

MarketMinds is an AI-powered financial analysis platform designed to help users make smarter investment decisions through a unified visual dashboard.

The project combines market data collection, AI-based prediction, chart pattern recognition, sentiment analysis, portfolio analytics, and real-time dashboard visualization into one system. It was developed as a final year project with a focus on practical AI engineering, fintech automation, and data-driven decision support.

> This public repository is a project showcase. The complete production source code, credentials, trained models, and private deployment files are not included for security and academic integrity reasons.

---

## Project Overview

Many investors, students, and small businesses rely on multiple tools for market data, news, technical analysis, and portfolio tracking. These workflows are often fragmented, expensive, or difficult for beginner users.

MarketMinds addresses this problem by providing a single AI powered dashboard that can support:

* Real-time market data analysis
* AI-based price prediction
* Chart image upload and pattern detection
* Financial news sentiment analysis
* AI-generated BUY / HOLD / SELL signals
* Portfolio risk and allocation insights
* Google OAuth-based authentication
* Cloud-ready deployment architecture

The goal of the project is not to replace professional financial advisors, but to provide an intelligent decision-support system that makes market analysis more accessible, explainable, and organized.

---

## Key Features

### 1. Market Data Pipeline

The system collects and processes financial, crypto, and economic data from multiple sources.

Supported data sources include:

* Yahoo Finance
* CoinGecko
* FRED economic indicators
* NewsAPI
* User-uploaded chart images

The pipeline cleans, normalizes, and prepares the data for downstream AI and analytics modules.

---

### 2. AI-Based Price Prediction

MarketMinds uses machine learning models to support price movement prediction and market trend analysis.

The prediction module works with historical OHLCV data, technical indicators, and economic event features.

Models and techniques considered in the project include:

* LSTM
* XGBoost
* Random Forest
* LightGBM
* CatBoost
* Feature engineering for CPI, PPI, NFP, and FOMC events

---

### 3. Computer Vision for Chart Pattern Recognition

The platform supports chart image upload and AI-based analysis.

The chart analysis module is designed to detect patterns such as:

* Candlestick formations
* Breakouts
* Trend movements
* Head and shoulders
* Triangles
* Support and resistance areas

Computer vision and deep learning techniques such as OpenCV and CNN-based approaches are used for chart pattern analysis.

---

### 4. News Sentiment Analysis

The sentiment analysis module processes financial news and social media content to estimate market sentiment.

The pipeline includes:

* News ingestion
* Text preprocessing
* Tokenization
* Lemmatization
* Financial sentiment scoring
* Sentiment aggregation over time

The project uses financial NLP concepts such as FinBERT-based sentiment scoring and weighted sentiment aggregation.

---

### 5. AI Signal Generation

MarketMinds combines multiple signals into a single investment decision-support output.

The signal engine considers:

* Price prediction confidence
* Pattern recognition confidence
* Sentiment score
* Technical indicators
* Economic surprise features
* Volatility behavior

The final output is presented as a ranked BUY / HOLD / SELL signal with confidence-based interpretation.

---

### 6. Portfolio Analytics

The portfolio module helps users analyze investment allocations and risk.

Supported portfolio concepts include:

* Watchlist-based asset selection
* Mean-Variance Optimization
* Sharpe Ratio
* Sortino Ratio
* Maximum Drawdown
* Value at Risk
* Rebalancing alerts
* AI-supported allocation suggestions

---

### 7. Reinforcement Learning Trading Agent

The project also explores reinforcement learning for trading decision support.

The RL module is designed around:

* PPO-based learning
* BUY / HOLD / SELL action space
* Historical OHLCV market environment
* Transaction-cost-aware reward function
* Sharpe-ratio-aware evaluation
* Real-time RL signal API design

---

### 8. Dashboard and User Interface

The frontend dashboard is designed to present complex market intelligence in a simple and usable way.

The dashboard includes:

* Market overview
* AI predictions
* Sentiment feed
* Portfolio manager
* Chart analysis panel
* Alerts and reports
* Authentication-based user access

---

## System Architecture

MarketMinds follows a modular architecture:

```txt
Data Sources
    ↓
Data Collection & Preprocessing
    ↓
AI / ML Analysis Layer
    ↓
Backend API Services
    ↓
Frontend Dashboard
    ↓
Investor / User
```

Main system modules:

1. Data Collection and Preprocessing
2. Data Processing and AI Analysis
3. Backend and API Services
4. User Interface and Visualization
5. Sentiment and Signal Generation
6. Portfolio Management
7. Reinforcement Learning Agent
8. Authentication and Deployment Layer

---

## Tech Stack

### Frontend

* React.js
* JavaScript
* Dashboard visualization components
* Google OAuth frontend integration

### Backend

* FastAPI
* Flask
* REST APIs
* WebSocket-based real-time updates
* JWT authentication

### AI / ML

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* LightGBM
* CatBoost
* LSTM
* CNN
* OpenCV
* FinBERT
* Stable-Baselines3 PPO

### Data Sources

* Yahoo Finance
* CoinGecko
* FRED
* NewsAPI
* Social/news feeds
* User-uploaded chart images

### Deployment

* Docker
* Google Cloud Platform
* Cloud Run
* PostgreSQL
* Redis
* GitHub Actions
* Terraform concept design

---

## Testing Summary

The system was tested across all major modules, including:

* Economic data collection
* Feature engineering
* Price prediction model training
* Pattern recognition
* Sentiment analysis
* AI signal generation
* Portfolio optimization
* Reinforcement learning signal API
* Google OAuth login
* Cloud deployment health
* End-to-end dashboard integration

A total of 19 test cases were documented across the project iterations.

---

## My Contributions

My major contributions included:

* API integration and management
* Pattern recognition feature development
* AI signal generation engine
* Portfolio analytics backend
* Google Auth API integration
* Report development and system documentation

---

## Project Status

This project was developed as a final year academic project.

Current public repository status:

* Documentation available
* Architecture overview available
* Feature summary available
* Selected pseudocode available
* Screenshots and diagrams available
* Full private implementation not publicly released

---

## Security and Privacy Notice

The complete source code, model files, API keys, credentials, database schemas, and deployment configuration are not included in this public repository.

This is done to protect:

* API credentials
* Authentication secrets
* Cloud deployment configuration
* Academic project integrity
* Private implementation details


---

## Team

* Bilal Fayyaz
* M. Inam Ul Haq
* Asim Shahzad

Supervised by: Mr. Sohail Abbas

Department of Computer Science
National University of Technology, Islamabad, Pakistan
