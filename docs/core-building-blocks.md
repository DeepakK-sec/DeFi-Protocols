# Core Building Blocks of DeFi

DeFi isn't magic — it's built on a small set of simple ideas that fit together like Lego pieces. Once you understand these core parts, everything else in DeFi starts to make sense.

Here are the main building blocks you'll see over and over:

## 1. Blockchains

The foundation of everything.

A blockchain is like a giant shared notebook that:
- Everyone can read
- Anyone can add new lines to (if they follow the rules)
- Once something is written, it can **never** be erased or changed

Ethereum is the most popular blockchain for DeFi because it supports **smart contracts** (more on that next). Other chains like Polygon, Arbitrum, Optimism, Base, Solana, and Binance Smart Chain are also widely used — many are faster and cheaper than main Ethereum.

## 2. Smart Contracts

The "code is law" part of DeFi.

A smart contract is just a piece of computer code that lives on the blockchain and automatically runs when certain conditions are met.

**Example:**  
You send 100 USDC to a lending smart contract. The contract automatically:
- Records that you deposited 100 USDC
- Starts paying you interest every second
- Lets you withdraw your money + interest anytime

No bank employee needed. The code does it all, exactly as written.

Once a smart contract is launched, **nobody** can change it — not even the creators. This makes it trustworthy… but also risky if there's a bug.

## 3. Tokens

The "money" and "assets" in DeFi.

Tokens are digital items that live on the blockchain. The most common types:

- **ERC-20 tokens** → Fungible (interchangeable), like dollars or crypto coins  
  Examples: USDC, DAI, UNI, LINK
- **ERC-721 (NFTs)** → Unique, like collectibles or digital art
- **ERC-1155** → A mix of both

In DeFi, almost everything you trade, lend, or stake is an ERC-20 token.

## 4. Wallets

Your personal key to DeFi.

A wallet (like MetaMask, Rainbow, Coinbase Wallet, Trust Wallet, or a hardware Ledger) is an app that:
- Holds your **private keys** (your secret password to the blockchain)
- Lets you sign transactions (like sending money or interacting with protocols)

**Important rule:** "Not your keys, not your crypto."  
If you leave your funds on an exchange like Binance or Coinbase, you don't truly control them. In real DeFi, you connect your own wallet.

## 5. Oracles

How DeFi sees the outside world.

Smart contracts live inside the blockchain and can't check prices on Google or read the news by themselves.

**Oracles** (the biggest one is Chainlink) safely bring real-world data — like the current price of ETH, gold, or even election results — onto the blockchain.

Without good oracles, lending platforms wouldn't know when to liquidate loans, and trading wouldn't be fair.

## 6. Automated Market Makers (AMMs)

The engine behind most decentralized trading.

Traditional exchanges use an order book (buyers and sellers match). Most DeFi exchanges (DEXs) use something simpler called an AMM.

**How it works:**
- People deposit pairs of tokens into a "liquidity pool" (e.g., ETH + USDC)
- A simple math formula automatically sets the price based on how much of each token is in the pool
- You can swap one token for the other instantly — the pool adjusts the price as you trade

Uniswap, Curve, Balancer, and many others use AMMs. This is why you can trade rare tokens without waiting for someone else to take the other side.

## 7. Gas Fees

The cost of using the blockchain.

Every action — swapping, lending, withdrawing — requires computers on the network to do work. You pay a small fee for that work, called **gas**.

- On Ethereum mainnet, gas is paid in ETH and can get expensive during busy times
- Layer 2 networks (Arbitrum, Optimism, Base, zkSync, etc.) make gas fees tiny — often just pennies

## How All the Pieces Fit Together

Here's a simple flow of a typical DeFi action:



Your Wallet
   ↓ (you sign a transaction)
Smart Contract on Blockchain
   ↓ (needs real-world data?)
Oracle provides price/info
   ↓ (needs to trade tokens?)
AMM pool adjusts price and swaps
   ↓
Transaction complete — tokens move, interest accrues, etc.
   (You paid a small gas fee)

Every DeFi protocol is just a clever combination of these basic building blocks.

Now that you've got the foundation, you're ready for the fun part: seeing how these pieces create actual protocols like decentralized exchanges, lending platforms, and more.

Next up: **Decentralized Exchanges (DEXs)**!








