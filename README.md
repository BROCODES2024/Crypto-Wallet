# Crypto Wallet DApp

## Overview
This is a decentralized web application (DApp) that enables users to generate and manage cryptocurrency wallets for both Solana and Ethereum networks using mnemonic seed phrases. Users can create wallets, derive new addresses, and interact with their generated wallets.

## Features
- **Generate Seed Phrase**: Create a new mnemonic seed phrase.
- **Derive Solana Wallets**: Generate Solana wallet addresses from the mnemonic.
- **Derive Ethereum Wallets**: Generate Ethereum wallet addresses from the mnemonic.
- **Multi-Wallet Support**: Manage multiple wallets for both Ethereum and Solana.

## Technologies Used
- **React.js**
- **Solana Web3.js**
- **Ethers.js**
- **BIP39**
- **Ed25519-hd-key**
- **TweetNaCl**

## Prerequisites
Before running the application, ensure you have the following installed:
- **Node.js** (v16 or higher recommended)
- **npm** or **yarn**

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/BROCODES2024/Crypto-Wallet.git
cd Crypto-Wallet
```

### Install Dependencies
```bash
npm install
```

### Start the Application
```bash
npm run dev
```
This will launch the DApp on `http://localhost:3000/`.

## How to Use
1. **Generate a Seed Phrase**: Click the `Create Seed Phrase` button to generate a new mnemonic.
2. **Derive a Solana Wallet**: Click `Add SOL Wallet` to derive a new Solana wallet address from the mnemonic.
3. **Derive an Ethereum Wallet**: Click `Add ETH Wallet` to derive a new Ethereum wallet address from the mnemonic.
4. **View Wallets**: Generated wallet addresses will be displayed in the UI.

## Folder Structure
```
Crypto-Wallet/
│── src/
│   ├── components/
│   │   ├── SolanaWallet.js
│   │   ├── EthWallet.js
│   ├── App.js
│   ├── index.js
│── package.json
│── README.md
```

## Deployment
To deploy your application:
```bash
npm run build
```
Then, you can deploy the generated `build/` folder to platforms like **Vercel**, **Netlify**, or **GitHub Pages**.

## Notes
- This DApp supports both **Solana** and **Ethereum** blockchain networks.
- Wallets are generated locally using mnemonic seed phrases, ensuring security and privacy.

## License
This project is licensed under the MIT License.

## Contact
For any issues or contributions, feel free to open an issue on GitHub or contact the maintainer.

