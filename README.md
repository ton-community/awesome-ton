# Awesome TON (The Open Network)

A curated list of remarkable libraries, tools, services, protocols, and smart contracts related to TON.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Twitter](https://img.shields.io/twitter/follow/ton_blockchain?style=social)](https://twitter.com/ton_blockchain)
[![Telegram](https://img.shields.io/badge/telegram-TON%20Dev%20Chat-blue?logo=telegram)](https://t.me/tondev_eng)

<!---
ADD link to Tact language community in the future https://twitter.com/tact_language
--->


### 🗂️ Table of Contents

- 🏛️ [Official Resources](#🏛️-official-resources)
- 🎓 [Education](#🎓-education)
  - [Basic Theory](#📔-basic-theory)
  - [YouTube Educational Videos](#youtube-youtube-educational-videos)
  - [Community Tutorials](#📚-community-tutorials)
  - [Smart Contract Examples](#🧱-smart-contract-examples)
  - [Guidelines](#📖-guidelines) 
- 🧑‍💻 [Get coding](#🧑‍💻-get-coding)
  - [Dev Tools](#dev-tools)
  - [Libraries](#libraries)
  - [Boilerplates](#boilerplates)
  - [Get help](#get-help)
- 🗣 [Talks & Workshops](#🗣-talks--workshops)
- 🗂 [Projects](#🗂-projects)
  - [DEX](#decentralized-exchanges)
  - [Marketplaces](#marketplaces)
  - [Explorers](#explorers)
  - [Bridges](#bridges)
  - [Wallets](#wallets)
- 🌐 [Authentication](#🌐-authentication)
- 💵 [Funds](#💵-funds)
- 🎛 [Utilities](#🎛-utilities)
- 👨‍🎨 [UX/UI](#👨‍🎨-uxui)
- ✏️ [Contribute](#✏️-contribute)
- [License](#license)

---

## 🏛️ Official Resources


* [Documentation](https/docs.ton.org/)
* [Community blog](https://blog.ton.org/)
* [Hackathon, contests](https://ton.org/events)
* [List of actual vacancies](https://jobs.ton.org/)

---

## 🎓 Education


### 📔 Basic Theory
* [The Open Network](https://docs.ton.org/learn/introduction)
* [What is blockchain? What is a smart contract? What is gas?](https://blog.ton.org/what-is-blockchain)
* [Smart Contract Addresses](https://docs.ton.org/learn/overviews/addresses)
* [Six unique aspects of TON Blockchain that will surprise Solidity developers](https://blog.ton.org/six-unique-aspects-of-ton-blockchain-that-will-surprise-solidity-developers)

### ![YouTube](https://cdn.emojidex.com/emoji/mdpi/YouTube.png "YouTube") YouTube Educational Videos


* [Ton Dev Study](https://www.youtube.com/@WikiMar/playlists) channel
  * English
    * [FunC & Blueprint](https://www.youtube.com/playlist?list=PLyDBPwv9EPsDjIMAF3XqNI2XGNwdcB3sg)
    * [TON Development with Fift](https://www.youtube.com/playlist?list=PLyDBPwv9EPsB47mqzF4Z9K8k6HYqPv6Px)
    * [TON Development with Python](https://www.youtube.com/playlist?list=PLyDBPwv9EPsDrQUyuHTsKRzxg6XaTPzhh)
  * Russian
    * [FunC & Blueprint](https://www.youtube.com/playlist?list=PLyDBPwv9EPsA5vcUM2vzjQOomf264IdUZ)
    * [TON Connect - Integration in TON Ecosystem](https://www.youtube.com/playlist?list=PLyDBPwv9EPsCJ226xS5_dKmXXxWx1CKz_)
    * [TON Development with Python](https://www.youtube.com/playlist?list=PLyDBPwv9EPsC-7xbn8b8noZh9a1Xkg42W)
    * [TON Development with GO](https://www.youtube.com/playlist?list=PLyDBPwv9EPsCV-GifFVIQ1o3t35j1nj-u)
    * [TON Development with Fift](https://www.youtube.com/playlist?list=PLyDBPwv9EPsCYG-hR4N5FRTKUkfM8POgh)
* [Ton Dev Moscow](https://www.youtube.com/@tondevmoscow/featured) channel



### 📚 Community Tutorials
* Smart Contracts and dApps
  * [Get Started with TON](https://docs.ton.org/develop/onboarding-challenge) 
  * Ton-Community Hello World
    * [Step by step guide for working with your first TON wallet](https://ton-community.github.io/tutorials/01-wallet/)
    * [Step by step guide for writing your first smart contract](https://ton-community.github.io/tutorials/02-contract/)
    * [Step by step guide for building your first web client](https://ton-community.github.io/tutorials/03-client/)
    * [TON Hello World part 4: Step by step guide for testing your first smart contract](https://ton-community.github.io/tutorials/04-testing/)
  * [Func Journey](https://blog.ton.org/func-journey)
  * FunC @romanovichim lessons
    * [TonFunClessons_Eng](https://github.com/romanovichim/TonFunClessons_Eng)
    * [TonFunClessons_ru](https://github.com/romanovichim/TonFunClessons_ru)
  * [Learn Func in 10 minutes](https://learnxinyminutes.com/docs/func/)
  * [How to work with wallet smart contracts](https://docs.ton.org/develop/smart-contracts/tutorials/wallet)
  * [How to make a simple multisig contract](https://docs.ton.org/develop/smart-contracts/tutorials/multisig)
  * [Unlocking the Power of TON with Rift Framework](https://blog.ton.org/rift-announcement)
  * [Interact with multisig wallets using TypeScript](https://docs.ton.org/develop/smart-contracts/tutorials/multisig-js)
* FT(Jettons) & NFT
  * [Step by step NFT collection minting](https://docs.ton.org/develop/dapps/tutorials/collection-minting)
  * [Mint your first Jetton](https://docs.ton.org/develop/dapps/tutorials/jetton-minter)
* Telegram bot
  * [Storefront bot with payments in TON](https://docs.ton.org/develop/dapps/tutorials/accept-payments-in-a-telegram-bot)
  * [Bot with own balance](https://docs.ton.org/develop/dapps/tutorials/accept-payments-in-a-telegram-bot-2)
  * [Bot for sales of dumplings](https://docs.ton.org/develop/dapps/tutorials/accept-payments-in-a-telegram-bot-js)
* Ton Connect
  * [Integration manual](https://docs.ton.org/develop/dapps/ton-connect/integration)
  * [Telegram bot integration](https://docs.ton.org/develop/dapps/ton-connect/tg-bot-integration)
  * [Sending messages](https://docs.ton.org/develop/dapps/ton-connect/transactions)


### 🧱 Smart Contract Examples

 * [Smart Contract Examples](https://docs.ton.org/develop/smart-contracts/examples)


### 📖 Guidelines
* Smart Contract Development
  * [Overview](https://docs.ton.org/develop/smart-contracts/guidelines)
* Develop Apps
  * [Payments processing](https://docs.ton.org/develop/dapps/asset-processing/)
  * [TON Jetton processing](https://docs.ton.org/develop/dapps/asset-processing/jettons)
  * [TON NFT processing](https://docs.ton.org/develop/dapps/asset-processing/nfts)
  * [TON Metadata Parsing](https://docs.ton.org/develop/dapps/asset-processing/metadata)
* TON Connect (Integration)
  * [TON Connect for Developers](https://docs.ton.org/develop/dapps/ton-connect/developers)
  * [TON Wallet Guidelines](https://docs.ton.org/develop/dapps/ton-connect/wallet-guidelines)
  * [TON Connect Workflow](https://docs.ton.org/develop/dapps/ton-connect/workflow)

---

## 🧑‍💻 Get coding

### Dev Tools
  * [Testnet Faucet](https://t.me/testgiver_ton_bot) — Bot for getting testnet TON
  * [TON Dev Wallet](https://github.com/TonDevWallet/TonDevWallet) - Wallet for developers
  * [Rift](https://github.com/sky-ring/rift) - Python framework for building smart contracts.
  * [Tact](https://tact-lang.org/) - High-level language for TON smart-contracts
  * API
    * [toncenter.com](https://toncenter.com/) - Fast and reliable HTTP API for The Open Network.
    * [dton.io/graphql](https://dton.io/graphql)
    * [tonapi.io](https://tonapi.io/)
    * [anton.tools](https://anton.tools/)
  * Explorers preferred by devs
    * [dton.io](https://dton.io/)
    * [explorer.toncoin.org](https://explorer.toncoin.org/)
    * [explorer.tonnft.tools](https://explorer.tonnft.tools)

  * Telegram Web Apps (TWAs)
    * [Telegram WebApps Documentation](https://core.telegram.org/bots/webapps) — full description on Telegram website.
    * [docs.twa.dev](https://docs.twa.dev/) - User-friendly docs from community.
    * [ton-community/twa-template](https://github.com/ton-community/twa-template) — template for a new TWA interacting with the TON.
    * [twa-dev/boilerplate](https://github.com/twa-dev/Boilerplate) — another boilerplate for a new TWA.
    * [twa-dev/sdk](https://github.com/twa-dev/sdk) — npm package for TWA SDK.
    * [twa-dev/Mark42](https://github.com/twa-dev/Mark42) — Mark42 is a simple lightweight tree-shakable UI library for TWA.

### Boilerplates
* [Blueprint](https://github.com/ton-community/blueprint/) — A development environment for writing, testing, and deploying smart contracts.

### Libraries
  * Python
    * [tonfactory/tonsdk](https://github.com/tonfactory/tonsdk)
    * [toncenter/pytonlib](https://github.com/toncenter/pytonlib)
  * JavaScript
    * [ton-core/ton](https://github.com/ton-core/ton) — Cross-platform client for TON blockchain, by ton-core
    * [toncenter/tonweb](https://github.com/toncenter/tonweb) — Cross-platform client for TON blockchain, by TonCenter
    * [orbs-network/ton-access](https://github.com/orbs-network/ton-access) - Unthrottled anonymous RPC access to TON blockchain
  * Go
    * [xssnick/tonutils-go](https://github.com/xssnick/tonutils-go)
    * [tonkeeper/tongo](https://github.com/tonkeeper/tongo)
    * [Golang TonLib wrapper](https://github.com/ton-blockchain/tonlib-go)
  * [Rust SDK](https://github.com/ston-fi/tonlib-rs)
  * [C++ TonLib](https://github.com/ton-blockchain/ton/tree/master/example/cpp)
  * [Java TonLib wrapper (JNI)](https://github.com/ton-blockchain/tonlib-java)
  * [labraburn/SwiftyTON](https://github.com/labraburn/SwiftyTON) - native Swift wrapper for tonlib with async/await
  * [labraburn/node-tonlib](https://github.com/labraburn/node-tonlib) - C++ addon for NodeJS to work with tonlibjson
  * [ton-kotlin](https://github.com/andreypfau/ton-kotlin) — Kotlin SDK for TON blockchain


### Get help
  * [TON Overflow](https://answers.ton.org)
  * [English developers chat](https://t.me/tondev_eng)
  * [Russian developers chat](https://t.me/tondev)
  * [Chinese developers chat](https://t.me/tondev_zh)

---

## 🗣 Talks & Workshops

* [Community platform for talks](https://join.toncompany.org/home) by [Ton&Co](https://t.me/tonandcompany)
* [DoraHacks workshops](https://www.youtube.com/playlist?list=PLpkpEL9gYGez8hCtzMtOabQPX9bgYLZPN)

---

## 🗂 Projects
### Decentralized exchanges
  * [dedust.io](https://dedust.io/)
  * [STON.fi](http://app.ston.fi)
  * [DeDust](http://dedust.io/dex/swap)
  * [Megaton Finance](https://megaton.fi)

### Marketplaces
  * [Fragment](https://fragment.com/)
  * [GetGems](https://getgems.io/)
  * [ton.diamonds](https//ton.diamonds/)
  * [disintar.io](https://disintar.io/)

### Explorers
  * [tonscan.org](https://tonscan.org/)
  * [dton.io](https://dton.io/)
  * [tonviewer.com](https://tonviewer.com/)
  * [explorer.tonnft.tools](https://explorer.tonnft.tools/)
  * [tonlens.com](https://tonlens.com)
  * [TonWhales](https://tonwhales.com/explorer)
  * [3xpl](https://3xpl.com/ton)
  * [explorer.toncoin.org](https://explorer.toncoin.org)
  * [ton.cx](https://ton.cx)

### Bridges 
  * [bridge.ton.org](https://bridge.ton.org/)
  * [Orbit Bridge](https://bridge.orbitchain.io/)
  * [tonana.org](https://app.tonana.org/)

### Wallets 
  * [Tonkeeper](https://tonkeeper.com)
  * [TonHub](https://tonhub.com)
  * [@wallet](https://t.me/wallet) - 
  * [Ton Android](https://play.google.com/store/apps/details?id=ton.coin.wallet) - Official Android wallet
  * [TON Wallet](https://wallet.ton.org/) - Official Web Wallet
  * [ton-cli](https://github.com/ex3ndr/ton-cli) - CLI wallet
  * [MyTonWallet](https://mytonwallet.io) - Web wallet and browser extension for TON
  * [Juston](https://juston.io) - iOS wallet
  * [Coin98 Wallet](https://wallet.coin98.com) - A mobile and browser extension wallet with multi-chain support
  * [openmask.app](https://www.openmask.app/) - MetaMask analog for The Open Network
  * [Ton iOS](https://apps.apple.com/by/app/toncoin-wallet/id1560210939) - Official iOS wallet

### Staking
  * [TonWhales staking](https://tonwhales.com/staking)
  * [The list of the TON nominator pools](https://tonvalidators.org/)

---

## 🌐 Authentication
  * [Ton Connect](https://github.com/ton-connect/) — Standart protocol for communication between wallets and apps
  * [delab-team/connect](https://github.com/delab-team/connect) - SDK, which combines multiple protocols in one modal
---

## 💵 Funds
* [Toncoin Fund](https://www.toncoin.fund/)
* [TAV Fund](https://tav-incubation.com/)
* [Tonstarter](https://tonstarter.com/hi/)


## 🎛 Utilities

* [Tonutils Proxy](https://github.com/xssnick/Tonutils-Proxy) - user-friendly TON Proxy implementation 
* [vaniton](https://github.com/AntonMeep/vaniton) - Vanity address generator for The Open Network's standard wallets
* [custon](https://github.com/TON-NFT/custon) - User-friendly generator of custom TON wallet addresses written in JS
* [TON Grafana](https://tonmon.xyz/) - Blockchain metrics
* [TON Notify Bot](https://t.me/TONNotifyBot) [[Sources]](https://github.com/tonbase/ton-notify-bot) - Instant notifications about transfer coins of the TON address in Telegram.

## 👨‍🎨 UX/UI
* [TON Design System](https://github.com/designervoid/ton-design-system) - Design system which provides [TON Brand Assets](https://ton.org/brand-assets) as Atom CSS


## ✏️ Contribute

1. Decide on the changes you want to make in the awesome-ton list.
2. Press `.` on the `awesome-ton` page to open the online editor (VSCode).
3. Make changes, describe them, and submit a commit as a Pull Request.
4. Congratulations, you're now a contributor to TON! 😎

## License

MIT
