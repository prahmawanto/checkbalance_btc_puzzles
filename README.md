# Bitcoin Wallet Balance Checker

A Python script to fetch the final balance (in BTC) of multiple Bitcoin wallet addresses using the [Blockchain.com API](https://www.blockchain.com/explorer/api).

## Features

- Batch processing of wallet addresses (up to 20 per API call)
- Automatic conversion from satoshi to BTC
- Simple console output showing address balances
- Basic error handling for API responses

## Requirements

- Python 3.x
- `requests` library

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/bitcoin-balance-checker.git
   cd bitcoin-balance-checker
