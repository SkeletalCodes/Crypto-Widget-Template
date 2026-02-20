# Configure Your Wallet Addresses

Open the file `index.html` and find the `ADDRESSES` constant near the top.  

You will see something like this:

```javascript
const ADDRESSES = {
  bitcoin: "YOUR_BITCOIN_ADDRESS",
  ethereum: "YOUR_ETHEREUM_ADDRESS",
  binancecoin: "YOUR_BNB_ADDRESS",
  solana: "YOUR_SOLANA_ADDRESS",
  litecoin: "YOUR_LITECOIN_ADDRESS",
  dogecoin: "YOUR_DOGECOIN_ADDRESS",
  tron: "YOUR_TRON_ADDRESS"
};

Replace each "YOUR_..._ADDRESS" with your actual wallet address.

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

Save the file and commit your changes.
Your widget will automatically update and display your wallet addresses.

Important:
Only edit the ADDRESSES constant. Do NOT modify:

EXPLORERS constant

${addr} placeholders

Copy button code

Check Balance button code
