<!-- ───────────────────────────────────────────────────────────── -->
<!--                    HERO BANNER                                 -->
<!-- ───────────────────────────────────────────────────────────── -->

<div align="center">

<a href="https://t.me/Padudu0815">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0f,40:1a0b2e,80:6D28D9,100:8B5CF6&height=240&section=header&text=◆%20OBSIDIAN&fontSize=78&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI-Powered%20Crypto%20Trading%20Terminal&descAlignY=58&descSize=20&descAlign=50" alt="Obsidian Trading Terminal"/>
</a>

<h3>
  <em>Three specialized bots</em> · <em>Spot &amp; Perpetuals</em> · <em>Local LLM intelligence</em>
</h3>

<p>
  <em>A native desktop terminal for autonomous crypto trading.</em><br/>
  <em>100&nbsp;% local. 0&nbsp;% cloud. 0&nbsp;€ recurring fees.</em>
</p>

<br/>

<!-- ───── PRIMARY BADGES ───── -->
<p>
  <a href="#-whats-new-in-22"><img src="https://img.shields.io/badge/Version-2.2-8B5CF6?style=for-the-badge&labelColor=0a0a0f" alt="Version"/></a>
  <a href="https://python.org"><img src="https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=0a0a0f" alt="Python"/></a>
  <a href="https://ollama.ai"><img src="https://img.shields.io/badge/LLM-Ollama-FF6B6B?style=for-the-badge&logo=ollama&logoColor=white&labelColor=0a0a0f" alt="LLM"/></a>
  <a href="#-supported-exchanges"><img src="https://img.shields.io/badge/Exchanges-9-F7931A?style=for-the-badge&labelColor=0a0a0f" alt="Exchanges"/></a>
  <a href="https://t.me/Padudu0815"><img src="https://img.shields.io/badge/Telegram-@Padudu0815-26A5E4?style=for-the-badge&logo=telegram&logoColor=white&labelColor=0a0a0f" alt="Telegram"/></a>
</p>

<!-- ───── SECONDARY BADGES ───── -->
<p>
  <img src="https://img.shields.io/badge/Tests-46%20passing-22c55e?style=flat-square&logo=pytest&logoColor=white&labelColor=0a0a0f" alt="Tests"/>
  <img src="https://img.shields.io/badge/Phase%203-Hardened-22c55e?style=flat-square&labelColor=0a0a0f" alt="Hardened"/>
  <img src="https://img.shields.io/badge/Windows-blue?style=flat-square&logo=windows&logoColor=white&labelColor=0a0a0f" alt="Windows"/>
  <img src="https://img.shields.io/badge/Linux-yellow?style=flat-square&logo=linux&logoColor=white&labelColor=0a0a0f" alt="Linux"/>
  <img src="https://img.shields.io/badge/100%25-Local-22c55e?style=flat-square&labelColor=0a0a0f" alt="Local"/>
  <img src="https://img.shields.io/badge/No-Cloud-ef4444?style=flat-square&labelColor=0a0a0f" alt="No Cloud"/>
</p>

<br/>

<!-- ───── BOT BADGES ───── -->
<kbd>&nbsp;🤖&nbsp;&nbsp;<b>BALANCED</b>&nbsp;</kbd> &nbsp; <kbd>&nbsp;⚡&nbsp;&nbsp;<b>AGGRESSIVE</b>&nbsp;</kbd> &nbsp; <kbd>&nbsp;📈&nbsp;&nbsp;<b>FUTURES</b>&nbsp;</kbd>

<br/><br/>

<!-- ───── KPI HIGHLIGHTS ───── -->
<table>
<tr>
  <td align="center" width="155">
    <h2>3</h2>
    <sub><b>BOT STRATEGIES</b></sub><br/>
    <sub>Balanced · Aggressive · Futures</sub>
  </td>
  <td align="center" width="155">
    <h2>30</h2>
    <sub><b>MAX. TRADES</b></sub><br/>
    <sub>Open in parallel</sub>
  </td>
  <td align="center" width="155">
    <h2>10×</h2>
    <sub><b>MAX. LEVERAGE</b></sub><br/>
    <sub>Isolated · Liq-Buffer</sub>
  </td>
  <td align="center" width="155">
    <h2>11</h2>
    <sub><b>NEWS SOURCES</b></sub><br/>
    <sub>Aggregated in parallel</sub>
  </td>
  <td align="center" width="155">
    <h2>100%</h2>
    <sub><b>LOCAL · PRIVATE</b></sub><br/>
    <sub>No cloud, no tracking</sub>
  </td>
</tr>
</table>

<br/>

<!-- ───── PRIMARY CTA ───── -->
<p>
  <a href="#-quick-installation"><img src="https://img.shields.io/badge/▶_Install_in_5_minutes-Quick_Start-8B5CF6?style=for-the-badge&labelColor=0a0a0f" alt="Quick Install"/></a>
  &nbsp;
  <a href="#-whats-new-in-22"><img src="https://img.shields.io/badge/What's_New-v2.2-22c55e?style=for-the-badge&labelColor=0a0a0f" alt="What's New"/></a>
</p>

</div>

---

## ⚡ What is Obsidian?

> **Obsidian** is a complete trading terminal that runs **three specialized bots in parallel** inside one native desktop window. Every trading decision is made by a **locally running language model** (Ollama / DeepSeek-R1) — **no external AI service, no API key, no cloud subscription.**

<div align="center">

<!-- DASHBOARD PREVIEW -->
<table width="100%">
<tr>
<td align="left"><sub><b>◆ &nbsp; OBSIDIAN TRADING TERMINAL</b></sub></td>
<td align="right"><sub><code>v 2.2</code> &nbsp; <code>● LIVE</code></sub></td>
</tr>
</table>

<img width="2194" height="1195" alt="Obsidian Trading Terminal v2.2 — Dashboard"
     src="https://github.com/user-attachments/assets/2c222b2a-2ae5-4555-b2e9-71f9a169c987" />

</div>

---

## 🆕 What's New in 2.2

> **Phase 3 — Production Hardening.** A systematic 174-point audit found
> race conditions, silent-drift bugs and dead kill-switches. This release ships **60+ targeted fixes** spanning concurrency, security and risk-management correctness.

<table>
<tr>
<td valign="top" width="33%">

### 🔴 Money-loss risks closed
- **Per-symbol close locks** prevent double-sells between the shutdown handler and the main loop
- **Slippage circuit-breaker** now *reverts* over-slippage fills instead of leaving phantom positions
- **API kill-switch** finally works — `ok=0` now actually persists for error-rate queries
- **Cross-process rate limiter** via SQLite — three bots no longer triple your IP-ban risk

</td>
<td valign="top" width="33%">

### 🟠 Reliability boosts
- **Backtest = Live universe**: volume threshold (5 M USDT) and coin pool (60) unified
- **State-manager** rewritten with a single dedicated writer thread (no more thread-per-save)
- **F&G circuit-breaker** falls back to neutral 50 when cached data is > 1 h stale
- **Kelly** confidence ramp from 0.1 → 1.0 over 60 samples (was overconfident at 30)

</td>
<td valign="top" width="33%">

### 🔒 Security hardened
- **`redact()`** strips API keys / Authorization headers / Telegram tokens from every traceback
- **`.env` injection** blocked: newlines, null bytes and control chars rejected at setup
- **CryptoPanic token** moved out of URLs into `params` so it can't leak via referrer
- **Cooldown TOCTOU race** fixed with PID-check + atomic rename takeover

</td>
</tr>
</table>

<details>
<summary><b>📋 Full changelog — 60+ fixes</b> (click to expand)</summary>

| ID | Severity | Area | Fix |
|----|----------|------|-----|
| K-01 | 🔴 Critical | Concurrency | Per-symbol close locks (NEW `symbol_locks.py`) |
| K-02 | 🔴 Critical | Memory | Refcount cleanup for futures-bot close locks |
| K-03 | 🔴 Critical | Strategy | Backtest universe = live universe (5 M / 60 coins) |
| K-04 | 🔴 Critical | Kill-switch | `ok=0` now persisted — API-error monitoring works |
| K-05 | 🔴 Critical | Threading | `copy.deepcopy(markets)` (was shallow) |
| K-06 | 🔴 Critical | Threading | Per-thread CCXT clones via `threading.local` |
| K-07 | 🔴 Critical | Accounting | Fees no longer over-reported by 40% for VIP accounts |
| K-08 | 🔴 Critical | Rate-limit | Cross-process SQLite token bucket |
| K-09 | 🔴 Critical | Execution | Slippage revert — opposing reduce-only order on breach |
| K-10 | 🔴 Critical | Accounting | BUSD removed from stablecoin equivalents |
| K-11 | 🔴 Critical | Safety | Sell-logic survives API failures |
| K-13 | 🔴 Critical | Locking | `portalocker` mandatory (was best-effort O_EXCL) |
| K-14 | 🔴 Critical | Backtest | SHORT-close uses correct slippage side |
| K-15 | 🔴 Critical | Locking | TOCTOU race in stale-lock detection eliminated |
| K-16 | 🔴 Critical | Logging | Telegram-overflow log rotation (10 MB) |
| K-19 | 🔴 Critical | Logging | JSONL append cross-process safe (portalocker) |
| K-20 | 🔴 Critical | Performance | `save_trade` no longer O(n²) |
| K-21 | 🔴 Critical | Migration | `init_db()` runs once in launcher pre-fork |
| K-22 | 🔴 Critical | Threading | State-manager single dedicated writer thread |
| K-23 | 🔴 Critical | Schema | Dedup index covers `is_futures` |
| H-04…H-23 | 🟠 High | Various | 12 reliability and logic fixes |
| L-04…L-22 | 🟠 High | Logic | 6 strategy/optimizer correctness fixes |
| S-01…S-14 | 🟠 High | Security | 6 secret-leak / injection fixes |
| X-01…X-03 | 🟡 Medium | Drift | Constants centralized — no more 4-way drift |
| LT-01, LT-07 | 🟡 Medium | Long-term | VACUUM scheduler, error-log rotation |

**Test suite:** 46 tests, all green. See `CHANGELOG.md` for full detail.

</details>

---

## 📑 Table of Contents

<table>
<tr>
<td valign="top" width="50%">

**Getting Started**
- [⚡ Quick Installation](#-quick-installation)
- [✅ Requirements](#-requirements)
- [📥 Step-by-Step Installation](#-step-by-step-installation)
- [🧠 LLM Setup (Ollama)](#-setting-up-the-llm-ollama)
- [🌐 Supported Exchanges](#-supported-exchanges)

**Capabilities**
- [🚀 Feature Overview](#-feature-overview)
- [🎯 The Three Strategies](#-the-three-strategies)
- [🤖 AI Features in Detail](#-ai-features-in-detail)

</td>
<td valign="top" width="50%">

**Operations**
- [🛡️ Risk Management](#-risk-management-system)
- [🔐 Security & Privacy](#-security--privacy)
- [📊 Backtest & Optimizer](#-backtest--optimizer)
- [📈 Dashboard](#-dashboard)

**Reference**
- [🏗️ Architecture](#-architecture)
- [⚙️ Parameter Reference](#-parameter-reference)
- [🛠️ Troubleshooting](#-troubleshooting)
- [🗺️ Roadmap](#-roadmap)
- [⚠️ Disclaimer](#-disclaimer)

</td>
</tr>
</table>

---

## 🚀 Feature Overview

### 🧠 Core

| Feature | Description |
|---|---|
| **3 independent bots** | BALANCED (Spot), AGGRESSIVE (Spot), FUTURES (Perpetuals Long/Short) |
| **Local LLM** | Ollama — DeepSeek-R1, Qwen, Mistral, Llama — no cloud subscription |
| **Bull/Bear Adversarial Mode** | Second LLM call critically challenges every buy decision |
| **Reflection Loop** | Loss pattern analysis injects learning context into the next prompt |
| **Auto Symbol Scoring** | Candidates ranked by Vol-Surge, RSI-Momentum & Win-Rate |
| **Multi-Source News** | 11 sources in parallel: CryptoPanic · Reddit · 8 RSS feeds · CoinGecko |
| **Editable AI Prompts** | Per-bot prompt editable live — directly in the terminal, with validation |
| **LLM Fallback** | On Ollama failure: keyword-based filter runs automatically |
| **SIM/LIVE Toggle** | Each bot independently switchable with confirmation dialog |
| **Unrealized PnL Live** | Real-time display of open positions per bot and as a total |

### 📊 Tools & Analytics

| Feature | Description |
|---|---|
| **K-Fold Optimizer** | 30,000+ parameter combinations · 4-Fold CV · Robustness score |
| **Backtester** | Historical Binance data · real fee modeling · live output |
| **Streamlit Dashboard** | 5 tabs: KPIs · Equity curve · Positions · Sharpe/Sortino · Bot comparison |
| **Win/Loss Heatmap** | Win-rate by hour × weekday — 30-day window |
| **Emergency Close** | Futures: close all positions immediately with `reduceOnly` orders |

### 🛡️ Robustness & Privacy

| Feature | Description |
|---|---|
| **Graceful Shutdown** | SIGTERM → per-symbol close locks → close positions → persist DB → exit |
| **State Reconciliation** | On startup: reconcile local state vs. real exchange balance |
| **Atomic File Writes** | tmp + fsync + os.replace — corrupted files on crash impossible |
| **SQLite WAL-Mode** | 7 tables · read queries never block writing bots |
| **Cross-Process Locks** | `portalocker` for cooldown · advisory locks for migrations |
| **Circuit Breaker** | Exponential backoff on API errors (up to 10 min.) |
| **Telegram** | Buy/sell notifications with proxy support · credentials redacted in logs |
| **100 % local** | No data leaves your machine |

---

## 🎯 The Three Strategies

<table>
<tr>
<td width="33%" valign="top">

### 🤖 BALANCED
**Spot · Risk-Aware**

Optimizer-validated (60 days · 30,240 combos · K-Fold 4). Buys early in momentum, lets winners run.

```yaml
Min. Pump      : 2.0 %
Activation TP  : 9.0 %
Trailing       : 2.0 %
Stop-Loss      : −4.0 %
Partial Sell   : 30 %
Max Trades     : 5
Scan           : 300 s
RSI Max        : 65
Daily Limit    : −50 $
```

</td>
<td width="33%" valign="top">

### ⚡ AGGRESSIVE
**Spot · Momentum**

Higher entry threshold catches only strong breakouts. 60% partial exit locks in profits early.

```yaml
Min. Pump      : 6.0 %
Activation TP  : 9.0 %
Trailing       : 3.0 %
Stop-Loss      : −6.0 %
Partial Sell   : 60 %
Max Trades     : 5
Scan           : 150 s
RSI Max        : 65
Daily Limit    : −50 $
```

</td>
<td width="33%" valign="top">

### 📈 FUTURES
**Perpetuals · Long/Short**

The LLM decides the direction (LONG / SHORT / WAIT). Break-even trigger, liquidation safety buffer.

```yaml
Min. Pump      : 2.0 %
Activation TP  : 4.5 %
Trailing       : 2.5 %
Stop-Loss      : −3.5 %
Leverage       : 3 ×
Liq Buffer     : 25 %
Max Trades     : 3
Break-Even     : 2.0 %
Daily Limit    : −30 $
```

</td>
</tr>
</table>

> 💡 **All defaults are optimizer-validated.** Run the K-Fold optimizer after switching exchanges or changing market regimes to re-tune.

---

## ⚡ Quick Installation

```text
1.  Download ZIP and extract  (recommended: C:\ObsidianBot\)
2.  Double-click  INSTALL.bat
3.  Wait until  "Setup Complete!"  appears  (2–5 minutes)
4.  Double-click  OBSIDIAN.vbs  →  Setup Wizard  →  done
```

> 💡 **No Python required.** The installer downloads Python 3.13 Embedded (~30 MB) automatically.

<br/>

<div align="center">

| Step 1 | Step 2 | Step 3 | Step 4 |
|:---:|:---:|:---:|:---:|
| 📥 Download | 🔧 INSTALL.bat | ▶️ OBSIDIAN.vbs | 🎯 Trade |
| Extract ZIP | One-click setup | Run launcher | Configure & go |

</div>

---

## ✅ Requirements

<table>
<tr>
<td valign="top" width="50%">

**Required**
- Windows 10 / 11 (64-bit) — Linux with Python 3.11+ also works
- Internet connection for initial installation
- Exchange account with API key (**trade permission only — never withdrawal**)

</td>
<td valign="top" width="50%">

**Optional but recommended**
- [Ollama](https://ollama.ai) for AI decisions
- NVIDIA GPU for faster LLM inference
- CryptoPanic API token for extended news
- Telegram bot token for push notifications

</td>
</tr>
</table>

**Not required:** Pre-installed Python · Programming knowledge · Admin rights

---

## 📥 Step-by-Step Installation

### 1 — Download and Extract
- Download ZIP file → Right-click → **Extract All**
- Extract to a permanent folder — **not** into `Downloads`
- Recommended: `C:\ObsidianBot\`

> ⚠️ Do not move individual files out of the folder. The `prompts/` subfolder must remain next to `launcher.pyw`.

### 2 — Run Installer
```text
[1/4] Checking Python...
[2/4] Downloading Python 3.13 Embedded (~30 MB)    ← only if Python is missing
[3/4] Installing dependencies (2–5 min)...
[4/4] Creating desktop shortcut...
       Setup Complete!
```

> 📦 **Packages:** `customtkinter` · `psutil` · `ccxt` · `pandas` · `pandas_ta` · `python-dotenv` · `requests` · `feedparser` · `ollama` · `streamlit` · `plotly` · `portalocker`

### 3 — First Launch and Setup Wizard
**Double-click `OBSIDIAN.vbs`** (or desktop shortcut) — the Setup Wizard opens on first launch.

| Step | Action |
|---|---|
| **1** Choose exchange | Click on exchange. Strategy optimized on Bitget data. |
| **2** API credentials | ✅ Trade · ✅ Futures (for FUTURES bot) · ❌ **NEVER** Withdrawal |
| **3** Proxy (optional) | Only in restricted regions |
| **4** Optional services | Telegram · CryptoPanic · Connection test |

**Passphrase required?**

| Exchange | Passphrase |
|---|:---:|
| Bitget · OKX · KuCoin | ✅ Yes |
| Binance · Bybit · Kraken · Coinbase · Gate.io · MEXC | ❌ No |

---

## 🧠 Setting Up the LLM (Ollama)

The bots also work without an LLM via a keyword-based fallback. With LLM, decisions are **significantly more precise** — and the Bull/Bear Challenge + Reflection Loop only truly shine with LLM enabled.

```bash
# 1. Download Ollama: https://ollama.ai

# 2. Choose and pull a model
ollama pull deepseek-r1:14b   # Best quality  · ~8 GB VRAM/RAM
ollama pull deepseek-r1:7b    # Good          · ~4 GB
ollama pull qwen2.5:7b        # Fast + good   · ~4 GB
ollama pull mistral:7b        # Reliable      · ~4 GB
ollama pull llama3.2:3b       # Very fast     · ~2 GB

# 3. Start the server
ollama serve
```

> ✨ In the terminal: Sidebar → **CONNECTIONS → LLM: Ready** (green). Bot card → AI badge switches to **AI: LLM** on first trade. Model change detected within 5 seconds.

---

## 🌐 Supported Exchanges

| Exchange | Spot | Futures | Notes |
|---|:---:|:---:|---|
| **Bitget** ⭐ | ✅ | ✅ | Strategy is optimizer-validated on Bitget data |
| Binance | ✅ | ✅ | |
| OKX | ✅ | ✅ | |
| Bybit | ✅ | ✅ | |
| KuCoin | ✅ | ✅ | |
| Kraken | ✅ | ✅ | |
| Coinbase | ✅ | — | |
| Gate.io | ✅ | ✅ | |
| MEXC | ✅ | ✅ | |

> ⭐ When switching to a different exchange, **run the Optimizer** to adjust parameters to that venue's fee structure and liquidity.

---

## 🤖 AI Features in Detail

### Decision Flow (per scan cycle)

```text
┌─────────────────────────────────────────────────────┐
│  1. SCREENER                                        │
│     Filter USDT pairs: Volume ≥ 5 M · Min. Pump     │
│     Parallel: RSI 15m/1h/4h · MACD · ATR · EMA(50)  │
│     Quality filter: Vol-Surge ≥ 1.5× · ATR 1-8%     │
├─────────────────────────────────────────────────────┤
│  2. AUTO SYMBOL SCORING                       v2.1  │
│     Volume-Surge 40% + RSI-Momentum 30%             │
│     + Historical Win-Rate (own DB) 30%              │
├─────────────────────────────────────────────────────┤
│  3. REFLECTION CONTEXT                        v2.1  │
│     ≥ 3 SLs in last 20 trades?                      │
│     → RSI pattern · Pump size · BTC correlation     │
│     → 3-5 lines of context prepended to prompt      │
├─────────────────────────────────────────────────────┤
│  4. LLM ANALYSIS (first call)                       │
│     Prompt: RSI · News · Regime · BTC · F&G         │
│     Spot:    RESULT: BUY / WAIT                     │
│     Futures: RESULT: LONG / SHORT / WAIT            │
├─────────────────────────────────────────────────────┤
│  5. BULL/BEAR CHALLENGE                       v2.1  │
│     Only on BUY/LONG/SHORT (no call on WAIT)        │
│     Second LLM call: strongest counter-arguments?   │
│     CHALLENGE: WEAK   → signal stands               │
│     CHALLENGE: STRONG → signal becomes WAIT         │
├─────────────────────────────────────────────────────┤
│  6. QUALITY & RISK FILTERS                          │
│     Confidence · Multi-TF RSI · BTC dump · F&G      │
│     Blacklist · Cooldown · Daily killswitch         │
├─────────────────────────────────────────────────────┤
│  7. ORDER EXECUTION                                 │
│     Kelly sizing · Slippage revert · Precision      │
│     Per-symbol close lock · Atomic DB write         │
└─────────────────────────────────────────────────────┘
```

### 🥊 Bull/Bear Adversarial Mode
Every positive decision (BUY/LONG/SHORT) is challenged by a second short LLM call. The **challenger** looks for concrete counter-arguments: *squeeze risk, late entry, RSI overextension, funding pressure*.
- No extra call on WAIT — saves latency
- Can be disabled via `BULL_BEAR_MODE=false` in `.env`

### 🔄 Reflection Loop
With **≥ 3 stop-losses in the last 20 trades**, the bot analyzes loss patterns (avg RSI · pump size · BTC correlation · F&G) and prepends 3–5 lines to the next prompt — **without an additional LLM call**. Refreshes every 2 h.

### 🎯 Auto Symbol Scoring

| Weight | Criterion |
|:---:|---|
| **40%** | Volume-Surge ratio |
| **30%** | RSI-Momentum score (sweet spot 45–65) |
| **30%** | Historical win-rate (own DB, 30 days) |

### 📰 News Sources (parallel)

CryptoPanic · Reddit `/r/cryptocurrency` · CoinTelegraph · CoinDesk · CryptoSlate · BeInCrypto · Decrypt · NewsBTC · Bitcoin Magazine · The Block · CoinGecko Trending

> All sources run in parallel with **per-source timeouts** — one slow source does not block the others. **5-minute cache** per symbol.

---

## 🛡️ Risk Management System

The system learns after every completed trade (active from 30 trades onward).

<table>
<tr>
<td valign="top" width="50%">

**Position sizing & filters**
- 📐 **Kelly Criterion** — optimal size from win-rate / payoff (linearly ramped: 0.1 → 1.0 over 60 trades)
- 📊 **RSI Threshold Adaptation** — Win-rate < 35 % → −3 / > 65 % → +2 (range 50–88)
- 🚫 **Coin Blacklist** — 3/5 losses = 72 h · severe = 168 h, persisted in SQLite
- 📅 **Time Analysis** — Hours with win-rate < 35 % & avg PnL < −1 USDT are blocked

</td>
<td valign="top" width="50%">

**Circuit breakers & kill-switches**
- 🛑 **Daily Loss Killswitch** — Default −50 USDT Spot / −30 USDT Futures
- 📉 **BTC Correlation Protection** — No buy on BTC dump > 2 % / 1h
- 😱 **Fear & Greed (Multi-Source)** — alternative.me → coinybubble.com → neutral 50. No buy at F&G ≥ 85.
- ⚡ **API Error Rate** — automatic pause on >30 % error rate over 1 minute
- 🔌 **Circuit Breaker** — Exponential backoff on API errors (up to 10 min.)

</td>
</tr>
</table>

---

## 🔐 Security & Privacy

> **v2.2 ships hardened.** Phase-3 review focused specifically on credential handling, file-write atomicity and cross-process correctness.

| Threat | Mitigation |
|---|---|
| **API keys in error logs** | `redact()` strips Authorization headers, API keys, Telegram/CryptoPanic tokens from every traceback before writing to `error_log.txt` |
| **`.env` injection** | Setup wizard rejects newlines, null bytes and control chars in values |
| **`.env` world-readable** | File written with `chmod 0o600` (owner-only) on POSIX |
| **Existing `.env` overwritten** | Timestamped backup created before any write |
| **CryptoPanic token in URL** | Token now sent via `params` — never appears in traceback URLs or proxy logs |
| **Telegram token in stack traces** | URL pattern `api.telegram.org/bot<TOKEN>/...` redacted |
| **Cooldown race across processes** | `portalocker` mandatory; TOCTOU-safe stale-lock takeover with PID-check |
| **Event-bus history leak** | Credential-shaped keys (`apiKey`, `secret`, `token`...) redacted in history deque |
| **Log file disk-fill** | All log files (error, Telegram overflow, structured) auto-rotate at 10 MB |

> 🔒 **No data leaves your machine.** No cloud telemetry. No anonymous usage stats. No "phone home". Your API keys live only in `.env` on your disk.

---

## 📊 Backtest & Optimizer

### 🔬 Backtester
Tests current parameters on historical Binance price data.

- **Strategy:** BALANCED / AGGRESSIVE / FUTURES
- **Period:** 7 / 14 / 30 / 60 / 90 days
- **Universe:** Same volume threshold (5 M USDT) and coin pool (60) as live — so backtest results extrapolate
- **Metrics:** Net PnL · Win-Rate · Sharpe · Sortino · Max Drawdown · Profit Factor · Best/Worst trade · Std-Dev

### 🧪 Optimizer (K-Fold Cross-Validation)
Tests 6 parameters (~20,000–40,000 combos per bot) with **4-Fold CV** — finds configs that are profitable across **all** time periods.

| Mode | Runtime | Combinations |
|---|---|---|
| **Quick** | 5–15 min. | Reduced search space |
| **Full** | 30–90 min. | Full search space |

> 🏆 Best configuration highlighted in **gold** + **sensitivity analysis** (ROBUST / AVERAGE / FRAGILE). `✓ Apply best config` writes directly to `bot_config.json`.

---

## 📈 Dashboard

`Open Dashboard` opens the Streamlit analytics in the browser.

| Tab | Content |
|---|---|
| **Overview** | Hero KPIs · Equity curve with bot markers · Drawdown chart |
| **Trades** | Filterable trade journal by outcome / coin / reason / type |
| **Positions** | Live Spot + Futures · Liquidation distance indicator for Futures |
| **Performance** | Sharpe · Sortino · Profit Factor · Expectancy · Hourly heatmap |
| **Bots** | Side-by-side comparison · Per-bot equity curves · Learning timeline |

> ⚠️ **Bind dashboard to localhost only** if running on a shared LAN. `streamlit run dashboard.py --server.address=127.0.0.1`

---

## 🏗️ Architecture

```text
                         ┌─────────────────────────┐
                         │   launcher.pyw (GUI)    │
                         │   ─────────────────     │
                         │   • init_db() (once)    │
                         │   • spawn 3 bots        │
                         │   • polling state       │
                         └────┬────────────┬───┬───┘
                              │            │   │
            ┌─────────────────┘            │   └─────────────────┐
            ▼                              ▼                     ▼
   ┌─────────────────┐           ┌─────────────────┐    ┌─────────────────┐
   │  main_bot_      │           │  main_bot_      │    │  main_bot_      │
   │  balanced.py    │           │  aggressive.py  │    │  futures.py     │
   │                 │           │                 │    │                 │
   │  • Scan loop    │           │  • Scan loop    │    │  • Scan + monitor│
   │  • Sell logic   │           │  • Sell logic   │    │  • Liq guard    │
   │  • Emergency    │           │  • Emergency    │    │  • Emergency    │
   │    close        │           │    close        │    │    close        │
   └────┬────────────┘           └────┬────────────┘    └────┬────────────┘
        │                             │                      │
        └─────────────┬───────────────┴──────────────────────┘
                      ▼
        ┌────────────────────────────────────────┐
        │  Shared modules                        │
        │  ───────────────────────────────────   │
        │  • screener.py    (multi-TF + scoring) │
        │  • risk_manager.py (Kelly + filters)   │
        │  • news_brain.py  (LLM + sources)     │
        │  • symbol_locks.py (per-symbol locks) │
        │  • cooldown_utils.py (portalocker)    │
        │  • simulation.py  (paper trading)     │
        └─────────────┬──────────────────────────┘
                      ▼
        ┌────────────────────────────────────────┐
        │  Persistence layer                     │
        │  ───────────────────────────────────   │
        │  • SQLite (WAL, 7 tables)              │
        │     ├─ trades                          │
        │     ├─ bot_open_positions              │
        │     ├─ bot_params (Kelly-tuned)        │
        │     ├─ blacklist                       │
        │     ├─ api_rate_global (cross-proc)    │
        │     └─ ...                             │
        │  • atomic JSON snapshots (state)       │
        │  • portalocker (cooldown.json)         │
        └────────────────────────────────────────┘
                      ▼
        ┌────────────────────────────────────────┐
        │  External                              │
        │  ───────────────────────────────────   │
        │  • CCXT  →  9 exchanges                │
        │  • Ollama  →  local LLM (port 11434)   │
        │  • 11 news sources (parallel)          │
        │  • Telegram (optional)                 │
        └────────────────────────────────────────┘
```

---

## 📁 Project Structure

```text
ObsidianBot/
├── launcher.pyw                  # Desktop terminal (GUI, CustomTkinter)
├── OBSIDIAN.vbs                  # Starter without CMD window
├── INSTALL.bat                   # One-click installer
│
├── main_bot_balanced.py          # BALANCED bot
├── main_bot_aggressive.py        # AGGRESSIVE bot
├── main_bot_futures.py           # FUTURES bot
│
├── screener.py                   # Multi-TF screener + composite scoring
├── news_brain.py                 # News + LLM (BALANCED)
├── news_brain_aggressive.py      # News + LLM (AGGRESSIVE)
├── news_brain_futures.py         # News + LLM (FUTURES)
├── llm_utils.py                  # Bull/Bear challenge · keyword fallback
├── risk_manager.py               # Kelly · RSI · Blacklist · Reflection
├── market_filters.py             # BTC correlation · F&G · Regime
├── database.py                   # SQLite (7 tables, WAL mode)
├── logger.py                     # ANSI logs · JSON lines · Latency · redact()
├── news_sources.py               # Central news aggregation (11 sources)
├── symbol_locks.py               # ◆ NEW v2.2 — per-symbol close locks
├── cooldown_utils.py             # portalocker-backed cooldown
├── fee_utils.py                  # Unified fee extraction
├── constants.py                  # Single source of truth for thresholds
├── state_manager.py              # Single-writer state thread
├── event_bus.py                  # Pub/sub with watchdog + redaction
│
├── backtester.py                 # Historical backtest
├── optimizer.py                  # K-Fold parameter optimizer
├── dashboard.py                  # Streamlit analytics
│
├── bot_config.json               # Live parameters (written by UI)
├── trading_bot.db                # SQLite database (auto-created)
│
├── tests/                        # 46 passing tests
│   ├── test_fee_utils.py
│   ├── test_cooldown_utils.py
│   ├── test_event_bus.py
│   ├── test_news_brain_core.py
│   ├── test_simulation.py
│   └── test_symbol_locks.py      # ◆ NEW v2.2
│
└── prompts/
    ├── balanced.txt              # Active BALANCED prompt (editable)
    ├── balanced_default.txt      # Unchanged default (reset source)
    ├── aggressive.txt
    ├── aggressive_default.txt
    ├── futures.txt
    └── futures_default.txt
```

---

## ⚙️ Parameter Reference

### Shared Parameters (all bots)

| Parameter | BALANCED | AGGRESSIVE | FUTURES | Description |
|---|:---:|:---:|:---:|---|
| Min. Pump | 2.0 % | 6.0 % | 2.0 % | Minimum 24h movement for scan |
| Activation TP | 9.0 % | 9.0 % | 4.5 % | Partial exit trigger |
| Trailing Distance | 2.0 % | 3.0 % | 2.5 % | Distance from peak price |
| Stop-Loss | −4.0 % | −6.0 % | −3.5 % | Initial stop level |
| Breakeven At | 0 (off) | 0 (off) | 2.0 % | Move SL to entry |
| Partial Sell | 30 % | 60 % | 40 % | Portion at first TP |
| RSI Max | 65 | 65 | 70 | Max RSI on 2+ timeframes |
| Position Size | 10 USDT | 10 USDT | 10 USDT | Per trade |
| Kelly Cap | 25 USDT | 25 USDT | 25 USDT | Dynamic maximum |
| Max Open Trades | 5 | 5 | 3 | Simultaneous positions |
| Scan Interval | 300 s | 150 s | 150 s | Between scans |
| SL Cooldown | 120 min | 60 min | 120 min | Lock after stop-loss |
| Daily Loss Limit | −50 USDT | −50 USDT | −30 USDT | Daily killswitch |

### FUTURES-specific Parameters

| Parameter | Default | Range | Description |
|---|:---:|:---:|---|
| Leverage | 3× | 1–10× | Isolated leverage |
| Liq Safety Buffer | 25 % | 5–50 % | Auto-close before liquidation (v2.2: raised from 15 → 25 %) |
| Monitor Interval | 20 s | 5–120 s | Liquidation check for open positions |

> ℹ️ **Why 25 % liq buffer?** The locally-computed liquidation price ignores taker fees, accumulated funding, tiered maintenance margin and the exchange-side bankruptcy buffer. A 25 % cushion absorbs that gap.

---

## 🛠️ Troubleshooting

<details>
<summary><strong>INSTALL.bat closes immediately</strong></summary>
Right-click → <em>Run as administrator</em>. Antivirus may block the downloader.
</details>

<details>
<summary><strong>"Python not found" after installation</strong></summary>
Delete the <code>python\</code> folder and run <code>INSTALL.bat</code> again.
</details>

<details>
<summary><strong>OBSIDIAN.vbs opens Notepad</strong></summary>
Right-click → <em>Open with</em> → <em>Windows Script Host</em>.
</details>

<details>
<summary><strong>Setup Wizard does not appear</strong></summary>
A <code>.env</code> file already exists. Delete it (or rename it) and restart.
</details>

<details>
<summary><strong>Connection test failed — "invalid API key"</strong></summary>
Enter key without spaces. Check trade and (for FUTURES) perpetual permissions.
</details>

<details>
<summary><strong>LLM shows "Offline" even though Ollama is running</strong></summary>
Make sure Ollama is running on <code>http://localhost:11434</code>: <code>ollama serve</code>.
</details>

<details>
<summary><strong>FUTURES bot finds 0 coins</strong></summary>
Check API key for perpetual permission. Screener auto-detects <code>BTC/USDT</code> and <code>BTC/USDT:USDT</code>.
</details>

<details>
<summary><strong>Bull/Bear Mode takes too long</strong></summary>
Set <code>BULL_BEAR_MODE=false</code> in <code>.env</code> or choose a faster model (e.g. <code>qwen2.5:7b</code>).
</details>

<details>
<summary><strong>Reflection Context does not appear</strong></summary>
Trigger: ≥ 3 stop-losses in last 20 trades + no refresh in the last 2 h. The log shows <code>⚠ REFLECTION</code> when active.
</details>

<details>
<summary><strong>"portalocker is required" on startup (v2.2+)</strong></summary>
Run <code>pip install portalocker</code> in your environment. portalocker is now mandatory for cross-process cooldown safety.
</details>

<details>
<summary><strong>Optimizer: "Exited with code 1"</strong></summary>
Check the output. If a 🏆 block is present, the run was successful.
</details>

<details>
<summary><strong>Prompt editor: "Files missing"</strong></summary>
Click the warning text → <em>Create default files now</em>. Or restart the launcher — auto-heal creates all prompt files on startup.
</details>

---

## 🗺️ Roadmap

> *What's coming next.* Open to feedback — message me on Telegram if you'd like a feature prioritized.

| Status | Item |
|:---:|---|
| ✅ Done | Phase 3 hardening (60+ fixes, 46 tests) |
| ✅ Done | Cross-process API rate limiting |
| ✅ Done | Per-symbol close locks |
| ✅ Done | Backtest = live universe alignment |
| 🔄 Planned | BaseBot migration (eliminate 80% code duplication across 3 bots) |
| 🔄 Planned | order_engine.py wire-in (centralize idempotency + slippage) |
| 🔄 Planned | Test coverage for main_bot_*.py |
| 💡 Considering | Multi-exchange parallel execution |
| 💡 Considering | Web-based dashboard auth |
| 💡 Considering | Strategy hot-reload (no bot restart on config change) |

---

## ⚠️ Disclaimer

> **Crypto trading involves significant capital risk.**
> Futures trading is leveraged — losses are amplified just as much as gains.
> At 10× leverage, a price movement of ~9.5 % can lead to liquidation.
> The liquidation safety buffer closes positions automatically beforehand, but does **not** eliminate the risk.
>
> Past backtest performance does not guarantee future results.
>
> **Always start in simulation mode.** Never invest more than you can afford to lose.
>
> *Use at your own risk.*

---

## 💬 Contact & Support

Questions, feedback, bug reports or just interested in the project?
**Message me directly on Telegram:**

<div align="center">

[![Telegram](https://img.shields.io/badge/▶_Chat_on_Telegram-@Padudu0815-26A5E4?style=for-the-badge&logo=telegram&logoColor=white&labelColor=0a0a0f)](https://t.me/Padudu0815)

**[t.me/Padudu0815](https://t.me/Padudu0815)**

</div>

---

## ⚖️ Liability Disclaimer & Copyright

**Copyright © 2026 Obsidian Trading Terminal. All rights reserved.**

Crypto trading involves significant risks. Use of this software is at your own risk.
The author accepts no liability for financial losses.
Any modification of the code or removal of copyright notices is strictly prohibited.

---

<div align="center">

<br/>

**Built with ◆ Obsidian**

`Python` · `CustomTkinter` · `Ollama` · `SQLite` · `CCXT` · `Streamlit` · `portalocker`

<br/>

*Three bots. One terminal. Fully local.*

<br/>

◆

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,50:1a0b2e,100:0a0a0f&height=100&section=footer" alt="footer"/>

</div>
