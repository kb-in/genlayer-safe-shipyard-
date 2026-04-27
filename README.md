# 🚀 Safe-Shipyard — Secure GenLayer Contract Deployer

Safe-Shipyard is a browser-based deployment tool for GenLayer Intelligent Contracts that allows developers to deploy Python contracts securely using wallet-based signing — without ever exposing private keys.

---

## 🔐 Why Safe-Shipyard?

Traditional tools sometimes require users to input private keys — which is unsafe.

Safe-Shipyard fixes this by:

- ✅ Using wallet connection (MetaMask)
- ✅ Signing transactions locally
- ❌ Never asking for private keys
- ✅ Fully browser-based (works even on iPad)

---

## ⚡ Features

- 🧪 Upload or paste Python contracts  
- 🔗 Wallet connection via MetaMask (window.ethereum)  
- 🌐 Multi-network support:
  - Bradbury Testnet  
  - Asimov Testnet  
  - Studionet  
- ⚙️ Auto-detect constructor parameters  
- 📊 Real-time deployment logs  
- 📜 Deployment history tracking  
- 🎯 Clean, beginner-friendly UI  

---

## 🧠 Powered by GenLayer SDK

This app uses the official GenLayer JavaScript SDK:

- Uses genlayer-js via ESM CDN  
- Calls:
  - client.deployContract()  
  - client.waitForTransactionReceipt()  
- Connects to real GenLayer RPC endpoints  

---

## 🔗 Supported Networks

- Bradbury Testnet (Primary)
- Asimov Testnet
- Studionet (Browser environment)

> RPC endpoints are configurable in the code.

---

## 🚀 How It Works

1. Connect your wallet  
2. Upload or paste a Python contract  
3. Select network  
4. Fill constructor parameters (auto-detected)  
5. Click deploy  
6. Approve transaction in MetaMask  
7. Contract gets deployed on GenLayer  

---

## ⚠️ Security Model

- Private keys NEVER leave your wallet  
- Transactions are signed using MetaMask  
- No backend required  
- Fully client-side interaction  

---

## 📱 Works on iPad

You can deploy contracts directly from iPad using:

- MetaMask mobile browser  
- WalletConnect-supported wallets  

---

## 🛠️ Local Usage

No build required.

Just open:

bash index.html 

Or serve locally:

bash npx serve . 

---

## 🌍 Deploy Your Own Version

### Option 1 — Netlify (Fastest)

1. Go to netlify.com  
2. Drag & drop index.html  
3. Get live URL instantly  

---

### Option 2 — Vercel

1. Upload project to GitHub  
2. Import into Vercel  
3. Deploy  

---

## 💧 Get Testnet Tokens

Before deploying, get free tokens:

- https://testnet-faucet.genlayer.foundation/  
- https://genlayerlabs.github.io/trivia-faucet/  

---

## 🐛 Troubleshooting

### Wallet not connecting
- Ensure MetaMask is installed  
- Use MetaMask browser on mobile  

---

### Transaction fails
- Check you have testnet tokens  
- Verify network selection  

---

### Contract not deploying
- Check syntax of Python contract  
- Ensure constructor arguments are correct  

---

## 🧠 Future Improvements

- AI contract explanation  
- Gas estimation  
- Deployment analytics  
- Multi-wallet support  

---

## 🎯 Project Goal

To make GenLayer onboarding simple, secure, and accessible — especially for beginners and mobile users.

---

## 👨‍💻 Built by

Kbin

---

## 📜 License

MIT Lic
