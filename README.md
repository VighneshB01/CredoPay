<div align="center">

# 💳 CredoPay

### *Bringing UPI-like simplicity to Web3 payments*

[![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)](https://ethereum.org/)
[![Coinbase](https://img.shields.io/badge/Coinbase-0052FF?style=for-the-badge&logo=coinbase&logoColor=white)](https://coinbase.com/)
[![Web3](https://img.shields.io/badge/Web3-Ready-green?style=for-the-badge)](https://web3.foundation/)

[Overview](#overview) • [Features](#features) • [Architecture](#architecture) • [Getting Started](#getting-started)

</div>

---

## Overview

**CredoPay** is a full-stack Web3 payment platform that transforms complex cryptocurrency transactions into simple, UPI-like experiences. Built with modularity and scalability in mind, it bridges traditional payments and decentralized finance.

---

## ✨ Key Features

| 🔐 **Smart Payments** | 🛍️ **Marketplace** | 📱 **User Experience** |
|---|---|---|
| Account abstraction with programmable logic | x402-powered service bazaar | QR code scanning like UPI |
| Conditional escrow & milestone payments | Automated service delivery | ENS human-readable addresses |
| Multi-signature wallet support | Seller protection & ratings | Real-time transaction explorer |

### 🚀 **Unique Implementations**
- **Programmable Micropayments** - Streaming payments and usage-based billing
- **Universal Wallet Registry** - Cross-platform identity mapping
- **Advanced Conditional Engine** - Multi-stage escrow with dispute resolution
- **Coinbase Commerce Integration** - Direct crypto payment processing
- **Local Development Faucet** - Multi-token support for testing

---

## 🏗️ Architecture

```
📦 CredoPay/
├── 📁 packages/hardhat/     # Smart contracts & deployment
│   └── 📁 contracts/       # Solidity contracts
└── 📁 packages/nextjs/      # Full-stack web application
    ├── 📁 components/       # UI components
    ├── 📁 services/         # Business logic
    └── 📁 pages/           # Next.js pages & APIs
```

### 📜 **Core Smart Contracts**
- `AccountAbstraction.sol` - Programmable wallet logic
- `ConditionalPayment.sol` - Escrow & milestone system
- `ENSIntegration.sol` - Human-readable addresses
- `UniversalWalletIdRegistry.sol` - Cross-platform identity

### 🔧 **Technology Stack**

<div align="center">

![Hardhat](https://img.shields.io/badge/Hardhat-FFF04D?style=for-the-badge&logo=hardhat&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

</div>

---

## 🚀 Getting Started

```bash
# Clone & install
git clone https://github.com/VighneshB01/CredoPay.git
cd CredoPay && npm install

# Start blockchain & deploy contracts
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost

# Launch application
npm run dev
```

**Access:** Frontend at http://localhost:3000

### 🔥 **Quick Commands**
```bash
npm run compile    # Compile contracts
npm run test       # Run tests
npm run build      # Build for production
```

---

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/name`)
3. Commit changes (`git commit -m 'Add feature'`)
4. Push to branch (`git push origin feature/name`)
5. Open Pull Request

---

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

---

<div align="center">

**Built with ❤️ for the Web3 community**

![Web3 Ready](https://img.shields.io/badge/Web3-Ready-green?style=for-the-badge)
![MIT License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Ethereum Compatible](https://img.shields.io/badge/Ethereum-Compatible-purple?style=for-the-badge)

</div>
