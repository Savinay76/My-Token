# 🪙 ERC-20 Token Smart Contract (MyToken – MTK)

## 📌 Project Overview

The **ERC-20 Token Smart Contract** is a beginner-friendly blockchain project that demonstrates how fungible cryptocurrency tokens are created and managed on the Ethereum blockchain.

It simulates real-world token behavior such as **balance tracking, token transfers, spending approvals, and delegated transfers**, while strictly following the **ERC-20 standard** to ensure compatibility with wallets and other smart contracts.

This project reflects a **strong foundational understanding of blockchain concepts**, smart contract development, and Ethereum token standards.

---

## 🎯 Objective

To build a smart contract that:
- Defines a custom cryptocurrency token
- Implements all core ERC-20 functionalities
- Allows secure token transfers and approvals
- Emits blockchain events for transparency
- Can be deployed and tested using RemixIDE

---

## 🧩 Core Features

### ✅ Token Metadata
- Token Name
- Token Symbol
- Decimal precision (18)
- Fixed total supply minted at deployment

### ✅ Balance Management
- Tracks token balances for every Ethereum address
- Ensures accurate balance updates after each transaction

### ✅ Token Transfers
- Allows token holders to transfer tokens to others
- Prevents transfers to the zero address
- Prevents transfers exceeding available balance

### ✅ Allowance & Delegated Transfers
- `approve()` enables third-party spending
- `transferFrom()` allows approved spending
- Allowances decrease automatically after use

### ✅ Event Emission
- Emits `Transfer` events for every token movement
- Emits `Approval` events for allowance updates
- Enables transaction tracking via block explorers

## 🏗️ Project Structure

```text
My-Token/
│
├── contracts/
│   └── MyToken.sol
│       └── ERC-20 smart contract implementation
│
├── Screenshots/
│   ├── compilation.png
│   │   └── Successful Solidity compilation in RemixIDE
│   ├── deployment.png
│   │   └── Contract deployment transaction details
│   ├── token-info.png
│   │   └── Token name, symbol, decimals, total supply
│   ├── transfer-test.png
│   │   └── Successful token transfer between accounts
│   └── events.png
│       └── Transfer and Approval events emitted
│
└── README.md
    └── Project documentation

```
### 🛠️ Technologies Used

- Solidity ^0.8.x

- Ethereum Virtual Machine (EVM)

- RemixIDE

- JavaScript VM (local blockchain simulation)

### 🚀 How to Deploy the Contract (RemixIDE)

- Open https://remix.ethereum.org/

- Create a new file MyToken.sol

- Paste the ERC-20 smart contract code

- Set Solidity compiler version to 0.8.x

- Compile the contract

- Open Deploy & Run Transactions

- Select JavaScript VM

### Deploy with constructor value:
```bash
1000000000000000000000000
```

(1,000,000 tokens with 18 decimals)

### 🔗 Smart Contract Usage
- Check Token Balance
```bash
balanceOf(address)
```
- Transfer Tokens
```bash
transfer(to, amount)
```
- Approve Token Spending
```bash
approve(spender, amount)
```
- Check Allowance
```bash
allowance(owner, spender)
```
- Transfer Tokens on Behalf
```bash
transferFrom(from, to, amount)
```
### 📈 Learning Outcomes

- Understood ERC-20 token standards and compliance

- Learned how balances and allowances are managed on-chain

- Gained hands-on experience with Solidity mappings

- Practiced secure smart contract validation using require

- Learned the importance of blockchain event emission

- Gained confidence deploying and testing contracts with RemixIDE

- Built a strong foundation for advanced token features like minting and burning

### ✅ Expected Outcomes (All Achieved)

- ✔ ERC-20 compliant smart contract

- ✔ Successful deployment on local blockchain

- ✔ All core functions tested

- ✔ Clean and readable Solidity code

- ✔ Wallet-compatible token behavior

### 👤 Author

- Savinay Reddy Sathi