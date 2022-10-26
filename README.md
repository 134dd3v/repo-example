# RageTrade contest details

- `<UPDATE THIS>` 8,000 USDC main award pot
- Join [Sherlock Discord](https://discord.gg/MABEWyASkp)
- Submit findings using the issue page in your private contest repo (label issues as med or high)
- [Read for more details](https://docs.sherlock.xyz/audits/watsons)
- Starts `<UPDATE THIS>` September 15, 2022 15:00 UTC
- Ends `<UPDATE THIS>` September 18, 2022 21:00 UTC

# Resources

`<UPDATE THIS>`

- [Docs](https://harpie.gitbook.io/welcome-to-the-harpie-docs)
- [Harpie Contracts @ 97083d](https://github.com/Harpieio/contracts/tree/97083d7ce8ae9d85e29a139b1e981464ff92b89e)
- [Smart Contract Overview](https://harpie.notion.site/Smart-Contract-Overview-b95414ffafe243519eda539606c3f982)

# Audit scope

The following contracts in the [RageTrade/dn-lb-vault@e940de](https://github.com/RageTrade/dn-lb-vault/tree/e940de5ea56d1030f1abd5e57f8c7f0b8c449ec5) repo are in scope.

- `ERC4626/ERC4626Upgradeable.sol`
- `libraries/DnGmxJuniorVaultManager.sol`
- `libraries/FeeSplitStrategy.sol`
- `libraries/SafeCast.sol`
- `periphery/WithdrawPeriphery.sol`
- `vaults/DnGmxBatchingManager.sol`
- `vaults/DnGmxJuniorVault.sol`
- `vaults/DnGmxSeniorVault.sol`

# About RageTrade DN LB Vault

`<UPDATE THIS>`

> source: [Harpie Docs](https://harpie.gitbook.io/welcome-to-the-harpie-docs/about/whitepaper#how-it-works-summary)

Harpie identifies malicious transactions by having users set up a "trusted network" of protocols and peers. If your wallet sends a transfer to someone outside this trusted network, we stop that transaction from happening.

We are able to eliminate these malicious transfers even after they're transmitted on-chain with an advanced strategy called frontrunning. When a malicious transfer or approval is detected, we move your funds to a noncustodial vault before the transaction can confirm. By paying a higher gas fee, we have the ability to move your funds to the vault before the hacker can move your funds to their own wallet.
