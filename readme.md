# Blockchain Sandbox

Your very own blockchain complete with the following components:

- Wallets (public/private key pairs)
- Transactions (signed by wallets)
- Mining (mine a block of transactions and reap the rewards)
- Ephemeral Testnet (the blockchain vanishes when the node stops) 

## Quick Start

    npm install
    npm start

http://localhost:3030/index.html shows blockchain and wallet controls.

## Architecture

Core Files
-- index.js - central module
-- lib/blockchain.js - The blockchain functionality; add transactions to a block and try to mine it.
-- lib/wallet.js - Wallet functionality; create wallets and sign transactions

Developer Mode
-- server.js - imports index.js and sets up a rest API for development.
-- static/* - the UI for server.js

## Contribution Guidelines

- Create a pull request!

## Copyright

- MIT licensed open source created by Cenetex Inc. (www.cenetex.com)