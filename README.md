# SustainabilityReward-Hajj
# 🌱 Sustainability Reward Smart Contract for Hajj

This project implements a blockchain-based reward system to promote sustainable behaviors during the Hajj pilgrimage. Pilgrims are incentivized through ERC-20 tokens for engaging in eco-friendly actions such as recycling, conserving water and electricity, and using public transportation.

---

## 📌 Project Features

- ✅ **ERC-20 Smart Contract** with minting and burning functions  
- ♻️ **Behavior Types**: Recycling, Green Energy (electricity/water), EcoMove (transport)  
- 🔐 **Custodial Wallet Integration**  
- 🔄 **Token Redemption** with on-chain event logging  
- 🔬 **Simulated Case Study** for a 5-day Hajj journey  
- 📊 **Auditable**, **transparent**, and **extensible** framework  

---

## 📂 Project Structure

├── contracts/
│ └── SustainabilityToken.sol # Main smart contract
├── scripts/
│ └── deploy.js # Script for contract deployment
├── test/
│ └── SustainabilityToken.test.js # Sample test cases (optional)
├── README.md
└── .gitignore


---

## 🛠️ Deployment Steps

> **Environment Requirements**
- Node.js ≥ 18.x
- Hardhat or Truffle
- Metamask wallet connected to a testnet (Goerli, Sepolia, etc.)

### 1. Clone the repository
```bash
git clone https://github.com/sabreen2020/SustainabilityReward-Hajj.git
cd SustainabilityReward-Hajj
### 2. Install dependencies
npm install
npx hardhat compile
4. Deploy the contract to testnet
Set your .env with private key and Infura/Alchemy URL, then:
npx hardhat run scripts/deploy.js --network goerli
