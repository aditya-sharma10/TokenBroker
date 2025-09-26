SimpleStockBroker
A simple Solidity smart contract that manages a list of popular stock symbols. Users can check if a stock is available and emit events for a range of stocks. Perfect for learning basic listing management on Ethereum.

**Features**
check if a stock symbol is available
Emit events for a range of listings

**Predefined stock list: AAPL, MSFT, GOOGL, AMZN, TSLA, META, NFLX, NVDA, BABA, JPM
**

Records the contract owner

**Usage**
Deploy the contract

1. Call checkStatus("AAPL") → returns "available" or "not available"

2. Call range(5) → emits events for the first 5 stock symbols

**Event**
1. RangeValue(string value) – emitted for each stock in the range

License: MIT
