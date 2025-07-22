
# 🔐 Simple Crypto Wallet

A multi-chain cryptocurrency wallet built with **React** that supports **Ethereum**, **Bitcoin**, and **Solana** using a secure 12-word mnemonic phrase. Send, receive, and view balances all from a single dashboard.

---

## ✨ Features

- ✅ **Import/Create Wallet** using a 12-word mnemonic
- ✅ **Generate addresses** for Ethereum, Bitcoin, and Solana
- ✅ **View token balances** in real-time
- ✅ **Send crypto** to other wallet addresses
- ✅ **Live transaction feedback** with status polling (for Solana)
- ✅ **Mnemonic recovery** (stored locally for demo — not secure for production)

---
# 🔐 Simple Crypto Wallet

A multi-chain cryptocurrency wallet built with **React** that supports **Ethereum**, **Bitcoin**, and **Solana** using a secure 12-word mnemonic phrase. Send, receive, and view balances all from a single dashboard.

---

### ✅ Live Demo

🚀 [Click here to try the live app](https://sweet-cendol-93d3f7.netlify.app/)

---


## 📂 Project Structure

```bash
src/
├── components/
│   ├── AssetCard.jsx           # UI for each coin with send functionality
│   ├── WalletDashboard.jsx     # Main dashboard to view wallet and balances
│   └── Login.jsx               # Wallet import/create screen
│
├── context/
│   └── WalletContext.js        # Global wallet state and login/logout
│
├── services/
│   ├── blockchain.js           # Send & getBalance functions for ETH, BTC, SOL
│   └── wallet.js               # Mnemonic generation and derivation


🚀 Getting Started

🧾 Clone the Repository
git clone https://github.com/abhisheksingg-5351/Cryptowallet
cd cryptowallet

📦 Install Dependencies

npm install

▶️ Run the Development Server

npm run dev

🛠 Blockchain Functions Overview

Chain	   Library	       Description
Ethereum ethers.js	Transaction creation & balance check
Bitcoin	bitcoinjs-lib	P2PKH address, send via WIF
Solana	@solana/web3.js	Transaction and confirmation polling

🔐 Wallet    Derivation Paths

Blockchain  	Derivation Path
Ethereum	   m/44'/60'/0'/0/0
Bitcoin	      m/44'/0'/0'/0/0
Solana	      m/44'/501'/0'/0'

⚠️ Disclaimer

This project is intended for educational/demo purposes only.
It stores wallet mnemonics in the browser's localStorage, which is not secure.
Never use this wallet with real funds. For real usage, use hardware wallets and secure backends.

📸 UI Preview
Replace the placeholders below with actual screenshots (e.g., /screenshots/login.png)

🔐 Login / Import Wallet

📊 Wallet Dashboard

📤 Send Crypto

📬 Feedback & Contributions
Feel free to open issues or submit pull requests.
For large changes, please open an issue first to discuss your idea.
