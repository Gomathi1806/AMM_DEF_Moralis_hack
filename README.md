# `ethereum-boilerplate`

> Fully Typescript ready NextJS components for fast building dApps without running own backend

🚀DEMO: https://eth-boilerplate.vercel.app/

This boilerplate is built with [Moralis](https://moralis.io?utm_source=github&utm_medium=readme&utm_campaign=ethereum-boilerplate)




# ⭐️ `Star us`

If this boilerplate helps you build Ethereum dapps faster - please star this project, every star makes us very happy!

# 🤝 `Need help?`

If you need help with setting up the boilerplate or have other questions - don't hesitate to write in our community forum and we will check asap. [Forum link](https://forum.moralis.io/t/ethereum-boilerplate-questions/3951/86). The best thing about this boilerplate is the super active community ready to help at any time! We help each other.

# 🚀 `Quick Start`

📄 Clone or fork `ethereum-boilerplate`:

```sh
git clone https://github.com/ethereum-boilerplate/ethereum-boilerplate.git
```

💿 Install all dependencies:

```sh
cd ethereum-boilerplate
yarn install
```

✏ Rename `.env.local.example` to `.env.local` and provide required data. Get your Web3 Api Key from the [Moralis dashboard](https://admin.moralis.io/):


🚴‍♂️ Run your App:

```sh
yarn start
```

# 🧭 `Table of contents`
- [`ethereum-boilerplate`](#ethereum-boilerplate)
- [🚀 Quick Start](#-quick-start)
- [🧭 Table of contents](#-table-of-contents)
- [🏗 Ethereum Components](#-ethereum-components)
  - [`<NFTBalances />`](#nftbalances-)
  - [`<ERC20Balances />`](#erc20balances-)
  - [`<ERC20Transfers />`](#erc20transfers-)
  - [`<NFTTransfers />`](#nfttransfers-)
  - [`<Transactions />`](#transactions-)

# 🏗 Ethereum Components

### `<NFTBalances />`


location: `src/component/templates/balances/NFT/NFTBalances.tsx`

🎨 `<NFTBalances />` : displays the the user's balances. Uses Moralis Evm API (does not require an active web3 provider).

### `<ERC20Balances />`


location: `src/component/templates/balances/ERC20/ERC20Balances.tsx`

💰 `<ERC20Balances />` : displays the user's ERC20 balances. Uses Moralis Evm API (does not require an active web3 provider).

### `<ERC20Transfers />`


location: `src/component/templates/transfers/ERC20/ERC20Transfers.tsx`

💰 `<ERC20Transfers />` : displays the user's ERC20 transfers. Uses Moralis Evm API (does not require an active web3 provider).

### `<NFTTransfers />`



location: `src/component/templates/transfers/NFT/NFTTransfers.tsx`

🎨 `<NFTTransfers />` : displays the user's NFT transfers. Uses Moralis Evm API (does not require an active web3 provider).

### `<Transactions />`


location: `src/component/templates/transactions/Transactions.tsx`

💰 `<Transactions />` : displays the user's transactions. Uses Moralis Evm API (does not require an active web3 provider).

