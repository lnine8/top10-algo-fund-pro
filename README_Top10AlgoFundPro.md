# 🧠 Top10Algo Fund Pro

A modular, AI-augmented multi-strategy hedge fund framework using the top 10 algorithmic trading strategies. Built for research, backtesting, and real deployment — with GPT agents, machine learning filters, ERC-4626 vault contracts, and a live performance dashboard.

---

## 🔧 Features

- ✅ 10 Proven Quant Strategies (Momentum, StatArb, Sentiment, etc.)
- 🤖 GPT Agent to Auto-Generate and Mutate New Strategies
- 🧠 Machine Learning Filters (LightGBM, XGBoost)
- 📊 Streamlit Dashboard: Live Sharpe, Drawdown, WinRate
- 📈 Backtest Engine with Sample Results
- 💼 ERC-4626 Smart Vault Contract for LP Tokenization
- 🗂️ GitHub-Ready Modular Folder Structure

---

## 📂 Project Structure

```
top10-algo-fund-pro/
├── strategies/            # Trading strategy logic
├── ml_models/             # ML classifiers and signal filters
├── backtests/             # Backtest runners + strategy examples
├── optimization/          # Bayesian tuning modules
├── contracts/             # Solidity smart contract (ERC-4626)
├── agents/                # GPT prompt template + agent logic
├── dashboard/             # Streamlit dashboard app
├── docs/                  # Pitch deck summary, whitepaper, etc.
├── utils/                 # Helper functions
├── data/                  # Data loading, preprocessing
├── README.md              # Project overview and setup
└── requirements.txt       # Python package dependencies
```

---

## 🚀 Quickstart

### 1. Clone the repo

```bash
git clone https://github.com/lnine8/top10-algo-fund-pro.git
cd top10-algo-fund-pro
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the dashboard

```bash
streamlit run dashboard/streamlit_app.py
```

---

## 🧠 GPT Strategy Agent

Prompt template included in:
```
agents/gpt_strategy_prompt_template.txt
```

Sample prompt:
```
You are a quantitative strategist. Generate a new trading strategy:

Market: Crypto
Objective: Sharpe > 2.0
Timeframe: 1h
Return format:
- Entry logic
- Exit logic
- Stop loss
- Expected Sharpe
```

---

## 🛡 Smart Contract

A compliant ERC-4626 vault is included in `contracts/Top10AlgoVault.sol` to tokenize LP stakes and allow decentralized capital management.

---

## 📊 Sample Backtest Results

Located in: `backtests/strategy_examples.txt`

| Strategy           | Sharpe | Max DD | Win Rate |
|--------------------|--------|--------|----------|
| Momentum RSI       | 2.6    | 8.2%   | 62%      |
| Stat Arb (MSFT/AAPL) | 3.1  | 6.7%   | 65%      |
| Sentiment Surge    | 1.9    | 9.4%   | 59%      |

---

## 📄 License

MIT License — feel free to fork, adapt, and contribute.

---

## 🧩 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you’d like to modify.

---

## 💬 Contact

Built with 💡 by [@lnine8](https://github.com/lnine8)  
Email: your.email@example.com  
