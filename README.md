# Moralis Wallet API

With [Moralis' Wallet API](https://moralis.io/api/wallet/), you can create secure, efficient, and feature-rich Web3 wallets for your dApps. Whether you are building decentralized exchanges, NFT marketplaces, portfolio trackers, DAOs, or web3 gaming platforms, Moralis provides the tools you need to succeed.

In this article, you will explore the Moralis Wallet API and how it can empower your dApp wallet development.

Select what you want to achieve:

* [Get Wallet Details](#get-wallet-details)
* [Get Native Balance](#get-native-balance)
* [Get NFTs](#get-nfts)
* [Get Tokens](#get-tokens)
* [Get Transactions](#get-transactions)
* [Get Transfers](#get-transfers)
* [Domains Lookups](#domain-lookups)

## Quick Start to Wallet API

1. [Get an API key](https://docs.moralis.io/web3-data-api/evm/get-your-api-key)
2. Explore the [documentation guides](https://docs.moralis.io/web3-data-api/evm/wallet-api/)
3. Explore the [full list of endpoints](https://docs.moralis.io/web3-data-api/evm/reference)

### Get Wallet Details

| No. | Method                           | Description                           | API Reference                                                                                                                   | URL                                                                                                                             |
|-----|----------------------------------|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| 1   | `getChainActivityByWallet`       | Get chain activity by wallet          | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/wallet-api/get-chain-activity-by-wallet)                                 | [https://deep-index.moralis.io/api/v2.2/wallets/:address/chains](https://deep-index.moralis.io/api/v2.2/wallets/:address/chains)                                                                       |

### Get Native Balance

| No. | Method                           | Description                           | API Reference                                                                                                                   | URL                                                                                                                             |
|-----|----------------------------------|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| 2   | `getNativeBalanceByWallet`       | Get native balance by wallet          | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/get-native-balance)                                                       | [https://deep-index.moralis.io/api/v2.2/:address/balance](https://deep-index.moralis.io/api/v2.2/:address/balance)                                                                       |
| 3   | `getNativeBalancesForAddresses`  | Get native balance for multiple wallets | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/get-native-balances-for-addresses)                                     | [https://deep-index.moralis.io/api/v2.2/wallets/balances](https://deep-index.moralis.io/api/v2.2/wallets/balances)                                                                  |

### Get NFTs

| No. | Method                           | Description                           | API Reference                                                                                                                   | URL                                                                                                                             |
|-----|----------------------------------|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| 4   | `getNFTsByWallet`                | Get NFTs by wallet                    | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/wallet-api/get-nfts-by-wallet)                                           | [https://deep-index.moralis.io/api/v2.2/:address/nft](https://deep-index.moralis.io/api/v2.2/:address/nft)                                                                                |
| 5   | `getNFTCollectionsByWallet`      | Get NFT collections by wallet         | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/wallet-api/get-nft-collections-by-wallet)                                 | [https://deep-index.moralis.io/api/v2.2/:address/nft/collections](https://deep-index.moralis.io/api/v2.2/:address/nft/collections)                                                                      |

### Get Tokens

| No. | Method                           | Description                           | API Reference                                                                                                                   | URL                                                                                                                             |
|-----|----------------------------------|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| 6   | `getTokenBalancesByWallet`       | Get ERC20 token balance by wallet     | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/wallet-api/get-token-balances-by-wallet)                                   | [https://deep-index.moralis.io/api/v2.2/:address/erc20](https://deep-index.moralis.io/api/v2.2/:address/erc20)                                                                      |

### Get Transactions

| No. | Method                           | Description                           | API Reference                                                                                                                   | URL                                                                                                                             |
|-----|----------------------------------|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| 7   | `getDecodedTransactionsByWallet` | Get decoded transactions by wallet    | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/wallet-api/get-decoded-transactions-by-wallet)                             | [https://deep-index.moralis.io/api/v2.2/:address/verbose](https://deep-index.moralis.io/api/v2.2/:address/verbose)                                                                |
| 8   | `getNativeTransactionsByWallet`   | Get native transactions by wallet      | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/wallet-api/get-transactions-by-wallet)                                     | [https://deep-index.moralis.io/api/v2.2/:address](https://deep-index.moralis.io/api/v2.2/:address)                                                                 |

### Get Transfers

| No. | Method                           | Description                           | API Reference                                                                                                                   | URL                                                                                                                             |
|-----|----------------------------------|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| 9   | `getWalletNFTTransfers`          | Get NFT transfers by wallet           | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/wallet-api/get-wallet-nft-transfers)                                  | [https://deep-index.moralis.io/api/v2.2/:address/nft/transfers](https://deep-index.moralis.io/api/v2.2/:address/nft/transfers)                                                                         |
| 10  | `getWalletTokenTransfers`         | Get ERC20 token transfers by wallet   | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/wallet-api/get-wallet-token-transfers)                                | [https://deep-index.moralis.io/api/v2.2/:address/erc20/transfers](https://deep-index.moralis.io/api/v2.2/:address/erc20/transfers)                                                                        |

### Domain Lookups

| No. | Method                           | Description                           | API Reference                                                                                                                   | URL                                                                                                                             |
|-----|----------------------------------|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| 11  | `resolveAddress`                 | ENS Lookup by Address                  | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/wallet-api/resolve-address)                                                | [https://deep-index.moralis.io/api/v2.2/resolve/:address/reverse](https://deep-index.moralis.io/api/v2.2/resolve/:address/reverse)                                                                                |
| 12  | `resolveENSDomain`               | ENS Lookup By Domain                  | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/wallet-api/resolve-ens-domain)                                          | [https://deep-index.moralis.io/api/v2.2/resolve/ens/:domain](https://deep-index.moralis.io/api/v2.2/resolve/ens/:domain)                                                                            |
| 13  | `resolveAddressToDomain`         | Unstoppable Lookup by Address          |

 [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/wallet-api/resolve-address-to-domain)                                  | [https://deep-index.moralis.io/api/v2.2/resolve/:address/domain](https://deep-index.moralis.io/api/v2.2/resolve/:address/domain)                                                                    |
| 14  | `resolveDomain`                  | Unstoppable Lookup By Domain           | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/wallet-api/resolve-domain)                                           | [https://deep-index.moralis.io/api/v2.2/resolve/:domain](https://deep-index.moralis.io/api/v2.2/resolve/:domain)                                                                                |
| 15  | `getWalletStats`                 | Get wallet stats                       | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/wallet-api/get-wallet-stats)                                           | [https://deep-index.moralis.io/api/v2.2/wallets/:address/stats](https://deep-index.moralis.io/api/v2.2/wallets/:address/stats) |


## Native Balances

- Access both current and historical native balances for any wallet.
- Stay up to date with token balances, prices, and user activity.
- Filter out spam tokens for a cleaner user experience.

## NFTs

- Showcase the most comprehensive wallet history across NFTs, token transfers, native transactions, and internal transactions.
- Fetch all NFTs and collections held by a wallet, complete with enriched metadata and optimized images.

## ERC20s

- Look up current ERC20 token holdings, including real-time prices.
- Calculate a wallet's USD net worth.

## User experience Labels

- Improve user experience by providing context for wallet activity.
- Stay informed about your users' activity on your Dapp.

## Account Abstraction Enabled

Moralis' Wallet API natively supports Account Abstraction (ERC-4337). This feature enables developers to retrieve smart contract account balances, transaction details, gas fees, and much more. It's a powerful tool for interacting with smart contracts and enhancing your Dapp's capabilities.

## Chains

The Wallet API supports a wide range of EVM chains, including Ethereum, BNB Chain, Polygon, Avalanche, and more. You can seamlessly integrate these chains into your Dapp using the Wallet API, providing your users with a versatile and efficient experience.

## ⭐️ Star us

If this Wallet API helps you - please star this project, every star makes us very happy!

## 🤝 Need help?

If you need help with using the Wallet API or have other questions - don't hesitate to write in our community forum and we will check asap. [Forum link](https://forum.moralis.io/). We are answering questions 24/7
