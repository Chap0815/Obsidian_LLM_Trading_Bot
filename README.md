# Obsidian Trading Terminal 🚀

Obsidian is an automated cryptocurrency spot-trading bot with a modern desktop interface. It monitors the market around the clock, identifies momentum opportunities, and executes buy and sell orders on your behalf — all based on technical indicators, news sentiment, and market conditions. 

This bot runs 100% locally on your machine. No cloud, no subscriptions, maximum privacy.

## ✨ Key Features

* **Dual Strategies:** The system runs two independent strategies simultaneously: a conservative BALANCED approach and a momentum-focused AGGRESSIVE approach.
* **Local AI Analysis:** The bot supports any text-generation model available through Ollama (e.g., deepseek-r1:14b, qwen2.5:7b) to analyze news and market setups before buying.
* **Automatic Fallback:** When Ollama is not running or no model is loaded, the bot switches automatically to a keyword-based filter.
* **Live Parameter Tuning:** You can tune every parameter live from the interface without restarting the bots.
* **AI Risk Manager:** After 10 completed trades, the system begins learning to automatically adjust position sizes (Kelly Criterion), RSI thresholds, and manage a coin blacklist.
* **Simulation Mode:** Both bots start in Simulation Mode (SIM badge) where no real money is used, allowing you to test the strategies safely.
* **Comprehensive Dashboard:** Includes a browser dashboard showing live positions, trade history, AI learning progress, and market trends.

## 🏦 Supported Exchanges

The bot supports the following exchanges:
* Bitget, Binance, OKX, Bybit, KuCoin, Kraken, Coinbase, Gate.io, MEXC.
* **Recommendation:** Bitget offers the best compatibility as the strategy parameters were optimized using Bitget market data.

## 💻 System Requirements

* **OS:** A computer running Windows 10 or Windows 11 (64-bit).
* **Hardware:** NVIDIA GPU (RTX 30, 40, or 50 series recommended) if you plan to run local LLMs.
* **Prerequisites:** An internet connection for the initial setup and an API key from your exchange with Trade permission enabled.
* **Not Required:** You do NOT need Python installed, any programming knowledge, or admin rights.

## 🛠️ Installation & Quickstart

1. Download the latest release ZIP file and extract it to a permanent location (e.g., `C:\Users\YourName\Desktop\ObsidianBot\`).
2. Do not move individual files out of the folder after installation.
3. Double-click `INSTALL.bat`. The installer will automatically download Python 3.13 Embedded (~30 MB) if needed and install all dependencies.
4. Double-click `OBSIDIAN.vbs` in the program folder, or use the newly created "Obsidian Terminal" shortcut on your Desktop.
5. Follow the Setup Wizard to select your exchange and enter your API credentials.

## 🤖 Optional LLM Setup (AI Sentiment Analysis)

The bot can optionally use a local AI model for more sophisticated buy decisions.

1. Download Ollama from ollama.com and install it.
2. Open a command prompt and run: `ollama pull deepseek-r1:14b` (or any other supported model).
3. Start Ollama: `ollama serve`.
4. The sidebar in Obsidian Terminal will show "LLM: Ready" within a few seconds.

## ☕ Support & Donate

This project is completely free and built in my spare time. If this bot makes your workflow easier and you'd like to support future updates, I would be incredibly grateful for a small crypto donation!

* **Bitcoin (BTC):** `bc1qlee9wgt7d6pezdaf3n6784t43h8hj99qrylyv5`
* **Litecoin (LTC):** `LPmByUGT2ibFdSRk5UrPN11BmRp2UvNuuC`
* **Solana (SOL) - Low fees for small tips:** `41c8GgqzLx7WSavA8Md4xGhYXosHDFgKC4RNfqLcUKVU`

**Feedback & Contact:** Feedback is welcome at: [ Discord:@chap0815. / E-Mail:geeclan92@googlemail.com ].

## ⚠️ Disclaimer

Obsidian Trading Terminal — Use at your own risk. Cryptocurrency trading involves significant financial risk. Past backtest performance does not guarantee future results. Never invest more than you can afford to lose.
