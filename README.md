# 🧬 Eternum CLI Wallet

Welcome to the official Eternum Command Line Wallet, built in Swift.

This tool allows you to:
- Generate secure wallets and sign sigils
- Log wallet generation rituals with timestamped metadata
- Verify and validate sigil hashes
- Export sealed JSON and encrypted logs
- Prepare files for IPFS pinning

---

### 🔐 Smart Contract Blueprint: SigilMemory.sol

The `SigilMemory.sol` contract is designed to register the following:
- Wallet address of origin
- IPFS CID of the sealed sigil
- SHA256 of the log file
- Timestamp of creation

📁 Contract Path: `contracts/SigilMemory.sol`  
📜 Deploy Script: `script/Deploy.s.sol`

> This smart contract is ready for Base Layer 2 deployment. Deployment is paused until funding is received.

---

### 💾 Status

- Current version: `v1.0.0`
- Swift Package Compatible: ✅
- Solidity Contract Included: ✅
- Forge Simulation Ready: ✅
- Gas Funds: ❌ Awaiting donation or grant
