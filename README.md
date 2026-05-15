# ⚖️ Verdict Protocol — Meme Court Bot

> **The On-Chain Tribunal. Every wallet gets judged.**

AI-powered on-chain wallet intelligence bot for the Mantle ecosystem and all major EVM chains. Built for the **Mantle Turing Test Hackathon 2026 — AI Awakening, Track 02: AI Alpha & Data**.

[![Telegram](https://img.shields.io/badge/Telegram-@MemeCourt__Bot-blue?logo=telegram)](https://t.me/MemeCourt_Bot)
[![Website](https://img.shields.io/badge/Website-verdictprotocol.online-green)](https://verdictprotocol.online)
[![Track](https://img.shields.io/badge/Track-AI%20Alpha%20%26%20Data-purple)](https://dorahacks.io/hackathon/mantleturingtesthackathon2026)

---

## 🎯 What It Does

Meme Court Bot brings **smart money tracking and on-chain anomaly detection** directly into Telegram — powered by AI and styled as a crypto court tribunal.

Users can:
- 🔍 **Summon any EVM wallet to court** — get an instant AI judge verdict on whale status, risk level, and anomalous behavior
- 🐋 **Track whale suspects** — monitor known large wallets across Mantle and BNB Chain in real time
- 👁 **Issue subpoenas** — set surveillance on any wallet and receive instant alerts on large movements
- ⚖️ **Get AI rulings** — DeepSeek AI delivers dramatic court-style verdicts on every wallet analyzed

---

## 🔗 Supported Chains

| Chain | Emoji | Symbol |
|-------|-------|--------|
| Mantle | 🟢 | MNT |
| BNB Chain | 🟡 | BNB |
| Ethereum | 🔵 | ETH |
| Base | 🟦 | ETH |
| Arbitrum | 🔷 | ETH |
| Optimism | 🔴 | ETH |
| Polygon | 🟣 | MATIC |
| Avalanche | 🔺 | AVAX |

---

## 💬 Commands

| Command | Alias | Description |
|---------|-------|-------------|
| `/scan <address> [chain]` | `/judge` | Deep scan a wallet — summon to court |
| `/whale [chain]` | `/suspect` | View whale suspect lineup |
| `/watch <address> [label]` | `/subpoena` | Issue surveillance order |
| `/watchlist` | `/docket` | View active court cases |
| `/unwatch <address>` | — | Dismiss a case |

**Chain shortcuts:** `eth`, `bnb`, `polygon`, `arb`, `op`, `base`, `mantle`, `avax`

---

## 🤖 Example Output

```
⚖️ MEME COURT — CASE #04721
━━━━━━━━━━━━━━━━━━━
👨‍⚖️ THE HONORABLE AI JUDGE PRESIDING
🪙 Defendant: 0x8894...d4e3
🔗 Jurisdiction: 🟡 BNB Chain
━━━━━━━━━━━━━━━━━━━
💰 Holdings: 129,070 BNB (~$70M+)
🔨 VERDICT: GUILTY — MEGA WHALE 🔴
👨‍⚖️ The court finds this wallet guilty of extreme whale activity.
   Hereby sentenced to maximum surveillance.
```

---

## 🛠 Tech Stack

- **Runtime:** Python 3.9+
- **Bot Framework:** python-telegram-bot 20.7
- **On-Chain Data:** Moralis API (multi-chain)
- **AI Judge:** DeepSeek Chat API
- **Chains:** Mantle, BNB Chain, Ethereum, Base, Arbitrum, Optimism, Polygon, Avalanche

---

## 🚀 Quick Start

```bash
git clone https://github.com/lant1ng-1216/verdict-protocol-bot
cd verdict-protocol-bot
pip install -r requirements.txt
cp .env.example .env
# Fill in your keys in .env
python bot.py
```

---

## 🌐 Links

- **Website:** [verdictprotocol.online](https://verdictprotocol.online)
- **Telegram Bot:** [@MemeCourt_Bot](https://t.me/MemeCourt_Bot)
- **Hackathon:** [Mantle Turing Test 2026](https://dorahacks.io/hackathon/mantleturingtesthackathon2026)

---

*⚖️ Court is always in session.*
```
