# StellarPayWall Smart Contracts ⚡

> **Pure Rust workspace containing the `paywall_vault` Soroban smart contracts on the Stellar Network.**

[![CI Build](https://github.com/HassanKorey/StellarPayWall-contract/actions/workflows/ci.yml/badge.svg)](https://github.com/HassanKorey/StellarPayWall-contract/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Stellar Testnet](https://img.shields.io/badge/Stellar-Testnet-success.svg)](https://stellar.expert/explorer/testnet/contract/CA4L7T6R74G3T5F5V7V7RWWUHE2J76Y4WJ3L7C2WJ3L7C2WJ3L7C2WJ3)
[![Soroban SDK v21.0.0](https://img.shields.io/badge/Soroban%20SDK-v21.0.0-blue.svg)](https://soroban.stellar.org)

📖 **Documentation Portal**: [https://HassanKorey.github.io/StellarPayWall-app](https://HassanKorey.github.io/StellarPayWall-app)  
🖥️ **Frontend & Middleware Workspace**: [HassanKorey/StellarPayWall-app](https://github.com/HassanKorey/StellarPayWall-app)  
🚀 **Live Merchant Gateway**: [https://stellarpaywall.onrender.com](https://stellarpaywall.onrender.com)

---

## 🌟 Overview

`StellarPayWall-contract` is the pure Rust workspace containing the Soroban smart contracts (`contracts/paywall_vault`) for the **StellarPayWall** protocol on **Stellar**.

Written in `#![no_std]` Rust with `soroban-sdk` v21.0.0, the `paywall_vault` contract handles Soroban Asset Contract (SAC / SEP-41 USDC/XLM) deposit escrow, challenge memo verification, merchant claims, and `PaymentVerified` event emission.

---

## 👥 Maintainer Governance

| Name | Role | GitHub | Contact |
| :--- | :--- | :--- | :--- |
| Hassan Akorede (EDUN) | Lead Architect | [@HassanKorey](https://github.com/HassanKorey) | Telegram: `@HassanKorey` |
| Co-Maintainer | Smart Contract Reviewer | [@CoMaintainer](https://github.com/CoMaintainer) | Discord: `comaintainer#0001` |

---

## 📍 Deployed Contract Address & Explorer

| Contract | Network | Address & Stellar Expert Link |
| :--- | :--- | :--- |
| `paywall_vault` | Stellar Testnet | [`CA4L7T6R74G3T5F5V7V7RWWUHE2J76Y4WJ3L7C2WJ3L7C2WJ3L7C2WJ3`](https://stellar.expert/explorer/testnet/contract/CA4L7T6R74G3T5F5V7V7RWWUHE2J76Y4WJ3L7C2WJ3L7C2WJ3L7C2WJ3) |

- **Compiled WASM SHA-256 Hash**: `744f4b889771e3e8581093d0e796656686e94c30aefcbffd646fed848fe4c25d`

---

## 🧪 Testing & Verification

Run the complete cargo unit test suite:

```bash
cargo test --workspace --verbose
```

Build the release WASM target:

```bash
cargo build --package paywall-vault --target wasm32-unknown-unknown --release
```

---

## 📄 License

This project is licensed under the terms of the [MIT License](LICENSE).
