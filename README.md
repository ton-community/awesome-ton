# Awesome TON (The Open Network)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Twitter](https://img.shields.io/twitter/follow/ton_blockchain?style=social)](https://twitter.com/ton_blockchain)
[![Telegram](https://img.shields.io/badge/telegram-TON%20Dev%20Chat-blue?logo=telegram)](https://t.me/tondev_eng)

<!---
ADD link to Tact language community in the future https://twitter.com/tact_language
--->

A curated list of remarkable libraries, tools, services, protocols, and smart contracts related to TON.

### Table of Contents
- [APIs](#apis)
- [Authorization SDKs](#authorization-sdks)
- [Smart Contract Examples](#smart-contract-examples)
- [Endpoints](#endpoints)
- [Explorers](#explorers)
- [Frameworks](#frameworks)
- [Funds](#funds)
- [Languages and SDKs](#languages-and-sdks)
  - [JavaScript](#javascript)
  - [Go](#go)
  - [Kotlin / Java](#kotlin--java)
  - [Python](#python)
- [Launchpads](#launchpads)
- [Decentralized Exchanges (DEX)](#decentralized-exchanges-dex)
- [Bridges](#bridges)
- [Monitoring](#monitoring)
- [Fungible Tokens (Jettons)](#fungible-tokens-jettons)
- [Non-Fungible Tokens (NFTs)](#non-fungible-tokens-nfts)
- [Staking](#staking)
- [Telegram Web Apps (TWAs)](#telegram-web-apps-twas)
- [TonLib SDK](#tonlib-sdk)
- [Utilities](#utilities)
- [UX/UI](#uxui)
- [Wallets](#wallets)
- [Testnet](#testnet)
- [Contribution Guidelines](#contribution-guidelines)
- [License](#license)

## APIs

* [TonCenter.com](https://toncenter.com/) — Fast and reliable HTTP API for The Open Network.
* [TonApi.io](https://tonapi.io/) — API that allows working with indexed blockchain information.
* [TonConsole.com](https://tonconsole.com/) — one place with powerful API and deep commercial integrations.

## Authorization SDKs

To add a login button to your website or WebApp use these SDKs:

* [ton-connect/sdk](https://github.com/ton-connect/sdk) — unified authentication standard for TON Ecosystem.
* [delab-team/connect](https://github.com/delab-team/connect) - SDK, which combines multiple protocols in one modal

## Smart Contract Examples

* [Nominator Pool](https://github.com/EmelyanenkoK/nominator_pool) - WIP nominator pool
* [Multisig](https://github.com/akifoq/multisig) - original multisig implementation
* [Ton Starter Boilerplate](https://github.com/ton-defi-org/tonstarter-contracts) - great place to start learning by example
* [JuiceBox](https://github.com/Gajesh2007/Juicebox_TON) - Crowdfund Your DAO 
* [Coin Flip](https://github.com/Gajesh2007/CoinFlip_TON) - Flip & Try Your Luck
* [MasterChef](https://github.com/Gajesh2007/MasterChef) - Stake & Farm
* [Ton-By-Example](https://github.com/Gajesh2007/ton-by-example) - Bundle of TON Smart Contracts

## Endpoints
* [GetBlock Nodes](https://getblock.io/nodes/ton/) — connect and test your dApp to TON using GetBlocks Nodes.

## Explorers

* [3xpl.com/ton](https://3xpl.com/ton) - Fastest ad-free universal block explorer
* [tonwhales.com/explorer](https://tonwhales.com/explorer) - User friendly explorer and with detailed technical info
* [ton.sh](https://ton.sh) - official blockchain explorer, supports only recent transactions
* [explorer.toncoin.org](https://explorer.toncoin.org) - Advanced explorer for developers
* [ton.cx](https://ton.cx) - Another advanced explorer for devlopers
* [tonscan](https://tonscan.org/) - another official blockchain explorer
* [tonscanplus](https://chrome.google.com/webstore/detail/tonscan%2B/egonpnmjojlaogggbjklkbkflgipljpd/related) - Google Chrome extencion and [the community-driven address book](https://github.com/menschee/tonscanplus/blob/main/data.json). Apart from name tags, the extension enables one to choose a view mode as well as sort out transactions by the number of Toncoin. The extension is now [open source](https://github.com/menschee/tonscanplus) and ready for feedback. Feel free to report any bugs via [bot](https://t.me/thedailytonbot)
* [tonapi](https://tonapi.io/) - Convenient explorer
* [dton](https://dton.io) - Good explorer for developers
* [TON Searcher](https://ton.app/explorers/1644844142) - Simple open-source explorer
* [TonMoon Explorer](https://ton.app/explorers/tonmoon-explorer) - Search for addresses, shops, and NFT
* [TON NFT EXPLORER](https://ton.app/explorers/explorer-ton-nft) - Explore TON based NFT collections
* [TON Explorer](https://ton.app/explorers/tonexp) - Fast, reliable, user-friendly explorer
* [Tegro TON Explorer](https://ton.app/explorers/youton-explorer) - Tegro TON Explorer — The Open Network
* [Explorer Bot](https://ton.app/explorers/tonexpbot) - First Bot-explorer
* [tonobserver](https://ton.app/explorers/tonobserver) - TON explorer using indexing
* [TON Scan Mobile](https://ton.app/explorers/tonscanmobile) - First mobile explorer for TON
* [TonDomenBot](https://ton.app/explorers/ton-domen-bot) - Бот для мониторинга доменов в TON

## Frameworks
* [Blueprint](https://github.com/ton-community/blueprint) — A development environment for writing, testing, and deploying smart contracts.
* [Rift](https://github.com/sky-ring/rift) - Python framework for building smart contracts.

## Funds
* [Toncoin Fund](https://www.toncoin.fund/)
* [TAV Fund](https://tav-incubation.com/)

## Languages and SDKs

### JavaScript

#### SDKs
* [ton-core/ton](https://github.com/ton-core/ton) — Cross-platform client for TON blockchain, by ton-core
* [toncenter/tonweb](https://github.com/toncenter/tonweb) — Cross-platform client for TON blockchain, by TonCenter
* [@tegro/ton3-client](https://github.com/TegroTON/ton3-client) — JS ton3-client for tonhold API, by TonHold
* [nns2009/ton-payment-tracker](https://github.com/nns2009/ton-payment-tracker) — Ton Payment Tracker
* [ton-x](https://npm.im/ton-x) — a library that allows you to add Tonhub authorization to your project
* [@tonapps/tonconnect-server](https://npm.im/@tonapps/tonconnect-server) — a library that allows you to add Tonkeeper authorization to your project
* [tonRocket-api-sdk](https://github.com/danya7423/tonRocket-api-sdk) — library for easy work with the TON Rocket API

#### Examples
* [Create a key pair and a wallet](https://github.com/toncenter/examples/blob/main/common.js)
* [Accepting deposits to a single wallet](https://github.com/toncenter/examples/blob/main/deposits-single-wallet.js)
* [Accepting deposits to multiple wallets](https://github.com/toncenter/examples/blob/main/deposits-multi-wallet.js) (tonweb)
* [Withdrawal processing](https://github.com/toncenter/examples/blob/main/withdrawals.js)
* [Payment Channels Example](https://github.com/toncenter/payment-channels-example/blob/main/index.js)
* [TON Bridge front-end](https://github.com/ton-blockchain/bridge)
* [Web Wallet source code](https://github.com/toncenter/ton-wallet)

### Go

#### SDKs
* [tonutils-go](https://github.com/xssnick/tonutils-go) — Go utils for TON blockchain.
* [tongo](https://github.com/startfellows/tongo) — Golang primitives for working with TON.

#### Examples
* [10+ examples from xssnick/tonutils-go](https://github.com/xssnick/tonutils-go/tree/master/example)


### Kotlin / Java
* [ton-kotlin](https://github.com/andreypfau/ton-kotlin) — Kotlin SDK for TON blockchain


### Python

#### SDKs
* [psylopunk/pytonlib](https://github.com/psylopunk/pytonlib) — Python SDK
* [toncenter/pytonlib](https://github.com/toncenter/pytonlib) — Python SDK
* [tonfactory/tonsdk](https://github.com/tonfactory/tonsdk) — Analogue of the tonweb js library
* [tonrocketapisdk](https://github.com/danya7423/tonRocket-api-sdk-py) — library for easy work with the TON Rocket API

#### Examples
* [psylopank/pytonlib examples](https://github.com/psylopunk/pytonlib/tree/main/examples)
* [Transfer NFT & Jettons by creating a transfer message from an owner wallet](https://github.com/tonfactory/tonsdk#transfer-nft--jettons-by-creating-a-transfer-message-from-an-owner-wallet)
* [Create mnemonic, init wallet class, create external message to deploy the wallet](https://github.com/tonfactory/tonsdk#create-mnemonic-init-wallet-class-create-external-message-to-deploy-the-wallet)
* [Accept payments using Telegram bot](https://www.tonspace.co/develop/dapps/payment-processing/accept-payments-in-a-telegram-bot) (Python with Aiogram)

## Launchpads
* [Tonstarter](https://tonstarter.com/) — Launchpad for projects

## Decentralized Exchanges (DEX)
* [STON.fi](http://app.ston.fi) — an AMM DEX for the TON Blockchain. 
* [DeDust](http://dedust.io/dex/swap) — a DEX for the TON Blockchain supporting the import of any tokens.
* [TonSwap](http://tonswap.org) — an AMM DEX for the TON Blockchain developed by Mint.xyz.
* [Tegro.Finance](http://tegro.finance) — a DEX for the TON Blockchain.
* [Megaton Finance](https://megaton.fi) - Deposit Crypto, reap rewards every day

## Bridges
* [Orbit Bridge](https://bridge.orbitchain.io) - Fast and secure way for token conversion

## Monitoring
* [TON Grafana](https://tonmon.xyz/) - Blockchain metrics
* [TON Notify Bot](https://t.me/TONNotifyBot) - Instant notifications about transfer coins of the TON address in Telegram. Link to [GitHub](https://github.com/tonbase/ton-notify-bot)
* [TOKEN INSIDE](https://t.me/token_inside) - Monitoring of new jettons, meta data changes and other events

## Fungible Tokens (Jettons)

* [Jetton Live](https://jetton.live/) - service for minting arbitrary jettons
* [Tonox Minter](https://minter.tonox.exchange/) - another service for minting arbitrary jettons
* [Jettons Standard](https://github.com/ton-blockchain/TEPs/blob/master/text/0074-jettons-standard.md)
* [Smart Contracts Implementation (FunC)](https://github.com/ton-blockchain/token-contract)
* [Jetton.Live](https://jetton.live/) — open-source Jetton Deployer dApp
* [Jetton Deployer](https://github.com/ton-defi-org/jetton-deployer-contracts) Contracts (FunC, TL-B)
* [Jetton Deployer](https://github.com/ton-defi-org/jetton-deployer-webclient) WebClient (React, TypeScript)
* [Scaleton](http://scaleton.io/) — see your custom token balances.
* [@tegro/ton3-client](https://github.com/TegroTON/ton3-client#jettons-example) — SDK to query information about Jettons.
* [WTON Gateway](https://wton.dev/) - Your one and only, Gateway to WTON

## Non-Fungible Tokens (NFTs)
* [NFT Standard](https://github.com/ton-blockchain/TEPs/blob/master/text/0062-nft-standard.md)
* [NFTRoyalty Standard Extension](https://github.com/ton-blockchain/TEPs/blob/master/text/0066-nft-royalty-standard.md)
* [Smart Contracts Implementation (FunC)](https://github.com/ton-blockchain/token-contract/)
* [GetGems NFT, Sale, Auctions smart contracts (FunC)](https://github.com/getgems-io/nft-contracts)
* [NFT Deployer](https://github.com/tondiamonds/ton-nft-deployer) by TON Diamonds (TypeScript, no comments)
* [NFT Minter Example](https://github.com/ton-foundation/token-contract/tree/main/nft/web-example) (JavaScript, with comments)
* [NFT Minter using React](https://github.com/tonbuilders/tonbuilders-minter) (React, no comments)
* [NFT Deployer](https://github.com/anomaly-guard/nft-deployer) (Python, with comments)
* [LiberMall/tnt](https://github.com/LiberMall/tnt) — TNT is an all-in-one command line tool to query, edit, and mint new Non-Fungible Tokens on The Open Network

## Staking
* [Ton Whales Staking](https://tonwhales.com/staking) - staking service with the 50 TON minimal deposit
* [Red Ziccurat bot](https://t.me/red_ziccurat_staking_bot) - official staking from redcompany.team

## Telegram Web Apps (TWAs)
* [Telegram WebApps Documentation](https://core.telegram.org/bots/webapps) — full description on Telegram website
* [ton-defi-org/tonstarter-twa](https://github.com/ton-defi-org/tonstarter-twa) — template for a new TWA interacting with the TON.
* [twa-dev/boilerplate](https://github.com/twa-dev/Boilerplate) — another boilerplate for a new TWA.
* [twa-dev/sdk](https://github.com/twa-dev/sdk) — npm package for TWA SDK.
* [twa-dev/Mark42](https://github.com/twa-dev/Mark42) — Mark42 is a simple lightweight tree-shakable UI library for TWA.

## TonLib SDKs

TonLib was one of the first libraries for working with TON blockchain:

* [C++ TonLib](https://github.com/ton-blockchain/ton/tree/master/example/cpp)
* [Python TonLib wrapper](https://github.com/toncenter/pytonlib)
* [Golang TonLib wrapper](https://github.com/ton-blockchain/tonlib-go)
* [Java TonLib wrapper (JNI)](https://github.com/ton-blockchain/tonlib-java)
* [tonlib-xcframework](https://github.com/labraburn/tonlib-xcframework) - builder for Apple that generates .xcramework for all architectures
* [labraburn/SwiftyTON](https://github.com/labraburn/SwiftyTON) - native Swift wrapper for tonlib with async/await
* [labraburn/node-tonlib](https://github.com/labraburn/node-tonlib) - C++ addon for NodeJS to work with tonlibjson

### Examples
* [Desktop standard wallet (C++ and Qt)](https://github.com/ton-blockchain/wallet-desktop)
* [Android standard wallet (Java)](https://github.com/ton-blockchain/wallet-android)
* [iOS standard wallet (Swift)](https://github.com/ton-blockchain/wallet-ios)
* [TonLib CLI (C++)](https://github.com/ton-blockchain/ton/blob/master/tonlib/tonlib/tonlib-cli.cpp)

## Utilities

* [vaniton](https://github.com/AntonMeep/vaniton) - Vanity address generator for The Open Network's standard wallets
* [custon](https://github.com/TON-NFT/custon) - User-friendly generator of custom TON wallet addresses written in JS
* [TON Web Archive Web Client](https://feliciss.itcouldbewor.se/tonwebarchivewebclient) - TON Web Archive is an app to archive websites from Clearnet to TON Darknet with .ton domains.

## UX/UI
* [TON Design System](https://github.com/designervoid/ton-design-system) - Design system which provides [TON Brand Assets](https://ton.org/brand-assets) as Atom CSS

## Wallets
* [Ton iOS](https://apps.apple.com/by/app/toncoin-wallet/id1560210939) - Official iOS wallet
* [Ton Android](https://play.google.com/store/apps/details?id=ton.coin.wallet) - Official Android wallet
* [TON Wallet](https://wallet.ton.org/) - Official Web Wallet
* [ton-cli](https://github.com/ex3ndr/ton-cli) - TON CLI client
* [Tonkeeper](https://tonkeeper.com) - Wallet for store, send, and receive Toncoin on The Open Network
* [TonHub](https://tonhub.com) - Also good mobile wallet that allows you send, receive and stake Toncoin with Tonwhales staking pool
* [MyTonWallet](https://mytonwallet.io) - Web wallet and browser extension for TON – with support of tokens, NFT, TON DNS, TON Sites, TON Proxy, and TON Magic
* [Juston](https://juston.io) - Wallet has a built-in browser that can open sites in the .ton domain zone without the need for settings. Available on iOS.
* [Coin98 Wallet](https://wallet.coin98.com) - A mobile and browser extension wallet with multi-chain support.


## Testnet

### Faucets 
* [Testnet Faucet](https://t.me/testgiver_ton_bot) — Bot for getting testnet TON

### APIs
* [toncenter](https://testnet.toncenter.com/)

### DNS Providers
* [dns.ton.org](https://dns.ton.org/?testnet=true)

### NFT Marketplaces
* [GetGems.io](https://testnet.getgems.io/)

### Explorers
* [tonscan.org](https://testnet.tonscan.org)
* [tonapi.io](https://testnet.tonapi.io/)
* [ton.sh](https://testnet.ton.sh/)
* [ton.cx](https://testnet.ton.cx/)
* [dton.io](https://testnet.dton.io/)

# Contribution Guidelines

1. Decide on the changes you want to make in the awesome-ton list.
2. Press `.` on the `awesome-ton` page to open the online editor (VSCode).
3. Make changes, describe them, and submit a commit as a Pull Request.
4. Congratulations, you're now a contributor to TON! 😎

# License

MIT
