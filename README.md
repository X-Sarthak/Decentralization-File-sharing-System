---

# 📂 Decentralized File Sharing System

A blockchain-powered decentralized file-sharing system using **Solidity, Node.js, React, Hardhat, and Pinata**.

## 🚀 Features

- **Decentralized Storage**: Utilizes IPFS via **Pinata** for secure and distributed file storage.
- **Smart Contracts**: Built using **Solidity** and deployed on Ethereum.
- **React Frontend**: User-friendly UI built with **React.js**.
- **Hardhat**: For smart contract development, testing, and deployment.
- **Node.js Backend**: Handles API requests and blockchain interactions.

## 🛠️ Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js
- **Smart Contracts**: Solidity
- **Development Environment**: Hardhat
- **Decentralized Storage**: Pinata (IPFS)

## 📦 Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/decentralized-file-sharing.git
cd decentralized-file-sharing
```

### 2️⃣ Install Dependencies
```sh
npm install
```

### 3️⃣ Compile and Deploy Smart Contracts
```sh
npx hardhat compile
npx hardhat run scripts/deploy.js --network localhost
```

### 4️⃣ Start the Frontend
```sh
cd frontend
npm start
```

### 5️⃣ Start the Backend
```sh
cd backend
node server.js
```

## 📡 Connecting to Pinata

To use **Pinata** for decentralized storage:

1. Create an account on [Pinata](https://www.pinata.cloud/)
2. Get your **API Key** and **Secret Key**
3. Add them to your environment variables:
   ```sh
   PINATA_API_KEY=your_api_key
   PINATA_SECRET_API_KEY=your_secret_key
   ```

## 📜 License

This project is licensed under the **MIT License**.

---
