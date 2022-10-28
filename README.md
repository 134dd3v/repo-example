# RageTrade contest details

- `<UPDATE THIS>` 8,000 USDC main award pot
- Join [Sherlock Discord](https://discord.gg/MABEWyASkp)
- Submit findings using the issue page in your private contest repo (label issues as med or high)
- [Read for more details](https://docs.sherlock.xyz/audits/watsons)
- Starts `<UPDATE THIS>` September 15, 2022 15:00 UTC
- Ends `<UPDATE THIS>` September 18, 2022 21:00 UTC

# Resources

`<UPDATE THIS>`

- [RageTrade/dn-lb-vault @ e940de](https://github.com/RageTrade/dn-lb-vault/tree/e940de5ea56d1030f1abd5e57f8c7f0b8c449ec5)

# Audit scope

The following contracts in the [RageTrade/dn-lb-vault @ e940de](https://github.com/RageTrade/dn-lb-vault/tree/e940de5ea56d1030f1abd5e57f8c7f0b8c449ec5) repo are in scope.

- `ERC4626/ERC4626Upgradeable.sol`
- `libraries/DnGmxJuniorVaultManager.sol`
- `libraries/FeeSplitStrategy.sol`
- `libraries/SafeCast.sol`
- `periphery/WithdrawPeriphery.sol`
- `vaults/DnGmxBatchingManager.sol`
- `vaults/DnGmxJuniorVault.sol`
- `vaults/DnGmxSeniorVault.sol`

# About RageTrade DN LB Vault

> source: [Harpie Docs](https://harpie.gitbook.io/welcome-to-the-harpie-docs/about/whitepaper#how-it-works-summary) `<UPDATE THIS>`

RageTrade's DN LB Vaults are set of contracts that allow any users to pool in funds for providing liquidity on GMX in a delta neutral way while earning ETH rewards on GMX. This vault operates on-chain for minimising exposure on ETH and BTC by performing a short on Aave + Uniswap.

DeFi Protocols used:
- GMX (for liquidity provision)
- Aave (for borrowing assets to short)
- Balancer (for leveraging Aave borrow)
- Uniswap (for swapping)

## Steps to run the tests:

Node v16, Hardhat v2.11

1. Clone the repo
2. `yarn install`
3. `yarn patch-package`
4. Create .env file with env var `ALCHEMY_KEY` (use http://alchemy.com)
5. `yarn test`
