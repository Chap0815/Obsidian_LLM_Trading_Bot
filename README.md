<div align="center">

```
◆  O B S I D I A N  T R A D I N G  T E R M I N A L
```

# Obsidian Trading Terminal

**Drei KI-Bots · Ein Desktop-Terminal · Vollständig lokal · Keine Cloud**

[![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D6?style=flat-square&logo=windows&logoColor=white)](https://microsoft.com/windows)
[![LLM](https://img.shields.io/badge/LLM-Ollama%20%2F%20DeepSeek--R1-111827?style=flat-square)](https://ollama.ai)
[![Exchange](https://img.shields.io/badge/Exchange-Bitget%20%26%208%20more-00D4AA?style=flat-square)](https://bitget.com)
[![License](https://img.shields.io/badge/License-MIT-8b5cf6?style=flat-square)](LICENSE)
[![Version](https://img.shields.io/badge/Version-v2.1.0-10b981?style=flat-square)]()

*Automatisiertes Krypto-Trading mit lokaler KI — kein API-Key für KI, keine Cloud-Abhängigkeit, keine versteckten Kosten.*

</div>

---

## Inhaltsverzeichnis

- [Was ist Obsidian?](#was-ist-obsidian)
- [Features im Überblick](#features-im-überblick)
- [Die drei Strategien](#die-drei-strategien)
- [Schnellinstallation](#schnellinstallation)
- [Voraussetzungen](#voraussetzungen)
- [Schritt-für-Schritt Installation](#schritt-für-schritt-installation)
- [LLM einrichten (Ollama)](#llm-einrichten-ollama)
- [Unterstützte Exchanges](#unterstützte-exchanges)
- [KI-Features im Detail](#ki-features-im-detail)
- [Risikomanagementsystem](#risikomanagementsystem)
- [Backtest & Optimizer](#backtest--optimizer)
- [Dashboard](#dashboard)
- [Parameter-Referenz](#parameter-referenz)
- [Troubleshooting](#troubleshooting)
- [Disclaimer](#disclaimer)

---

## Was ist Obsidian?

Obsidian ist ein vollständiges Trading-Terminal für drei unabhängige Bots in einem einzigen nativen Desktop-Fenster. Alle Handelsentscheidungen trifft ein **lokal laufendes Sprachmodell** (Ollama / DeepSeek-R1) — kein externer KI-Dienst, kein API-Key, kein Cloud-Abo.

```
┌─────────────────────────────────────────────────────────────────────────┐
│ ◆ OBSIDIAN  [🤖 Balanced] [⚡ Aggressive] [📈 Futures]   [Dashboard]   │
├──────────────┬────────────────────┬────────────────────┬────────────────┤
│ MARKET       │ 🤖 BALANCED        │ ⚡ AGGRESSIVE       │ 📈 FUTURES     │
│ Phase: BULL  │ Spot · Risk-Aware  │ Spot · Momentum    │ Long / Short   │
│ BTC: +2.3%   │                    │                    │                │
│ F&G:  61     │ REALIZED  +18.45 $ │ REALIZED  +31.20 $ │ REALIZED +12.80│
│              │ UNREALIZED +1.23 $ │ UNREALIZED +3.45 $ │ UNREAL −0.80 $ │
│ PERFORMANCE  │                    │                    │                │
│ +62.45 USDT  │ [▶ Start]          │ [▶ Start]          │ [▶ Start]      │
│ today: +8.10 │ [↻ Restart]        │ [↻ Restart]        │ [↻ Restart]    │
│              │ [■ Stop]           │ [■ Stop]           │ [■ Stop]       │
│ SYSTEM       │                    │                    │                │
│ CPU  ██  23% │ Activity Log       │ Activity Log       │ Activity Log   │
│ RAM  ███ 61% │ 14:32:01 · ⓘ INFO │ 14:32:05 · ⓘ INFO │ ...            │
│ GPU  █   12% │ Analyzing BTC ...  │ Analyzing ETH ...  │                │
└──────────────┴────────────────────┴────────────────────┴────────────────┘
```

---

## Features im Überblick

### Kern

| Feature | Beschreibung |
|---|---|
| **3 unabhängige Bots** | BALANCED (Spot), AGGRESSIVE (Spot), FUTURES (Perpetuals Long/Short) |
| **Lokales LLM** | Ollama — DeepSeek-R1, Qwen, Mistral, Llama — kein Cloud-Abo |
| **Bull/Bear Adversarial Mode** | Zweiter LLM-Call hinterfragt jede Kaufentscheidung kritisch |
| **Reflection Loop** | Verlust-Musteranalyse injiziert Lern-Kontext in den nächsten Prompt |
| **Auto Symbol Scoring** | Kandidaten nach Vol-Surge, RSI-Momentum und historischer Win-Rate ranked |
| **Multi-Source News** | 11 Quellen parallel: CryptoPanic · Reddit · 8 RSS-Feeds · CoinGecko |
| **Editierbare KI-Prompts** | Per-Bot-Prompt live editierbar direkt im Terminal, mit Validierung |
| **LLM-Fallback** | Bei Ollama-Ausfall: keyword-basierter Filter läuft automatisch weiter |
| **SIM/LIVE Toggle** | Jeder Bot unabhängig umschaltbar mit Bestätigungsdialog |
| **Unrealized PnL Live** | Echtzeit-Anzeige offener Positionen pro Bot und als Gesamtsumme |

### Tools & Analytics

| Feature | Beschreibung |
|---|---|
| **K-Fold Optimizer** | 30.000+ Parameterkombinationen · 4-Fold Cross-Validation · Robustheitsscore |
| **Backtester** | Historische Binance-Daten · echte Fee-Modellierung · Live-Output |
| **Streamlit Dashboard** | 5 Tabs: KPIs · Equity-Curve · Positions · Sharpe/Sortino · Bot-Vergleich |
| **Win/Loss Heatmap** | Win-Rate nach Stunde × Wochentag — 30-Tage-Fenster |
| **Emergency Close** | Futures: alle Positionen sofort mit `reduceOnly`-Orders schließen |

### Robustheit & Datenschutz

| Feature | Beschreibung |
|---|---|
| **Graceful Shutdown** | SIGTERM → Positionen schließen → DB persistieren → Exit |
| **State Reconciliation** | Beim Start: lokaler State vs. echte Exchange-Balance abgleichen |
| **Atomic File Writes** | tmp + fsync + os.replace — korrupte Dateien bei Absturz unmöglich |
| **SQLite WAL-Mode** | 7 Tabellen · Lese-Abfragen blockieren nie schreibende Bots |
| **Circuit Breaker** | Exponentieller Backoff bei API-Fehlern (bis 10 Min.) |
| **Telegram** | Kauf/Verkauf-Benachrichtigungen mit Proxy-Support |
| **100 % lokal** | Keine Daten verlassen deinen Rechner |

---

## Die drei Strategien

### 🤖 BALANCED — Spot · Risk-Aware

Optimizer-validiert (60 Tage · 30.240 Kombinationen · K-Fold 4). Kauft früh im Momentum, lässt Gewinner laufen. Konservative Stops, 30% Partial-Exit.

```
Min. Pump  2.0%    Activation TP  9.0%    Trailing     2.0%
Stop-Loss −4.0%    Partial Sell  30%     Max Trades      5
Scan       300s    RSI Max        65     Daily Limit   −50$
```

### ⚡ AGGRESSIVE — Spot · Momentum

Höhere Einstiegsschwelle fängt nur starke Ausbrüche. 60% Partial-Exit sichert früh Gewinne. Schnellerer Scan-Zyklus.

```
Min. Pump  6.0%    Activation TP  9.0%    Trailing     3.0%
Stop-Loss −6.0%    Partial Sell  60%     Max Trades      5
Scan       150s    RSI Max        65     Daily Limit   −50$
```

### 📈 FUTURES — Perpetuals · Long/Short

Das LLM entscheidet Richtung (LONG / SHORT / WAIT). Break-Even-Trigger, Liq-Safety-Buffer, separater Monitor-Loop alle 20 Sekunden.

```
Min. Pump  2.0%    Activation TP  4.5%    Trailing     2.5%
Stop-Loss −3.5%    Leverage        3×     Liq Buffer    15%
Max Trades   3     Break-Even     2.0%    Daily Limit   −30$
```

---

## Schnellinstallation

```batch
1.  ZIP herunterladen und entpacken (empfohlen: C:\ObsidianBot\)
2.  INSTALL.bat doppelklicken
3.  Warten bis "Setup Complete!" erscheint  (2–5 Minuten)
4.  OBSIDIAN.vbs doppelklicken → Setup-Wizard → fertig
```

> **Kein Python nötig.** Das Installer-Skript lädt Python 3.13 Embedded (~30 MB) automatisch herunter.

---

## Voraussetzungen

**Pflicht:**
- Windows 10 / 11 (64-bit) — Linux mit Python 3.11+ funktioniert ebenfalls
- Internetverbindung für die Erstinstallation
- Exchange-Account mit API-Key (Trade-Berechtigung)

**Optional aber empfohlen:**
- [Ollama](https://ollama.ai) für KI-Entscheidungen
- NVIDIA GPU für schnellere LLM-Inferenz
- CryptoPanic API-Token für erweiterte News
- Telegram Bot Token für Push-Benachrichtigungen

**Nicht nötig:**
- Python vorinstalliert haben
- Programmierkenntnisse
- Admin-Rechte *(Desktop-Verknüpfung kann dann nicht erstellt werden)*

---

## Schritt-für-Schritt Installation

### 1 — Herunterladen und Entpacken

1. ZIP-Datei herunterladen
2. Rechtsklick → Alle extrahieren
3. In einen **dauerhaften Ordner** entpacken — **nicht** in `Downloads` (wird ggf. geleert)
   ```
   Empfohlen: C:\ObsidianBot\
   ```

> ⚠️ Einzelne Dateien **nicht** aus dem Ordner verschieben. Alle Dateien müssen im selben Verzeichnis liegen. Der `prompts/`-Unterordner muss neben `launcher.pyw` bleiben.

### 2 — Installer ausführen

1. `INSTALL.bat` doppelklicken
2. Das schwarze Fenster führt vier Schritte durch:

```
[1/4] Checking Python...
[2/4] Downloading Python 3.13 Embedded (~30 MB)    ← nur wenn Python fehlt
[3/4] Installing dependencies (2–5 min)...
[4/4] Creating desktop shortcut...
       Setup Complete!
```

3. Bei `Setup Complete!` eine Taste drücken

*Installierte Pakete:* `customtkinter · psutil · ccxt · pandas · pandas_ta · python-dotenv · requests · feedparser · ollama · streamlit · plotly`

### 3 — Erststart und Setup-Wizard

1. `OBSIDIAN.vbs` doppelklicken *(oder Desktop-Verknüpfung)*
2. Der **Setup-Wizard** öffnet sich beim ersten Start

**Wizard Schritt 1 — Exchange wählen**
Klick auf die gewünschte Exchange. Die Strategie wurde auf Bitget-Daten optimiert — alle aufgeführten Exchanges funktionieren.

**Wizard Schritt 2 — API-Credentials**

API-Key auf der Exchange erstellen (Account → API-Verwaltung):

| ✅ Aktivieren | ❌ Niemals aktivieren |
|---|---|
| Trade-Berechtigung | Auszahlung / Withdrawal |
| Futures/Perpetual *(für FUTURES-Bot)* | |

| Exchange | Passphrase nötig? |
|---|---|
| Bitget, OKX, KuCoin | ✅ Ja |
| Binance, Bybit, Kraken, Coinbase, Gate.io, MEXC | ❌ Nein |

**Wizard Schritt 3 — Proxy** *(optional)*
Nur in Regionen nötig wo die Exchange eingeschränkt ist. Typische Ports: HTTP `10808`, SOCKS5 `10809`.

**Wizard Schritt 4 — Optionale Services + Verbindungstest**
- Telegram: Bot Token von `@BotFather`, Chat ID von `@userinfobot`
- CryptoPanic Token: kostenlos unter cryptopanic.com → Account → API
- Verbindungstest: prüft Credentials, zeigt USDT-Balance

→ **Setup abschließen → Trading Terminal starten**

---

## LLM einrichten (Ollama)

Die Bots funktionieren auch **ohne LLM** über einen keyword-basierten Fallback. Mit LLM sind die Entscheidungen deutlich präziser — und die neuen Features (Bull/Bear Challenge, Reflection Loop) kommen erst mit LLM richtig zur Geltung.

### Installation

```bash
# 1. Ollama herunterladen: https://ollama.ai

# 2. Modell wählen und laden
ollama pull deepseek-r1:14b   # Beste Qualität  · ~8 GB VRAM/RAM
ollama pull deepseek-r1:7b    # Gut             · ~4 GB
ollama pull qwen2.5:7b        # Schnell + gut   · ~4 GB
ollama pull mistral:7b        # Zuverlässig     · ~4 GB
ollama pull llama3.2:3b       # Sehr schnell    · ~2 GB

# 3. Server starten
ollama serve
```

### Im Terminal

- Sidebar → CONNECTIONS → **LLM: Ready** (grün)
- Bot-Karte → AI-Badge wechselt auf **AI: LLM** beim ersten Trade
- Modell wechseln: Sidebar → **Change Model** → Modell wählen → Apply → Bot neu starten

> Die Bots erkennen LLM-Wechsel innerhalb von 5 Sekunden und schalten automatisch zwischen Vollanalyse und Keyword-Fallback um.

---

## Unterstützte Exchanges

| Exchange | Spot | Futures | Hinweis |
|---|---|---|---|
| **Bitget** ⭐ | ✅ | ✅ | Optimiert auf Bitget-Daten |
| Binance | ✅ | ✅ | |
| OKX | ✅ | ✅ | |
| Bybit | ✅ | ✅ | |
| KuCoin | ✅ | ✅ | |
| Kraken | ✅ | ✅ | |
| Coinbase | ✅ | — | |
| Gate.io | ✅ | ✅ | |
| MEXC | ✅ | ✅ | |

⭐ Beim Wechsel auf eine andere Exchange den Optimizer ausführen um Parameter anzupassen.

---

## KI-Features im Detail

### Entscheidungsablauf (pro Scan-Zyklus)

```
┌─────────────────────────────────────────────────────┐
│  1. SCREENER                                         │
│     Alle USDT-Paare filtern: Volumen · Min. Pump    │
│     Parallel: RSI 15m/1h/4h · MACD · ATR · EMA(50)  │
│     Qualitätsfilter: Vol-Surge ≥ 1.5× · ATR 1-8%   │
├─────────────────────────────────────────────────────┤
│  2. AUTO SYMBOL SCORING  ← v2.1                      │
│     Volume-Surge 40% + RSI-Momentum 30%              │
│     + Historische Win-Rate (eigene DB) 30%           │
├─────────────────────────────────────────────────────┤
│  3. REFLECTION CONTEXT   ← v2.1                      │
│     ≥ 3 SLs in letzten 20 Trades?                    │
│     → RSI-Muster · Pump-Größe · BTC-Korrelation     │
│     → 3-5 Zeilen Kontext vor den Prompt              │
├─────────────────────────────────────────────────────┤
│  4. LLM-ANALYSE (erster Call)                        │
│     Prompt: RSI · News · Regime · BTC · F&G          │
│     Spot:   RESULT: BUY / WAIT                       │
│     Futures: RESULT: LONG / SHORT / WAIT             │
├─────────────────────────────────────────────────────┤
│  5. BULL/BEAR CHALLENGE  ← v2.1                      │
│     Nur bei BUY / LONG / SHORT (kein Call bei WAIT)  │
│     Zweiter LLM-Call: stärkste Gegenargumente?       │
│     CHALLENGE: WEAK   → Signal bleibt                │
│     CHALLENGE: STRONG → Signal wird WAIT             │
├─────────────────────────────────────────────────────┤
│  6. QUALITÄTS- & RISIKOFILTER                        │
│     Konfidenz · Multi-TF RSI · BTC-Dump · F&G        │
│     Blacklist · Cooldown · Daily-Killswitch           │
├─────────────────────────────────────────────────────┤
│  7. ORDER-EXECUTION                                  │
│     Kelly-Sizing · Precision-Rounding · Fee-Tracking │
└─────────────────────────────────────────────────────┘
```

### Bull/Bear Adversarial Mode *(v2.1)*

Jede positive Handelsentscheidung (BUY/LONG/SHORT) wird durch einen zweiten kurzen LLM-Call herausgefordert. Der "Challenger" sucht konkrete Gegenargumente: squeeze risk, late entry, RSI overextension, funding pressure.

- **Kein Extra-Call bei WAIT** — spart Latenz in der Mehrheit der Scan-Zyklen
- Deaktivierbar via `BULL_BEAR_MODE=false` in der `.env`
- Bei Exception im Challenge-Call: Original-Signal bleibt erhalten

### Reflection Loop *(v2.1)*

Bei ≥ 3 Stop-Losses in den letzten 20 Trades analysiert der Bot automatisch Verlust-Muster:
- Durchschnittlicher RSI beim Einstieg
- Pump-Größe vor dem Verlust
- BTC-Korrelation
- Fear & Greed Level

Die Erkenntnisse werden als 3–5 Zeilen vor den nächsten Prompt gestellt — **ohne zusätzlichen LLM-Call**. Refresh alle 2 Stunden.

### Auto Symbol Scoring *(v2.1)*

Nach den technischen Qualitätsfiltern werden Kandidaten nach einem Composite-Score sortiert:

| Gewicht | Kriterium |
|---|---|
| 40% | Volume-Surge-Ratio (Pumpe durch echtes Volumen gestützt) |
| 30% | RSI-Momentum-Score (Sweetspot 45–65 = Raum nach oben) |
| 30% | Historische Win-Rate (eigene Trade-Datenbank, letzten 30 Tage) |

### News-Quellen (parallel)

| Quelle | Typ | Token nötig |
|---|---|---|
| CryptoPanic | API | Optional |
| Reddit /r/cryptocurrency | JSON API | Nein |
| CoinTelegraph | RSS | Nein |
| CoinDesk | RSS | Nein |
| CryptoSlate | RSS | Nein |
| BeInCrypto | RSS | Nein |
| Decrypt | RSS | Nein |
| NewsBTC | RSS | Nein |
| Bitcoin Magazine | RSS | Nein |
| The Block | RSS | Nein |
| CoinGecko Trending | API | Nein |

Alle Quellen laufen parallel mit eigenem Timeout — eine langsame Quelle blockiert nicht die anderen. 5-Minuten-Cache pro Symbol.

---

## Risikomanagementsystem

Das System lernt nach jedem abgeschlossenen Trade (aktiv ab 10 Trades):

**Kelly-Criterion (Positionsgröße)**
Berechnet die optimale Losgröße aus Win-Rate, Avg-Win und Avg-Loss (30% Fraction). Grenzen aus `bot_config.json` werden immer eingehalten.

**RSI-Schwellen-Adaption**
Win-Rate in der RSI-Gefahrenzone < 35%: Schwelle −3 Punkte. > 65%: +2 Punkte. Grenzen: 50–88.

**Coin-Blacklist**
- 2 Verluste in 5 Trades: 72h Sperre
- 3+ Verluste: 168h (7 Tage)
- Persistiert in SQLite, überlebt Neustarts

**Zeitanalyse**
Stunden mit Win-Rate < 35% und Avg-PnL < −1 USDT werden für neue Käufe gesperrt.

**Daily Loss Killswitch**
Konfigurierbares Limit (Standard: −50 USDT Spot / −30 USDT Futures). Bot pausiert sich selbst bis Tagesende.

**BTC-Korrelationsschutz**
Kein Kauf bei BTC-Dump > 2% in 1h. Bei starkem Dump: offene Spot-Positionen werden auf Break-Even gezogen.

**Fear & Greed (Multi-Source)**
`alternative.me` → `coinybubble.com` → Neutral-Fallback (50). Kein Kauf bei F&G ≥ 85.

**Circuit Breaker**
Exponentieller Backoff bei aufeinanderfolgenden API-Fehlern (bis 10 Min. Maximum). Einmalige Telegram-Warnung beim ersten Trip.

---

## Backtest & Optimizer

Beide Tools starten aus der Sidebar → TOOLS.

### Backtester

Testet aktuelle Parameter auf historischen Binance-Preisdaten. Besonders nützlich nach dem Bearbeiten eines KI-Prompts.

- Strategy: BALANCED / AGGRESSIVE / FUTURES
- Zeitraum: 7 / 14 / 30 / 60 / 90 Tage
- Output streamt live ins Dialog-Fenster
- Metriken: Net PnL · Win-Rate · Sharpe · Sortino · Max Drawdown · Profit Factor

### Optimizer (K-Fold Cross-Validation)

Testet 6 Parameter in Kombination (~20.000–40.000 Kombinationen je Bot) mit 4-Fold Cross-Validation — findet Configs die in **allen** Zeitperioden profitabel sind.

| Modus | Laufzeit | Kombinationen |
|---|---|---|
| Quick | 5–15 Min. | Reduzierter Suchraum |
| Full | 30–90 Min. | Vollständiger Suchraum |

Nach Abschluss:
- Beste Konfiguration wird in Gold hervorgehoben
- Sensitivitätsanalyse: **ROBUST** / DURCHSCHNITTLICH / FRAGIL
- **"✓ Apply best config"**-Button schreibt direkt in `bot_config.json` und aktualisiert die UI sofort
- "Restart required"-Banner erscheint auf der Bot-Karte

---

## Dashboard

`Open Dashboard` öffnet die Streamlit-Analytics im Browser.

| Tab | Inhalt |
|---|---|
| **Overview** | Hero KPIs · Equity-Curve mit Bot-Markern · Drawdown-Chart |
| **Trades** | Filterbares Trade-Journal nach Outcome/Coin/Grund/Typ |
| **Positions** | Live Spot + Futures · Liq-Distanz-Ampel für Futures |
| **Performance** | **Sharpe · Sortino** · Profit Factor · Expectancy · Stunden-Heatmap |
| **Bots** | Side-by-Side Vergleich · Per-Bot Equity-Curves · Lern-Timeline |

---

## Parameter-Referenz

### Gemeinsame Parameter (alle Bots)

| Parameter | BALANCED | AGGRESSIVE | FUTURES | Beschreibung |
|---|---|---|---|---|
| Min. Pump | 2.0 % | 6.0 % | 2.0 % | Mindest-24h-Bewegung für Scan |
| Activation TP | 9.0 % | 9.0 % | 4.5 % | Partial-Exit-Trigger |
| Trailing Distance | 2.0 % | 3.0 % | 2.5 % | Abstand vom Höchstpreis |
| Stop-Loss | −4.0 % | −6.0 % | −3.5 % | Initiales Stop-Level |
| Breakeven At | 0 *(aus)* | 0 *(aus)* | 2.0 % | SL auf Entry ziehen |
| Partial Sell | 30 % | 60 % | 40 % | Anteil beim ersten TP |
| RSI Max | 65 | 65 | 70 | Max RSI auf 2+ Timeframes |
| Position Size | 10 USDT | 10 USDT | 10 USDT | Pro Trade (Margin bei Futures) |
| Kelly Cap | 25 USDT | 25 USDT | 25 USDT | Dynamisches Maximum |
| Max Open Trades | 5 | 5 | 3 | Gleichzeitige Positionen |
| Scan Interval | 300 s | 150 s | 150 s | Zwischen Scans |
| SL Cooldown | 120 min | 60 min | 120 min | Sperre nach Stop-Loss |
| Daily Loss Limit | −50 USDT | −50 USDT | −30 USDT | Tages-Killswitch |

### FUTURES-spezifische Parameter

| Parameter | Default | Bereich | Beschreibung |
|---|---|---|---|
| Leverage | 3× | 1–10× | Isoliertes Leverage |
| Liq Safety Buffer | 15 % | 5–50 % | Auto-Close vor Liquidation |
| Monitor Interval | 20 s | 5–120 s | Liq-Check für offene Positionen |

---

## Troubleshooting

**INSTALL.bat schließt sofort**
Rechtsklick → Als Administrator ausführen. Antivirus kann den Downloader blockieren.

**"Python not found" nach Installation**
Den `python\`-Ordner löschen, `INSTALL.bat` erneut ausführen.

**OBSIDIAN.vbs öffnet Notepad**
Rechtsklick → Öffnen mit → Windows Script Host.

**Setup-Wizard erscheint nicht**
Eine `.env`-Datei existiert bereits. Löschen und neu starten.

**Verbindungstest fehlgeschlagen — "invalid API key"**
Key ohne Leerzeichen einfügen. Trade- und (bei FUTURES) Perpetual-Berechtigung prüfen.

**LLM zeigt "Offline" obwohl Ollama läuft**
Sicherstellen dass Ollama auf `http://localhost:11434` läuft: `ollama serve` im Terminal.

**FUTURES-Bot findet 0 Coins**
API-Key auf Perpetual-Berechtigung prüfen. Screener erkennt `BTC/USDT` und `BTC/USDT:USDT` automatisch.

**Bull/Bear Mode dauert zu lang**
In `.env` `BULL_BEAR_MODE=false` setzen oder schnelleres Modell wählen (z.B. `qwen2.5:7b`).

**Reflection Context erscheint nicht**
Trigger: ≥ 3 Stop-Losses in letzten 20 abgeschlossenen Trades + kein Refresh in den letzten 2 Stunden. Im Log erscheint `⚠ REFLECTION` wenn aktiv.

**Optimizer: "Exited with code 1"**
Ausgabe prüfen. Wenn ein 🏆-Block vorhanden ist, war der Lauf erfolgreich.

**Prompt-Editor: "Dateien fehlen"**
Warntext anklicken → "Create default files now". Oder Launcher neu starten — Auto-Heal erstellt alle Prompt-Dateien beim Start.

---

## Projektstruktur

```
ObsidianBot/
├── launcher.pyw                  # Desktop-Terminal (GUI, CustomTkinter)
├── OBSIDIAN.vbs                  # Starter ohne CMD-Fenster
├── INSTALL.bat                   # One-Click Installer
│
├── main_bot_balanced.py          # BALANCED Bot
├── main_bot_aggressive.py        # AGGRESSIVE Bot
├── main_bot_futures.py           # FUTURES Bot
│
├── screener.py                   # Multi-TF Screener + Composite Scoring
├── news_brain.py                 # News + LLM (BALANCED)
├── news_brain_aggressive.py      # News + LLM (AGGRESSIVE)
├── news_brain_futures.py         # News + LLM (FUTURES)
├── llm_utils.py                  # Bull/Bear Challenge · Keyword-Fallback
├── risk_manager.py               # Kelly · RSI · Blacklist · Reflection
├── market_filters.py             # BTC-Korrelation · F&G · Regime
├── database.py                   # SQLite (7 Tabellen, WAL-Mode)
├── logger.py                     # ANSI-Logs · JSON-Lines · Latenz
├── news_sources.py               # Zentrale News-Aggregation (11 Quellen)
│
├── backtester.py                 # Historischer Backtest
├── optimizer.py                  # K-Fold Parameter-Optimizer
├── dashboard.py                  # Streamlit-Analytics
│
├── bot_config.json               # Live-Parameter (von UI geschrieben)
├── trading_bot.db                # SQLite-Datenbank (auto-erstellt)
│
└── prompts/
    ├── balanced.txt              # Aktiver BALANCED-Prompt (editierbar)
    ├── balanced_default.txt      # Unveränderter Default (Reset-Quelle)
    ├── aggressive.txt
    ├── aggressive_default.txt
    ├── futures.txt
    └── futures_default.txt
```

---

## Disclaimer

Krypto-Trading birgt erhebliches Kapitalrisiko. Futures-Trading ist gehebelt — Verluste werden genauso verstärkt wie Gewinne. Bei 10× Leverage kann eine Preisbewegung von ~9.5% zur Liquidation führen. Der Liq-Safety-Buffer schließt Positionen vorher automatisch, eliminiert das Risiko aber nicht.

Vergangene Backtest-Performance garantiert keine zukünftigen Ergebnisse.

**Starte immer im Simulation-Modus. Investiere niemals mehr als du dir leisten kannst zu verlieren.**

Nutzung auf eigenes Risiko.

---

<div align="center">

Built with ◆ Obsidian · Python · CustomTkinter · Ollama · SQLite · CCXT

</div>
