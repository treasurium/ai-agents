# 🧠 Treasurium AI Agents

This repository contains AI-powered automation workflows built for [n8n](https://n8n.io), designed to interact with Web3 and DeFi ecosystems through intelligent triggers, analysis, and messaging.

## 🚀 Included Agent

### ✅ AAVE DeFi Health Monitor

Monitors a user's wallet position on Aave and generates a real-time health report including:

- Supplied and borrowed balances
- Health Factor
- Liquidation threshold
- Loan-to-Value (LTV) ratio
- Maximum borrowable amount
- Risk alerts

Reports are delivered via Telegram or email in a human-readable format.

🎥 **Watch the Demo**  
[![Watch the Demo](https://img.youtube.com/vi/teLNnkoGnJI/hqdefault.jpg)](https://youtu.be/teLNnkoGnJI?si=uZr8qxLfmJNcqvHx)

## 🧪 How to Use

1. Import the `aave-health-monitor/workflow.json` into your [n8n](https://n8n.io) instance.
2. Configure the following:
   - Moralis DeFi API key
   - Telegram Bot Token or email credentials
   - Wallet address input
3. Run the workflow on a schedule or via manual trigger.

## 📦 License

[MIT](./LICENSE)

---

