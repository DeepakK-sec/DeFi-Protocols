# Derivatives & Synthetics in DeFi

**Derivatives** in DeFi are like advanced bets on price movements — without needing to own the actual asset. The most popular type is **perpetual futures (perps)**: contracts that let you go long (bet price up) or short (bet price down) with leverage, and they never expire.

**Synthetics** are digital versions of real-world assets (stocks, gold, forex) created on-chain.

These protocols bring Wall Street-style trading to DeFi: high leverage, 24/7 markets, and global access — all non-custodial.

## Why Derivatives Matter in DeFi

- **Leverage** → Trade with 10x–100x your capital (big wins... or big losses).
- **Hedging** → Protect your portfolio (e.g., short ETH if you think it’ll drop).
- **Speculation** → Bet on any asset, even if it's not crypto.
- **Efficiency** → No expiration dates on perps means you can hold positions forever (paying/receiving small funding fees).

In 2025, decentralized perps have exploded — handling trillions in volume and capturing ~20–25% of the global perpetual futures market.

## Types of DeFi Derivatives

1. **Perpetual Futures (Perps)**  
   The dominant type. Use leverage to trade price direction indefinitely.

2. **Options**  
   Give you the right (but not obligation) to buy/sell at a set price. Less common in DeFi yet.

3. **Synthetics**  
   Tokens that track real-world assets (e.g., sAAPL for Apple stock).

## Leading Protocols in 2025

### Hyperliquid
- The clear leader — often 70–80% of decentralized perp volume.
- Built on its own high-speed Layer 1 chain.
- CEX-like speed, deep liquidity, up to 100x+ leverage.
- Massive daily volumes (tens of billions).

### dYdX
- Long-time favorite, now on its own Cosmos-based chain.
- Order book model for precise trading.
- Institutional-grade features, high liquidity.

### GMX
- AMM-based (pool liquidity like Uniswap).
- Popular on Arbitrum and Avalanche — low fees, simple interface.
- Zero price impact on many trades, great for larger sizes.

### Gains Network (gTrade)
- Similar to GMX — synthetic leverage on crypto, forex, stocks.
- High leverage, daily payouts to LPs.

### Synthetix
- Pioneer of synthetics (sTokens like sBTC, sAAPL).
- Recently relaunched perps on Ethereum mainnet (late 2025).
- Focus on real-world assets and deep Ethereum composability.

Others to watch: Aevo, MYX Finance, Vertex — new challengers gaining traction.

## How Perps Work (Simple Example)

1. Deposit collateral (e.g., USDC).
2. Open a position: Long 10x BTC at $60,000 (with $1,000 collateral → $10,000 exposure).
3. If BTC goes to $66,000 → you profit $1,000 (100% return).
4. If it drops to $54,000 → liquidated (lose your collateral).
5. Funding rate: Longs pay shorts (or vice versa) every few hours to keep price close to spot.

## Benefits

- Non-custodial — you control your keys.
- Global & permissionless.
- Transparent on-chain execution.
- Composable with other DeFi (use perps in yield strategies).

## Risks (This Is Advanced & Dangerous Stuff)

- **Liquidation** → Leverage amplifies losses — easy to get wiped out.
- **Funding rates** → Can eat profits if holding against the trend.
- **Oracle risks** → Wrong price feeds can cause bad liquidations.
- **Smart contract bugs** → Hacks have happened.
- **Extreme volatility** → Perps markets can be brutal.

**Never trade with more than you can afford to lose. Start on testnets!**

## Quick Comparison (Late 2025)

| Protocol      | Model          | Strengths                        | Leverage | Best For                  |
|---------------|----------------|----------------------------------|----------|---------------------------|
| Hyperliquid  | Custom L1     | Speed, volume, liquidity        | 50–100x+ | Pro traders               |
| dYdX         | Order book    | Precision, institutional tools  | Up to 50x| Advanced users            |
| GMX          | AMM pools     | Simplicity, low slippage        | Up to 100x| Retail, larger trades     |
| Gains Network| Synthetic AMM | Forex/stocks, high leverage     | Up to 1000x (!)| Risk-tolerant speculators |
| Synthetix    | Synthetics/Perps | Real-world assets, Ethereum native | Up to 50x| RWA exposure              |

Derivatives are the most advanced (and riskiest) part of DeFi — great for experienced traders looking for leverage and hedging.

Next: **Insurance** — how to protect yourself from some of these risks.
