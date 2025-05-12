#  FundMe Smart Contract

This project is a decentralized crowdfunding platform built with **Solidity** and powered by the **Foundry** framework. Users can fund the contract with ETH, and only the contract owner can withdraw the funds. It is inspired by real-world dApps and designed to help me deepen my understanding of smart contracts, oracles, and Foundry scripting/testing workflows.

---

##  Project Goals

- Learn **Foundry** deeply through scripting, testing, and deployment
- Understand **Chainlink Price Feeds** for ETH/USD conversion
- Build a secure, gas-optimized **FundMe** contract
- Implement testing best practices using **Foundry's testing framework**
- Practice ownership and access control in Solidity

---

##  Tech Stack

| Tool/Tech | Description |
|----------|-------------|
| **Solidity** | Smart contract programming language |
| **Foundry** | Ethereum development toolchain (testing, deploying, scripting) |
| **Chainlink** | Used for real-time ETH/USD price data |
| **VS Code** | Main IDE |
| **Git** | Version control |
| **Remix IDE** | Initially used for testing basic logic before migrating to Foundry |

---

## 📜 Features

- ✅ Accept ETH funding from any user
- ✅ Get real-time ETH/USD value via Chainlink oracles
- ✅ Owner-only withdrawal pattern
- ✅ Tracks funders and their contributions
- ✅ Gas-efficient coding patterns
- ✅ Full testing coverage using `forge test`
- ✅ Script deployment using `forge script`
- ✅ Contract interaction using `cast`
