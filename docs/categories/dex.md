# Decentralized Exchanges (DEXs)

A **Decentralized Exchange (DEX)** is exactly what it sounds like: a place to swap one cryptocurrency for another without a central company holding your funds or matching your orders.

No account signup, no KYC, no custodian — you connect your wallet and trade directly.

## How Traditional Exchanges Work vs. DEXs

| Traditional (Centralized) Exchange like Binance, Coinbase | Decentralized Exchange (DEX) |
|------------------------------------------------------------|------------------------------|
| You deposit money into their account                     | Your coins stay in your wallet until the moment you trade |
| They hold your funds and match buyers/sellers             | Smart contracts and math automatically handle trades |
| Can freeze accounts or restrict withdrawals              | Nobody can freeze your wallet |
| Often higher liquidity, more trading pairs               | Liquidity depends on users providing it |
| Custodial risk (hacks, bankruptcy)                        | Non-custodial — you control your keys |

## The Big Innovation: Automated Market Makers (AMMs)

Most DEXs today don’t use a traditional order book (limit buys/sells). Instead, they use **Automated Market Makers** — the core building block we talked about earlier.

**Simple explanation:**
- Users create “liquidity pools” by depositing pairs of tokens (e.g., ETH and USDC).
- A math formula (usually x * y = k) decides the price based on how much of each token is in the pool.
- When you swap, the pool automatically adjusts the ratio and price.
- You get instant trades — no waiting for someone to take the other side.

This is why you can trade even obscure tokens on a DEX.

## Popular DEXs and What They’re Known For

### Uniswap (Ethereum and Layer 2s)
- The most famous and widely used DEX.
- Simple constant product formula (x * y = k).
- Versions: V2 (basic), V3 (concentrated liquidity — more efficient), V4 (hooks and custom logic).
- Great for most everyday swaps.

### Curve Finance
- Specializes in **stablecoin swaps** (USDC ↔ USDT ↔ DAI) and similar assets.
- Very low slippage because prices are supposed to stay close.
- Popular for “stablecoin pools” and earning trading fees.

### SushiSwap
- Started as a fork of Uniswap with extra rewards (SUSHI token).
- Similar interface, but often has incentive programs.

### Balancer
- Pools can have up to 8 tokens and custom weights (not just 50/50).
- Good for more advanced liquidity providers.

### PancakeSwap (on BNB Chain)
- The biggest DEX on non-Ethereum chains.
- Very cheap fees, popular in certain regions.

### Others worth knowing
- **1inch** → Aggregator that finds the best price across many DEXs.
- **dYdX** → More advanced (perpetual futures), now on its own chain.
- **GMX** → Decentralized perpetuals trading with deep liquidity.

## How to Actually Use a DEX (Step-by-Step Example with Uniswap)

1. Go to app.uniswap.org (or any DEX interface).
2. Connect your wallet (MetaMask, WalletConnect, etc.).
3. Choose the token you have (e.g., ETH) and the token you want (e.g., USDC).
4. Enter amount → it shows you the rate and slippage tolerance.
5. Confirm the transaction in your wallet.
6. Pay gas → swap complete! Tokens appear in your wallet.

That’s it — you just traded peer-to-peer on-chain.

## Benefits of DEXs

- **Permissionless** — anyone can list a token or trade.
- **Transparent** — all code and transactions public.
- **No counterparty risk** — you keep control.
- **Composable** — other protocols can build on top (e.g., flash loans + arbitrage).

## Risks to Watch Out For

- **Front-running / MEV** — miners or bots can see your trade and jump ahead (Uniswap V3 helps reduce this).
- **Impermanent loss** — if you provide liquidity and prices move a lot, you can lose money compared to just holding (covered in the Yield section).
- **Scams** — fake tokens or rug pulls. Always check contract addresses.
- **High gas fees** — on Ethereum mainnet; use Layer 2 (Arbitrum, Optimism, Base) for cheap trades.
- **Slippage** — big trades on low-liquidity pools can get bad prices.

## Quick Recap

DEXs are the gateway for most people into DeFi — swapping tokens is usually the first thing you do. They replaced centralized exchanges for many users by being trustless, open, and always available.

Next up: **Lending & Borrowing** — where you can earn interest or leverage your assets.

Ready when you are!
