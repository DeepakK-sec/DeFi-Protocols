# Lending & Borrowing in DeFi

Lending and borrowing protocols are like decentralized banks. You can earn interest on your crypto by lending it out, or borrow crypto by putting up collateral — all without a bank, credit check, or paperwork.

Everything happens through smart contracts, and it's open to anyone with a wallet.

## How DeFi Lending Works (The Basics)

There are two sides:

1. **Lenders (Suppliers)**  
   - You deposit crypto into a protocol (e.g., USDC, ETH, DAI).  
   - You start earning interest immediately, paid by borrowers.  
   - You can withdraw anytime (as long as there's enough liquidity).

2. **Borrowers**  
   - You deposit collateral (usually more than you want to borrow — called over-collateralization).  
   - You borrow another asset (e.g., deposit ETH, borrow USDC).  
   - You pay interest to the lenders.  
   - If your collateral value drops too much, the protocol automatically liquidates it to pay back the loan.

This over-collateralization is key — it protects lenders if prices crash.

## Supply vs. Borrow Rates

Interest rates in DeFi are **variable** and change in real time based on supply and demand.

- When few people are borrowing → borrow rates low, lending rates low.
- When lots of borrowing → borrow rates high → lenders earn more.

No fixed 5% APY like a bank — rates can swing from 1% to 50%+ depending on the asset and market.

## Popular Lending Protocols

### Aave
- One of the biggest and most trusted.
- Supports many assets across Ethereum, Polygon, Arbitrum, Optimism, etc.
- Features: flash loans (borrow without collateral for one transaction — used by advanced traders), variable/stable rates, delegation of credit.
- Very user-friendly interface.

### Compound
- The protocol that kicked off "DeFi Summer" in 2020.
- Simple and battle-tested.
- Has its own governance token (COMP) rewarded to users.

### MakerDAO (and DAI)
- A bit different: you deposit collateral (ETH, wstETH, etc.) to mint DAI (a decentralized stablecoin).
- You're effectively borrowing DAI against your collateral.
- One of the oldest and most decentralized protocols.
- DAI aims to stay pegged to $1.

### Morpho
- A newer "optimizer" built on top of Aave and Compound.
- Matches lenders and borrowers peer-to-peer for better rates.

### Others
- **Spark Protocol** — DAI-focused lending from the Maker team.
- **Radiant Capital** — Cross-chain lending.
- **Benqi** (on Avalanche), **Tectonic** (Cronos) — chain-specific versions.

## Example: Lending on Aave (Step by Step)

1. Go to app.aave.com
2. Connect your wallet and switch to a supported network (e.g., Polygon for low fees).
3. Choose an asset you own (e.g., USDC).
4. Click "Supply" → enter amount → approve + supply transaction.
5. You now see your supply balance growing with interest.
6. To withdraw: click "Withdraw" anytime.

Borrowing is similar: supply collateral first, then borrow another asset.

## Benefits of DeFi Lending

- Earn real yield on stablecoins (often 3–10%+ vs. near 0% in banks).
- No credit checks — just need collateral.
- Global and permissionless.
- Transparent rates and rules.

## Risks to Understand

- **Liquidation risk** (for borrowers): If collateral drops too fast (e.g., ETH crashes), your position gets liquidated and you pay a penalty.
- **Smart contract risk**: Bugs or hacks can lead to loss (though top protocols are heavily audited).
- **Variable rates**: Your lending APY can drop suddenly.
- **Opportunity cost**: Your collateral is locked while borrowing.

**Pro tip**: Use tools like DeFiLlama or Zapper to track health factors and rates across protocols.

## Quick Comparison Table

| Protocol     | Best For                          | Key Feature                     | Chains Supported              |
|--------------|-----------------------------------|----------------------------------|-------------------------------|
| Aave        | Most users, flash loans           | Stable + variable rates         | Ethereum + many L2s           |
| Compound    | Simplicity, governance            | Original yield farming protocol | Ethereum, some L2s            |
| MakerDAO    | Decentralized stablecoin (DAI)    | Most decentralized              | Mainly Ethereum               |
| Morpho      | Best rates                        | Peer-to-peer matching           | Ethereum                      |

DeFi lending lets you earn passive income or get leverage — but always start small and understand the risks.

Next: **Yield Farming & Liquidity Providing** — how to earn even higher rewards (with more risk).
