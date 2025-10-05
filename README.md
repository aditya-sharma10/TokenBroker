# 📈 SimpleStockBroker

**SimpleStockBroker** is a lightweight Solidity smart contract that manages a list of popular stock symbols on Ethereum.  

It’s perfect for beginners who want to learn **basic listing management**, event emission, and ownership in smart contracts.

---

## ✅ Features

- Check if a stock symbol is available  
- Emit events for a range of stock listings  
- Tracks the **contract owner**  

---

## 📊 Predefined Stock List
AAPL, MSFT, GOOGL, AMZN, TSLA, META, NFLX, NVDA, BABA, JPM



---

## 🚀 Usage

1. **Deploy** the contract  
2. **Check stock availability**  
```solidity
checkStatus("AAPL")  // returns "available" or "not available"

