# Fibonacci Volume Trend ATR Strategy

## 📌 Overview
This trading strategy integrates **volume surges, Fibonacci retracement levels, a 200-SMA trend filter, and ATR-based or Fixed 1% Take Profit** to enhance trade decision-making. By combining multiple technical indicators, it aims to identify high-probability entry and exit points.

## 🌟 Purpose & Use Cases
This Pine Script strategy is designed for **automated trading and backtesting** on **TradingView**. It helps traders make informed decisions by combining multiple technical indicators.

### ✅ Key Features:
1. **Identifies High-Probability Buy Signals**
   - Uses **Fibonacci retracement (0.618 & 0.5)** to detect support & resistance levels.
   - Confirms trades with **volume surges** (above the 24-period average).
   - Ensures trades align with the **trend** using a **200-SMA filter**.

2. **Risk Management & Profit Optimization**
   - Uses **ATR (Average True Range)** to dynamically set stop-loss & take-profit levels.
   - Offers two versions: **Fixed 1% Take Profit** and **ATR-Based Take Profit**.
   - Higher timeframes (**4H, 1D, 1W**) offer **better accuracy & profitability**.

3. **Backtesting & Strategy Optimization**
   - Test performance on **historical data** before live trading.
   - Works with **crypto, stocks, and forex markets**.

### 👤 Who Should Use This?
- **Swing & Trend Traders** – Ideal for longer-term trades using Fibonacci & trend analysis.
- **Crypto & Stock Traders** – Suitable for **high-volume** markets.
- **TradingView Users** – Designed for those looking to **automate or backtest strategies**.

## 📖 Table of Contents
- [Overview](#-overview)
- [Purpose & Use Cases](#-purpose--use-cases)
- [Available Strategy Versions](#-available-strategy-versions)
- [Strategy Components](#-strategy-components)
- [Entry & Exit Conditions](#-entry--exit-conditions)
- [Timeframe Considerations](#-timeframe-considerations)
- [Backtest Performance Summary](#-backtest-performance-summary)
- [Installation](#-installation)
- [How to Use](#-how-to-use)
- [Important Notes](#-important-notes)
- [License & Disclaimer](#-license--disclaimer)

## 📂 Available Strategy Versions
We provide **two variations** of this strategy:

### 1️⃣ **Fixed 1% Take Profit Version**
📌 **File:** `FibTrend_1%_TP.pine`
🔹 This version sets a **fixed 1% take profit** per trade. Ideal for **short-term traders** looking for quick gains.

### 2️⃣ **ATR-Based Take Profit Version**
📌 **File:** `FibTrend_ATR.pine`
🔹 This version **dynamically adjusts take profit** based on **market volatility (ATR)**. Best for **adaptive risk management**.

## ✅ Strategy Components
- 🌊 **Volume Surges:** Trades are executed when significant market activity is detected.
- 💢 **Fibonacci Retracement:** Uses **0.618** and **0.5** levels to identify key support and resistance zones.
- 📈 **Trend Filter:** A 200-period SMA confirms overall market direction.
- 🎯 **ATR-Based Take Profit:** Dynamically adjusts profit targets based on market volatility.
- 💰 **Fixed 1% Take Profit:** Ensures consistent short-term gains.

## 🎯 Entry & Exit Conditions
- **📈 Buy Entry:** Triggered when the price is above the 0.618 Fibonacci level, volume surges, and the market is in an uptrend (above SMA 200).
- **📉 Exit:** Occurs when the price falls below the 0.5 Fibonacci level or reaches the take-profit target (either 1% fixed or ATR-based).

## ⏳ Timeframe Considerations
Higher timeframes (such as **4H, 1D, or 1W**) tend to provide **better profit percentages** as they reduce market noise and improve trade reliability. Lower timeframes (**15m, 30m, 1H**) may result in more frequent but less reliable trades. Adjust settings accordingly based on your risk tolerance and trading style.

## 📊 Backtest Performance Summary(BTCUSDT)
- **Win Rate:** 79.83% & 91.58%  
- **Average RRR:** 1:2 
- **Best Timeframe:** 4H & 1D  

## 📥 Installation
1. Clone the repository:  
   ```sh
   git clone https://github.com/yourusername/FibTrend-Pro-Strategy.git
   ```
2. Open your preferred strategy file in **TradingView's Pine Editor**:  
   - **`FibTrend_1%_TP.pine`** for fixed 1% take profit.  
   - **`FibTrend_ATR.pine`** for ATR-based take profit.  
3. Click **Add to Chart** and test it!  

## 🛠️ How to Use
1. Copy and paste the **Pine Script** code into **TradingView's Pine Editor**.
2. Apply the script to your preferred trading chart.
3. Adjust settings based on your trading strategy and market conditions.
4. Conduct thorough backtesting before implementing in live trading.

## ⚠️ Important Notes
- Always apply proper **risk management** when using this strategy.
- Modify **Fibonacci levels, ATR settings, and SMA periods** to adapt to different market conditions.
- Suitable for **crypto and stock markets** with sufficient liquidity.

## 📝 License & Disclaimer
This strategy is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

🚨 **Disclaimer:** This strategy is for educational purposes only and does not constitute financial advice. Use at your own risk. Trading involves financial risk, and past performance does not guarantee future results. Always test before live trading.

