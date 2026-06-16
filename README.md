# 📈 NexTrade | AI Stock Predictor & Trading Terminal

NexTrade is a modern full-stack web application designed to predict stock market trends and provide actionable trading signals. Combining Ensemble Machine Learning, Deep Reinforcement Learning, and technical indicators, it delivers a high-performance terminal experience for traders.

## 🧠 Key Features

- **AI-Powered Trend Predictions:** Utilizes a trained Machine Learning Ensemble (Random Forest & XGBoost) to forecast stock price movements with confidence scores.
- **Reinforcement Learning (PPO Engine):** Integrates Stable Baselines 3 (`PPO`) inside a custom Gymnasium environment to simulate and optimize automated trading actions (BUY, SELL, HOLD).
- **Interactive Visualizations:** Implements high-performance **Plotly.js** charts featuring Candlestick data, Simple/Exponential Moving Averages (SMA/EMA), MACD, RSI, and Bollinger Bands.
- **Two-Factor Authentication (OTP):** Secure local authentication flow requiring email OTP verification alongside Google OAuth 2.0 login.
- **Premium Glassmorphic UI:** Features a futuristic dark-theme interface, responsive grid layouts, and real-time AJAX updates.

## 🛠️ Technology Stack

- **Backend:** Flask (Python)
- **Database:** SQLite & SQLAlchemy
- **Machine Learning & RL:** Scikit-learn, XGBoost, Stable Baselines 3, Gymnasium
- **Data Source:** Yahoo Finance API (`yfinance`) & Pandas
- **Frontend:** HTML5, Vanilla CSS (Glassmorphism), JavaScript (ES6+), Plotly.js
- **Auth & Mail:** Authlib (Google OAuth), Flask-Mail (OTP verification)
