# Public Crypto Wallet Widget

A simple, easy-to-use crypto wallet widget displaying 7 popular cryptocurrencies with live USD prices. Users can copy wallet addresses or check balances on blockchain explorers. Ideal for GitHub Pages or personal websites.

# Features

- Supports Bitcoin (BTC), Ethereum (ETH), Binance Coin (BNB), Solana (SOL), Litecoin (LTC), Dogecoin (DOGE), Tron (TRX)
- Real-time prices via CoinGecko API
- Copy wallet addresses with one click
- Open wallet in blockchain explorers
- Clean dark-themed UI with hover effects
- Auto-refreshes every 30 seconds
- No backend required

# Setup on GitHub Pages

Clone or fork the repository to your GitHub account.

Go to your repository Settings → Pages

Under Source, switch from None to main and click Save

Wait about 30–60 seconds, then refresh the page

Your public link will be available at:

https://yourusername.github.io/repository-name/

# Configure Your Wallet Addresses

Open the file:

index.html

Navigate to the constants section near the top of the file.

You will see:

const ADDRESSES = {
  bitcoin: "YOUR_BITCOIN_ADDRESS",
  ethereum: "YOUR_ETHEREUM_ADDRESS",
  binancecoin: "YOUR_BNB_ADDRESS",
  solana: "YOUR_SOLANA_ADDRESS",
  litecoin: "YOUR_LITECOIN_ADDRESS",
  dogecoin: "YOUR_DOGECOIN_ADDRESS",
  tron: "YOUR_TRON_ADDRESS"
};

Replace each "YOUR_..._ADDRESS" value with your own wallet address.

Example:

const ADDRESSES = {
  bitcoin: "bc1qexample123...",
  ethereum: "0xexample123...",
  binancecoin: "0xexample123...",
  solana: "ExampleSolanaAddress...",
  litecoin: "Lexample123...",
  dogecoin: "Dexample123...",
  tron: "Texample123..."
};

Save the file and commit the changes.

Your widget will automatically update and display your wallet addresses.

# Important

Only edit the ADDRESSES constant.

Do NOT modify:

- EXPLORERS constant
- ${addr} placeholders
- Copy button code
- Check Balance button code

These are already configured and will automatically work with your addresses.

# Updating Your Widget

Any changes you commit to index.html will automatically update on your GitHub Pages site after refreshing.

# Contributing

Customize the UI, add more cryptocurrencies, or suggest improvements. Pull requests and issues are welcome.

# License

MIT License. See LICENSE for details.
