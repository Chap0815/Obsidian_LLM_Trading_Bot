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
  <a href="#-whats-new-in-30"><img src="https://img.shields.io/badge/Version-3.0-8B5CF6?style=for-the-badge&labelColor=0a0a0f" alt="Version"/></a>
  <a href="#-private-project--how-to-get-access"><img src="https://img.shields.io/badge/Status-Private-ef4444?style=for-the-badge&labelColor=0a0a0f" alt="Private"/></a>
  <a href="https://python.org"><img src="https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=0a0a0f" alt="Python"/></a>
  <a href="https://ollama.ai"><img src="https://img.shields.io/badge/LLM-Ollama-FF6B6B?style=for-the-badge&logo=ollama&logoColor=white&labelColor=0a0a0f" alt="LLM"/></a>
  <a href="https://t.me/Padudu0815"><img src="https://img.shields.io/badge/Telegram-@Padudu0815-26A5E4?style=for-the-badge&logo=telegram&logoColor=white&labelColor=0a0a0f" alt="Telegram"/></a>
</p>

<!-- ───── SECONDARY BADGES ───── -->
<p>
  <img src="https://img.shields.io/badge/Phase%203-Hardened-22c55e?style=flat-square&labelColor=0a0a0f" alt="Hardened"/>
  <img src="https://img.shields.io/badge/v3.0-43%2B%20bugs%20fixed-22c55e?style=flat-square&labelColor=0a0a0f" alt="v3.0 fixes"/>
  <img src="https://img.shields.io/badge/Architecture-Modular-8B5CF6?style=flat-square&labelColor=0a0a0f" alt="Modular"/>
  <img src="https://img.shields.io/badge/Windows-blue?style=flat-square&logo=windows&logoColor=white&labelColor=0a0a0f" alt="Windows"/>
  <img src="https://img.shields.io/badge/Linux-yellow?style=flat-square&logo=linux&logoColor=white&labelColor=0a0a0f" alt="Linux"/>
  <img src="https://img.shields.io/badge/100%25-Local-22c55e?style=flat-square&labelColor=0a0a0f" alt="Local"/>
</p>

<br/>

<!-- ───── BOT BADGES ───── -->
<kbd>&nbsp;🤖&nbsp;&nbsp;<b>BALANCED</b>&nbsp;</kbd> &nbsp; <kbd>&nbsp;⚡&nbsp;&nbsp;<b>AGGRESSIVE</b>&nbsp;</kbd> &nbsp; <kbd>&nbsp;📈&nbsp;&nbsp;<b>FUTURES</b>&nbsp;</kbd>

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--           PRIVATE PROJECT NOTICE — TOP OF PAGE                  -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🔒 Private Project — How to Get Access

> **As of version 2.0, Obsidian is a closed-source private project.** The repository no longer hosts the trading engine, slim bot subclasses, or the v3.0 launcher.
>
> If you're interested in running Obsidian on your own machine, **reach out directly on Telegram**. Access is granted case-by-case after a short conversation about your setup, goals, and risk awareness.

<div align="center">

<br/>

[![Telegram](https://img.shields.io/badge/▶_Request_Access_via_Telegram-@Padudu0815-26A5E4?style=for-the-badge&logo=telegram&logoColor=white&labelColor=0a0a0f)](https://t.me/Padudu0815)

**[t.me/Padudu0815](https://t.me/Padudu0815)**

<br/>

</div>

> ℹ️ **What's still public:** this README, the architecture overview, the changelog, and the security/risk-management documentation. Everything below is current and accurate for v3.0 — if you're considering reaching out, this is the right page to read first.

---

## ⚡ What is Obsidian?

> **Obsidian** is a complete trading terminal that runs **three specialized bots in parallel** inside one native desktop window. Every trading decision is made by a **locally running language model** (Ollama / DeepSeek-R1 / Qwen / Mistral) — **no external AI service, no API key, no cloud subscription, no telemetry.**

What makes it different from the dozens of other "AI trading bots" on GitHub:

- **No subscription, no SaaS.** It runs on your hardware. The LLM runs on your hardware. Your API keys never leave your disk.
- **Three strategies, one terminal.** BALANCED, AGGRESSIVE and FUTURES (Long/Short perpetuals) run as independent subprocesses with a shared launcher UI.
- **Real risk management.** Kelly sizing, daily loss kill-switches, per-symbol close locks, cross-process API rate limiting, slippage circuit-breakers, liquidation buffers.
- **Production-hardened.** v3.0 ships **43+ critical audit fixes** plus a deep Futures audit (8 additional bugs found and fixed) — see [What's New](#-whats-new-in-30).

<div align="center">

<table width="100%">
<tr>
<td align="left"><sub><b>◆ &nbsp; OBSIDIAN TRADING TERMINAL</b></sub></td>
<td align="right"><sub><code>v 3.0</code> &nbsp; <code>● LIVE</code></sub></td>
</tr>
</table>

<img width="2194" height="1195" alt="Obsidian Trading Terminal v3.0 — Dashboard"
     src="https://github.com/user-attachments/assets/2c222b2a-2ae5-4555-b2e9-71f9a169c987" />

</div>

---

## 📐 At a Glance

<div align="center">

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

</div>

---

## 🆕 What's New in 3.0

> **Phase 3 — Modular Architecture + Deep Audit.** The 6,635-line monolithic launcher was rewritten into a clean, testable package. A systematic deep-audit found **43 bugs across the bot core**, plus **8 additional Futures-specific bugs** missed by previous reviews. This release ships every one of them as a targeted fix.

<table>
<tr>
<td valign="top" width="33%">

### 🏗️ Modular launcher rewrite
- **6,635-line monolith → modular package** (`launcher/config`, `launcher/core`, `launcher/state`, `launcher/ui`, `launcher/ui/dialogs`)
- **Slim bot subclasses** (~100 lines each) on top of `core/spot_bot.py` and `core/futures_bot.py` base classes
- **17 dedicated modules** in `bot_utils/` — every concern (state persistence, order placement, funding, circuit-breakers) lives in its own file
- **Easier to test, easier to extend, easier to audit**

</td>
<td valign="top" width="33%">

### 🔴 Money-loss risks closed
- **Spot shutdown deadline-thread** — bot can no longer hang forever on a stalled exchange API
- **BotProcess lifecycle lock** — double-clicking the start button can no longer spawn two parallel subprocesses
- **Per-symbol close locks** prevent double-sells between shutdown handler and main loop
- **Slippage circuit-breaker** with per-instance state (no more cross-bot contamination)
- **`atomic_save_json`** uses unique tmp filenames per pid+thread — no more lost writes when launcher and bot race for the same file

</td>
<td valign="top" width="33%">

### 🛡️ Futures hardening (NEW)
- **Reconcile safety-gate** — if the exchange API briefly returns an empty list, the bot **refuses** to wipe all local positions (previously a silent disaster scenario)
- **`verify_position_closed`** is now pessimistic — won't return "closed" on API uncertainty (no more ghost positions)
- **Funding correctly scaled** for partial-sold positions during emergency close (no more double-counted funding)
- **Entry-price validation** before opening any position — no more orphan positions from price=0 glitches
- **Orphan detection** — if order placed but filled=0 returned, loud warning + struct log for manual reconciliation

</td>
</tr>
</table>

<table>
<tr>
<td valign="top" width="33%">

### 🔒 Security & correctness
- **SQL injection whitelist** — DB migrations validate every identifier and DDL fragment against a strict regex
- **clientOrderId via UUID** — replaces millisecond timestamps that could collide between bots
- **Funding-rate epsilon comparison** — tiny non-zero rates (1e-13) no longer slip through `== 0.0` checks
- **UTC everywhere** — `buy_time` / `sell_time` / order timestamps use UTC across all 5 writers (no more cross-midnight trade attribution bugs)
- **`safe_float` helpers** for defensive numeric coercion against `None` / `NaN` / `Infinity`

</td>
<td valign="top" width="33%">

### 📊 Observability
- **`silent_log`** rate-limited stderr writer — the ~140 historical `except Exception: pass` sites now have a non-spammy escape hatch
- **Poller error visibility** — UI poller no longer swallows every exception silently; errors surface once per minute per type
- **Telegram failure counter** — after 5 consecutive failed sends, the bot escalates to a prominent log warning (no more silently-disabled alerts)
- **Log-struct queue overflow** — dropped events are counted and reported every 30s instead of silently lost

</td>
<td valign="top" width="33%">

### ⚙️ Reliability boosts
- **Spot bots now respect `budget_exhausted()`** — previously only futures did, so spots could burn the shared API quota and IP-ban all three bots
- **SafeMode persistence** — alert-sent flag now survives bot restart (no more Telegram spam on same-day restart)
- **`add_if_absent`** atomic TradeState insertion — closes the TOCTOU window between `state.has(sym)` and `state.add(sym, ...)`
- **Spot monitor writes `last_price`** every tick — killswitch now sees accurate unrealized PnL and triggers on time
- **Restart polling** instead of blind 800ms delay — restart waits for the old process to actually die before launching the new one

</td>
</tr>
</table>

<details>
<summary><b>📋 Full v3.0 audit changelog — 43 + 8 fixes</b> (click to expand)</summary>

<br/>

**Critical fixes (K-series, 8 bugs):**

| ID | Area | Fix |
|----|------|-----|
| K-1 | Shutdown | Spot bot now uses deadline-thread for emergency close (was blocking forever on API stall) |
| K-2 | Concurrency | `BotProcess._lifecycle_lock` prevents doubled subprocesses from rapid start clicks |
| K-3 | Order placement | `_place_buy_order` validates `r["price"] > 0` before division |
| K-4 | Risk override | BTC-stress override defensive against API failures (no more force-BE on API glitch) + batched ticker fetch |
| K-5 | Persistence | `atomic_save_json` uses `{path}.tmp.{pid}.{tid}` to prevent cross-process tmp collision |
| K-6 | Restart | Polls until old process is actually dead before starting new one |
| K-7 | SQL safety | DB-migration identifiers + DDL whitelist-validated against strict regex |
| K-8 | Math | Funding-rate uses epsilon comparison (`< 1e-9`) instead of `== 0.0` |

**High-severity fixes (H-series, 15 bugs):**

| ID | Area | Fix |
|----|------|-----|
| H-1 | Observability | Poller stderr rate-limit (60s / error-type) — silent failures now visible |
| H-2 | Threading | Poller `get_all()` deep-copies nested dicts (RuntimeError "dict changed" eliminated) |
| H-3 | Rate-limiting | Spot bots now check `budget_exhausted()` — was futures-only before |
| H-4 | Observability | `silent_log` helper for the ~140 historical silent excepts; critical paths patched first |
| H-5 | Concurrency | `TradeState.add_if_absent` atomic insertion closes TOCTOU window |
| H-6 | Alerts | SafeMode `alert_sent` persisted across restarts (no Telegram spam on restart) |
| H-8 | Performance | BTC override uses batch `fetch_tickers` instead of N single-ticker calls |
| H-9 | Order placement | `extract_fill_price > 0` validation — orphan position detection |
| H-10 | Logging | `log_struct` queue overflow tracked with rate-limited drop counter |
| H-11 | Risk | Spot monitor writes `last_price` every tick (killswitch now sees real PnL) |
| H-12 | Order placement | `clientOrderId` uses UUID instead of `int(time.time()*1000)` (no collisions) |
| H-13 | UI | Launcher position reader skips entries with `state="CLOSED"` |
| H-14 | UI | Launcher skips corrupted entries with `buy_price <= 0` |
| H-15 | Restart | 500ms × 120 retry polling instead of 800ms blind delay |

**Medium fixes (M-series, 6 fixed of 10 — others verified N/A):**

| ID | Area | Fix |
|----|------|-----|
| M-1 | Architecture | SafeMode slippage observations moved from module globals to per-instance |
| M-2 | Lifecycle | `register_console_logger` / `register_structured_logger` idempotent |
| M-3 | Defensive | `safe_float` / `safe_int` / `safe_dict_float` helpers in `bot_utils/safe_numeric.py` |
| M-4 | Correctness | UTC timestamps for `buy_time` / `sell_time` across all 5 writers |
| M-5 | Shutdown | `_emergency_closed` idempotency flag prevents double-run (SIGINT + atexit) |
| M-7 | Shutdown | Poller uses `Event.wait()` for cancellable sleep |

**Polish items (N-series, 6 fixed of 10):**

| ID | Area | Fix |
|----|------|-----|
| N-1 | Config | `API_BUDGET_PER_MINUTE` configurable via env var |
| N-2 | Constants | `SHUTDOWN_DEADLINE_SEC` is a class attribute (folded into K-1) |
| N-3 | Config | `STATE_PERSIST_RETRIES` + `STATE_PERSIST_RETRY_SLEEP` env-configurable |
| N-4 | Readability | Killswitch decomposed into `_compute_today_pnl()` + `_should_kill()` |
| N-5 | Hygiene | `print()` replaced with `silent_log` / `stderr` in launcher core |
| N-10 | Alerts | Telegram failure counter — escalates to prominent log warning after 5× in a row |

**Deep Futures Audit (F-series — 8 additional bugs found AFTER the K/H/M/N fixes):**

| ID | Severity | Fix |
|----|----------|-----|
| F-1 | KRITISCH | Futures entry validates `entry_price > 0` + orphan-position detection on `filled=0` |
| F-2 | HOCH | Futures SIM mode skips when computed amount = 0 |
| F-3 | HOCH | `_evaluate_futures_exit` now receives `sym` explicitly — previous `d.get("symbol", "")` always returned empty string, silently failing the `initial_liq_distance` heal-write |
| F-4 | MED | UTC timestamps in 2 more sites in `futures_bot_exits.py` |
| F-5 | KRITISCH | **Periodic reconcile now refuses to wipe local state** when exchange API returns an empty list (auth/network glitch protection) |
| F-6 | MED | UTC timestamps in `futures_order.py` with lazy import to avoid circular dependency |
| F-7 | HOCH | `emergency_close_all_futures` scales funding by `remaining_ratio` for partial-sold positions — prevents double-counting |
| F-8 | KRITISCH | `verify_position_closed` returns `(False, -1.0)` instead of `(True, 0.0)` when API can't verify — no more ghost positions from API uncertainty |

</details>

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
| **Graceful Shutdown** | SIGTERM → per-symbol close locks → close positions → deadline-thread → persist DB → exit |
| **State Reconciliation** | On startup: reconcile local state vs. real exchange balance · **periodic reconcile refuses to wipe state on API glitches (v3.0)** |
| **Atomic File Writes** | tmp + fsync + os.replace — **unique tmp filenames prevent cross-process collision (v3.0)** |
| **SQLite WAL-Mode** | 7 tables · read queries never block writing bots |
| **Cross-Process Locks** | `portalocker` for cooldown · advisory locks for migrations · **SQL identifier whitelist (v3.0)** |
| **Circuit Breaker** | Exponential backoff on API errors (up to 10 min.) |
| **Telegram** | Buy/sell notifications with proxy support · **failure counter escalates after 5 consecutive failures (v3.0)** |
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

## 🤖 AI Features in Detail

### Decision Flow (per scan cycle)

```text
┌─────────────────────────────────────────────────────┐
│  1. SCREENER                                        │
│     Filter USDT pairs: Volume ≥ 5 M · Min. Pump     │
│     Parallel: RSI 15m/1h/4h · MACD · ATR · EMA(50)  │
│     Quality filter: Vol-Surge ≥ 1.5× · ATR 1-8%     │
├─────────────────────────────────────────────────────┤
│  2. AUTO SYMBOL SCORING                             │
│     Volume-Surge 40% + RSI-Momentum 30%             │
│     + Historical Win-Rate (own DB) 30%              │
├─────────────────────────────────────────────────────┤
│  3. REFLECTION CONTEXT                              │
│     ≥ 3 SLs in last 20 trades?                      │
│     → RSI pattern · Pump size · BTC correlation     │
│     → 3-5 lines of context prepended to prompt      │
├─────────────────────────────────────────────────────┤
│  4. LLM ANALYSIS (first call)                       │
│     Prompt: RSI · News · Regime · BTC · F&G         │
│     Spot:    RESULT: BUY / WAIT                     │
│     Futures: RESULT: LONG / SHORT / WAIT            │
├─────────────────────────────────────────────────────┤
│  5. BULL/BEAR CHALLENGE                             │
│     Only on BUY/LONG/SHORT (no call on WAIT)        │
│     Second LLM call: strongest counter-arguments?   │
│     CHALLENGE: WEAK   → signal stands               │
│     CHALLENGE: STRONG → signal becomes WAIT         │
├─────────────────────────────────────────────────────┤
│  6. QUALITY & RISK FILTERS                          │
│     Confidence · Multi-TF RSI · BTC dump · F&G      │
│     Blacklist · Cooldown · Daily killswitch         │
│     ► API budget check ← NEW in v3.0 for spot       │
├─────────────────────────────────────────────────────┤
│  7. ORDER EXECUTION                                 │
│     Kelly sizing · Slippage revert · Precision      │
│     UUID clientOrderId · Atomic DB write            │
│     ► Orphan detection on filled=0 ← NEW in v3.0    │
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
- 🛑 **Daily Loss Killswitch** — Default −50 USDT Spot / −30 USDT Futures · **uses real `last_price` (v3.0)**
- 📉 **BTC Correlation Protection** — No buy on BTC dump > 2 % / 1h · **defensive against API gaps (v3.0)**
- 😱 **Fear & Greed (Multi-Source)** — alternative.me → coinybubble.com → neutral 50. No buy at F&G ≥ 85
- ⚡ **API Error Rate** — automatic pause on >30 % error rate over 1 minute
- 🔌 **Circuit Breaker** — Exponential backoff on API errors (up to 10 min.)
- 🆕 **SafeMode persistence** — daily-loss alert state survives restart (no Telegram spam)

</td>
</tr>
</table>

---

## 🔐 Security & Privacy

> **v3.0 builds on v2.2's hardening with an additional 8 Futures-specific fixes and SQL identifier validation.**

| Threat | Mitigation |
|---|---|
| **API keys in error logs** | `redact()` strips Authorization headers, API keys, Telegram/CryptoPanic tokens from every traceback before writing to `error_log.txt` |
| **SQL injection in migrations** | **NEW v3.0:** every table/column name + DDL fragment whitelist-validated against strict regex |
| **`.env` injection** | Setup wizard rejects newlines, null bytes and control chars in values |
| **`.env` world-readable** | File written with `chmod 0o600` (owner-only) on POSIX |
| **Existing `.env` overwritten** | Timestamped backup created before any write |
| **CryptoPanic token in URL** | Token sent via `params` — never appears in traceback URLs or proxy logs |
| **Telegram token in stack traces** | URL pattern `api.telegram.org/bot<TOKEN>/...` redacted |
| **Cooldown race across processes** | `portalocker` mandatory; TOCTOU-safe stale-lock takeover with PID-check |
| **Event-bus history leak** | Credential-shaped keys (`apiKey`, `secret`, `token`...) redacted in history deque |
| **Log file disk-fill** | All log files (error, Telegram overflow, structured) auto-rotate at 10 MB |
| **Cross-process state collision** | **NEW v3.0:** `atomic_save_json` uses pid+tid-unique tmp filenames |
| **Reconcile wipes state on API glitch** | **NEW v3.0:** Futures reconcile refuses to remove local positions when exchange returns empty list |

> 🔒 **No data leaves your machine.** No cloud telemetry. No anonymous usage stats. No "phone home". Your API keys live only in `.env` on your disk.

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

## 🏗️ Architecture (v3.0 — Modular)

```text
                         ┌─────────────────────────┐
                         │   launcher.pyw (22 LoC) │
                         │      bootstrap only     │
                         └────────────┬────────────┘
                                      ▼
                         ┌─────────────────────────┐
                         │   launcher/             │  ← NEW v3.0
                         │   ───────────────       │     modular package
                         │   • config/settings.py  │
                         │   • core/               │
                         │     ├ process_manager   │
                         │     ├ metrics_service   │
                         │     ├ positions         │
                         │     └ bot_controller    │
                         │   • state/poller.py     │
                         │   • ui/                 │
                         │     ├ app.py            │
                         │     ├ logging_panel.py  │
                         │     ├ components/       │
                         │     └ dialogs/          │
                         └────┬────────────┬───┬───┘
                              │            │   │
            ┌─────────────────┘            │   └─────────────────┐
            ▼                              ▼                     ▼
   ┌─────────────────┐           ┌─────────────────┐    ┌─────────────────┐
   │  bots/          │           │  bots/          │    │  bots/          │
   │  main_bot_      │           │  main_bot_      │    │  main_bot_      │
   │  balanced.py    │           │  aggressive.py  │    │  futures.py     │
   │  (slim ~100 LoC)│           │  (slim ~100 LoC)│    │  (slim ~100 LoC)│
   └────┬────────────┘           └────┬────────────┘    └────┬────────────┘
        │                             │                      │
        └─────────────┬───────────────┴──────────────────────┘
                      ▼
   ┌──────────────────────────────────────────────────────────────────┐
   │  core/  (V2 base classes)                                        │
   │  ──────────────────────────────────────────────────────────      │
   │  • spot_bot.py + spot_bot_{scan,exits,reconcile}.py              │
   │  • futures_bot.py + futures_bot_{scan,exits,reconcile}.py        │
   │  • state_manager.py · database.py · logger.py                    │
   │  • symbol_locks.py · event_bus.py · models.py                    │
   └────────────────────────────────┬─────────────────────────────────┘
                                    ▼
   ┌──────────────────────────────────────────────────────────────────┐
   │  bot_utils/  (17 dedicated modules)                              │
   │  ──────────────────────────────────────────────────────────      │
   │  • trade_state.py · state_persist.py · circuit_breaker.py        │
   │  • api_budget.py · balance.py · order_utils.py                   │
   │  • spot_exits.py                                                 │
   │  • futures_order.py · futures_math.py · futures_funding.py       │
   │  • futures_exits.py · ticker_cache.py                            │
   │  • safe_numeric.py · silent_log.py     ← NEW v3.0                │
   └────────────────────────────────┬─────────────────────────────────┘
                                    ▼
   ┌──────────────────────────────────────────────────────────────────┐
   │  Persistence layer                                               │
   │  ──────────────────────────────────────────────────────────      │
   │  • SQLite (WAL, 7 tables + identifier whitelist v3.0)            │
   │  • Atomic JSON snapshots (pid+tid-unique tmp v3.0)               │
   │  • portalocker (cooldown.json)                                   │
   └────────────────────────────────┬─────────────────────────────────┘
                                    ▼
   ┌──────────────────────────────────────────────────────────────────┐
   │  External                                                        │
   │  ──────────────────────────────────────────────────────────      │
   │  • CCXT  →  9 exchanges                                          │
   │  • Ollama  →  local LLM (port 11434)                             │
   │  • 11 news sources (parallel)                                    │
   │  • Telegram (optional, with failure escalation v3.0)             │
   └──────────────────────────────────────────────────────────────────┘
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
| Liq Safety Buffer | 25 % | 5–50 % | Auto-close before liquidation |
| Monitor Interval | 20 s | 5–120 s | Liquidation check for open positions |
| Shutdown Deadline | 45 s | env | Hard deadline for emergency close (v3.0) |

> ℹ️ **Why 25 % liq buffer?** The locally-computed liquidation price ignores taker fees, accumulated funding, tiered maintenance margin and the exchange-side bankruptcy buffer. A 25 % cushion absorbs that gap.

### Environment Variables (v3.0)

| Variable | Default | Description |
|---|:---:|---|
| `API_BUDGET_PER_MINUTE` | 300 | Cross-bot API call budget per 60s window |
| `STATE_PERSIST_RETRIES` | 8 | Windows: how many times to retry `os.replace` on PermissionError |
| `STATE_PERSIST_RETRY_SLEEP` | 0.05 | Sleep between retries (s) |
| `BULL_BEAR_MODE` | true | Enable adversarial LLM challenge on BUY/LONG/SHORT signals |

---

## 🗺️ Roadmap

> *What's coming next.* If you're an Obsidian user with a feature request, ping me on Telegram.

| Status | Item |
|:---:|---|
| ✅ Done (v2.2) | Phase 3 hardening (60+ fixes, 46 tests) |
| ✅ Done (v2.2) | Cross-process API rate limiting |
| ✅ Done (v2.2) | Per-symbol close locks |
| ✅ Done (v2.2) | Backtest = live universe alignment |
| ✅ Done (v3.0) | Modular launcher package (`launcher/` split into config/core/state/ui) |
| ✅ Done (v3.0) | Slim bot subclasses on V2 base classes |
| ✅ Done (v3.0) | Deep audit: 43 K/H/M/N fixes + 8 Futures-specific fixes |
| ✅ Done (v3.0) | SafeMode persistence, atomic_save_json cross-process safety |
| ✅ Done (v3.0) | Reconcile safety-gate against API empty-list glitches |
| 🔄 Planned | order_engine.py wire-in (centralize idempotency + slippage) |
| 🔄 Planned | Test coverage expansion for core/spot_bot.py + core/futures_bot.py |
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

## 💬 Get Access — Contact

<div align="center">

<br/>

**Obsidian is a private project.**
**No public download. No public installer. No support tickets.**

If the feature set above sounds like what you've been looking for —
reach out directly and let's talk.

<br/>

[![Telegram](https://img.shields.io/badge/▶_Request_Access_via_Telegram-@Padudu0815-26A5E4?style=for-the-badge&logo=telegram&logoColor=white&labelColor=0a0a0f)](https://t.me/Padudu0815)

**[t.me/Padudu0815](https://t.me/Padudu0815)**

<br/>

</div>

---

## ⚖️ Liability Disclaimer & Copyright

**Copyright © 2026 Obsidian Trading Terminal. All rights reserved.**

This project is closed-source as of version 2.0. No part of the source code, configuration files, prompts, documentation or branding may be copied, redistributed, modified, sold, sublicensed or used as the basis for derivative works without prior written permission from the author.

Crypto trading involves significant risks. Use of this software is at your own risk.
The author accepts no liability for financial losses.

---

<div align="center">

<br/>

**Built with ◆ Obsidian**

`Python` · `CustomTkinter` · `Ollama` · `SQLite` · `CCXT` · `Streamlit` · `portalocker`

<br/>

*Three bots. One terminal. Fully local. Production-hardened.*

<br/>

◆

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,50:1a0b2e,100:0a0a0f&height=100&section=footer" alt="footer"/>

</div>
