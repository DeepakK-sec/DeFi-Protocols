# Yield Farming & Liquidity Providing

Yield farming (often just called "farming") and liquidity providing are ways to earn extra rewards in DeFi — usually much higher than simple lending — by helping protocols function.

In simple terms: you put your tokens to work in places where they're needed, and you get paid for it.

## Liquidity Providing: The Foundation

Most yield farming starts with **providing liquidity** to a DEX (like Uniswap or Curve).

**How it works:**
- You deposit a pair of tokens into a liquidity pool (e.g., ETH and USDC in equal value).
- Traders use your pool to swap — every trade pays a small fee (usually 0.05%–0.3%).
- Those fees are shared among all liquidity providers (LPs) proportional to your share.

You get **LP tokens** (liquidity provider tokens) as a receipt — these represent your share of the pool.

**Reward:** Trading fees (steady but usually modest, like 5–20% APY on popular pairs).

## Yield Farming: Supercharging the Rewards

Protocols want lots of liquidity, so they offer **extra incentives** on top of trading fees.

This is yield farming:
- A protocol (or its governance) pays farmers in their own token (e.g., UNI, CRV, SUSHI, BAL).
- You stake your LP tokens into a "farm" or "stake pool" to earn these extra rewards.
- Rewards can be huge at launch (100%+ APY) but usually drop over time.

**Example flow:**
1. Deposit ETH + USDC into Uniswap pool → get UNI-V3 LP tokens.
2. Stake those LP tokens on a farming site → earn extra tokens (maybe from another project incentivizing that pool).

This is where people made (and lost) a lot during 2020–2021 "DeFi Summer."

## Popular Places for Yield Farming

- **Uniswap** → Basic LP fees (no native farming anymore, but others incentivize Uniswap pools).
- **Curve Finance** → Very popular for stablecoin pools. Low impermanent loss + CRV rewards + "gauge" voting.
- **Convex Finance** → Built on Curve — lets you earn boosted CRV rewards without locking.
- **Yearn.finance** → Automated yield optimizer ("vaults"). You deposit, Yearn moves your funds to the best opportunities.
- **Beefy, Harvest, Autofarm** → Auto-compounding farms on many chains.
- **Pendle, Aura, Balancer** → More advanced strategies with token incentives.

## Key Risks — This Is the Riskiest Part of DeFi

Yield farming can offer high returns, but the risks are real:

### 1. **Impermanent Loss (IL)**
   - The biggest one for LPs.
   - If the price of tokens in your pool moves a lot, you end up with less value than if you had just held the tokens.
   - Example: ETH price doubles → pool rebalances → you have more USDC, less ETH → you miss out on ETH gains.
   - Stablecoin pools (Curve) have very low IL. Volatile pairs (ETH/USDC) can have high IL.

### 2. **Token Reward Risk**
   - Farming rewards are often paid in the protocol's own token.
   - These tokens can crash in price → high APY looks great until the reward token loses 90% value.

### 3. **Smart Contract Risk**
   - More complex farms = more code = higher chance of bugs or hacks.

### 4. **Rug Pulls**
   - Some new farms are outright scams — high rewards to attract money, then devs drain it.

**Rule of thumb:** Higher APY usually = higher risk.

## Quick Comparison: Simple vs. Advanced

| Activity                  | Typical APY Range | Risk Level          | Best For                          |
|---------------------------|------------------|---------------------|-----------------------------------|
| Just holding              | 0%               | Low                 | Long-term believers               |
| Lending (Aave/Compound)   | 2–10%            | Low–Medium          | Stable yield                      |
| LP on stable pools (Curve)| 5–20% + rewards  | Medium              | Balanced risk/reward              |
| Farming volatile pairs    | 20–200%+         | High–Very High      | Experienced users chasing alpha   |
| Yearn vaults              | 5–30%            | Medium              | Set-it-and-forget-it optimization |

## Tips If You Want to Try It

1. Start small — use money you can afford to lose.
2. Prefer established protocols (Curve + Convex, Yearn, Aave).
3. Use tools like:
   - DeFiLlama.com (Yield section) — see real current APYs.
   - Zapper.fi or Zerion — track your positions.
4. Watch for impermanent loss calculators before depositing.
5. Auto-compound when possible (higher effective yield).

## Recap

Liquidity providing earns you trading fees.  
Yield farming adds extra token rewards on top — powerful but risky.

Many people use yield farming to boost returns, but most long-term DeFi users stick to simpler lending or stable pools once the hype dies down.

Next up: **Stablecoins** — the "cash" of DeFi that tries to stay worth $1.
