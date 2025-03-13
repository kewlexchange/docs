# Swap

The project features a multi-chain decentralized exchange (DEX), a pivotal component offering seamless trading across various blockchain networks. Key features include:

1. **Cross-Chain Trading**: Enables transactions across different blockchains.
2. **Liquidity Aggregation**: Gathers liquidity from various sources for optimal trading.
3. **Low Transaction Fees**: Offers competitive fees for trading activities.
4. **High Security**: Implements robust security measures to protect user assets.
5. **User-Friendly Interface**: Designed for ease of use, catering to both beginners and experienced traders.
6. **Decentralized Governance**: Allows community participation in decision-making processes.

The future vision is to establish this DEX as a leading platform in the decentralized finance space, promoting accessibility, security, and efficiency in trading across multiple blockchains.

## Supported Pair Types

**KEWL features two types of Liquidity Pairs, each with its own swap curve:**

* **Volatile (Uni V2)**: This is the most common type of pair where tokens are paired with equal weights in terms of dollar value.
  * ![Volatile Swap formula\*\*](https://latex.codecogs.com/svg.image?%5Clarge%20%5Ccolor%7BWhite%7Dx*y=k)
* **Stable (Correlated)**: These pairs use an optimized curve designed specifically for correlated assets like stablecoins. The curve features a modified invariant that allows for highly efficient swaps with minimal slippage between tokens of similar value.
  * \
