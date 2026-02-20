Configure Your Wallet Addresses

To use the widget with your own wallets, open the file:

index.html

Navigate to the constants section near the top of the file. You will see this code:

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

Important

Only edit the ADDRESSES constant.

Do NOT modify:

The EXPLORERS constant

Any ${addr} placeholders

The Copy button code

The Check Balance button code

These are already configured and will automatically work with your addresses.

Publish with GitHub Pages

After committing your changes:

Go to your repository Settings → Pages

Under Source, select:

Branch: main

Folder: / (root)

Click Save

Your widget will be live at:

https://yourusername.github.io/repository-name/
