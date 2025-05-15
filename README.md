<!-- omit from toc -->
# Awesome TON (The Open Network) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="logo/ton_symbol.svg" align="right" width="100">](https://ton.org)

[![TON Research](https://img.shields.io/badge/TON%20Research-0098EA?style=flat&logo=discourse&label=Forum&labelColor=gray)](https://tonresear.ch)
[![Telegram Foundation Group](https://img.shields.io/badge/TON%20Foundation-0098EA?logo=telegram&logoColor=white&style=flat)](https://t.me/tonblockchain)
[![Twitter Group](https://img.shields.io/twitter/follow/ton_blockchain)](https://twitter.com/ton_blockchain)

A carefully curated collection of outstanding libraries, tools, services, protocols, and smart contracts in the TON ecosystem. This list serves as a comprehensive resource for developers, researchers, and enthusiasts interested in building on The Open Network.

---

<!-- omit from toc -->
## Contents

- [🏛️ Official Resources](#️-official-resources)
- [🎓 Education](#-education)
  - [Basic Theory](#basic-theory)
  - [YouTube Educational Videos](#youtube-educational-videos)
  - [Community Tutorials](#community-tutorials)
  - [Smart Contract Examples](#smart-contract-examples)
  - [Guidelines](#guidelines)
- [🧑‍💻 Development](#-development)
  - [Dev Tools](#dev-tools)
  - [Libraries \& SDKs](#libraries--sdks)
  - [Community Support](#community-support)
- [🔌 Core Integrations](#-core-integrations)
  - [Authentication](#authentication)
  - [Telegram Web Apps (TWAs)](#telegram-web-apps-twas)
  - [API Services](#api-services)
- [🛠️ Utilities](#️-utilities)
- [🎨 Design Resources](#-design-resources)
- [🤝 Contribute](#-contribute)

---

## 🏛️ Official Resources
- [TON Documentation](https://docs.ton.org/) - Comprehensive technical documentation.
- [TON Community Blog](https://blog.ton.org/) - Official blog with ecosystem updates.
- [Hackathons & Contests](https://ton.org/events) - Official events and competitions.
- [TON Job Board](https://jobs.ton.org/) - Find or post TON ecosystem jobs.
- [TON Community on Telegram](https://t.me/toncoin) - Main community discussion group.

---

## 🎓 Education
### Basic Theory
- [Introduction to The Open Network](https://docs.ton.org/learn/introduction) - Foundational overview.
- [Blockchain & Smart Contract Fundamentals](https://blog.ton.org/what-is-blockchain) - Core concepts explained.
- [Smart Contract Addresses](https://docs.ton.org/learn/overviews/addresses) - Understanding TON addressing system.
- [TON for Solidity Developers](https://blog.ton.org/six-unique-aspects-of-ton-blockchain-that-will-surprise-solidity-developers) - Transitioning from EVM to TON.
- [TON Sites, TON WWW, TON Proxy](https://blog.ton.org/ton-sites) - TON's decentralized web infrastructure.

### YouTube Educational Videos

- TON Development Courses
  - [TON Dev Study](https://www.youtube.com/@WikiMar/playlists) - Educational playlists covering various TON development topics.
    - English
      - [FunC & Blueprint](https://www.youtube.com/playlist?list=PLyDBPwv9EPsDjIMAF3XqNI2XGNwdcB3sg)
      - [TON with Fift](https://www.youtube.com/playlist?list=PLyDBPwv9EPsB47mqzF4Z9K8k6HYqPv6Px)
      - [TON with Python](https://www.youtube.com/playlist?list=PLyDBPwv9EPsDrQUyuHTsKRzxg6XaTPzhh)
      - [Tact & Blueprint](https://www.youtube.com/@AlefmanVladimirEN-xb4pq/videos)
    - Russian
      - [FunC & Blueprint](https://www.youtube.com/playlist?list=PLyDBPwv9EPsA5vcUM2vzjQOomf264IdUZ)
      - [TON Connect Integration](https://www.youtube.com/playlist?list=PLyDBPwv9EPsCJ226xS5_dKmXXxWx1CKz_)
      - [TON with Python](https://www.youtube.com/playlist?list=PLyDBPwv9EPsC-7xbn8b8noZh9a1Xkg42W)
      - [TON with GO](https://www.youtube.com/playlist?list=PLyDBPwv9EPsCV-GifFVIQ1o3t35j1nj-u)
      - [TON with Fift](https://www.youtube.com/playlist?list=PLyDBPwv9EPsCYG-hR4N5FRTKUkfM8POgh)

- Community Channels
  - [TON & Company](https://www.youtube.com/@ton-company/featured) - Ecosystem updates and tutorials.
  - [TON Dev Moscow](https://www.youtube.com/@tondevmoscow/featured) - Developer-focused content.
  - [TON - The Open Network](https://www.youtube.com/@the_open_network/featured) - Official TON channel.
  - [DoraHacks Workshops](https://www.youtube.com/playlist?list=PLpkpEL9gYGez8hCtzMtOabQPX9bgYLZPN) - Hackathon training.

### Community Tutorials
- Smart Contracts
  - [TON Speedrun](https://tonspeedrun.com/) - Interactive learning challenges.
    - [🚩 Challenge 1: Simple NFT Deploy](https://github.com/romanovichim/TONQuest1)
    - [🚩 Challenge 2: Chatbot Contract](https://github.com/romanovichim/TONQuest2)
    - [🚩 Challenge 3: Jetton Vending Machine](https://github.com/romanovichim/TONQuest3)
    - [🚩 Challenge 4: Lottery/Raffle](https://github.com/romanovichim/TONQuest4)
    - [🚩 Challenge 5: Create UI to Interact with the Contract](https://github.com/romanovichim/TONQuest5)
    - [🚩 Challenge 6: Analyzing NFT Sales on Getgems](https://github.com/romanovichim/TONQuest6)
  - [Get Started with TON](https://docs.ton.org/develop/onboarding-challenge) - Official onboarding challenge.
  - [Build Your First DApp on TON](https://docs.tonxapi.com/reference/build-your-first-dapp) - Step-by-step guide.
  - TON Community Hello World Series:
    - [Working with Your First TON Wallet](https://ton-community.github.io/tutorials/01-wallet/)
    - [Writing Your First Smart Contract](https://ton-community.github.io/tutorials/02-contract/)
    - [Building Your First Web Client](https://ton-community.github.io/tutorials/03-client/)
    - [Testing Your First Smart Contract](https://ton-community.github.io/tutorials/04-testing/)
  - [FunC Journey](https://blog.ton.org/func-journey) - Learning FunC programming.
  - FunC Tutorial Series by @romanovichim:
    - [English](https://github.com/romanovichim/TonFunClessons_Eng)
    - [Russian](https://github.com/romanovichim/TonFunClessons_ru)
  - [Learn FunC in 10 Minutes](https://learnxinyminutes.com/docs/func/) - Quick reference guide.
  - [Wallet Smart Contracts Guide](https://docs.ton.org/develop/smart-contracts/tutorials/wallet) - Implementation tutorial.
  - [Multisig Contract Guide](https://docs.ton.org/develop/smart-contracts/tutorials/multisig) - Creating multisignature wallets.
  - [Rift Framework Tutorial](https://blog.ton.org/rift-announcement) - Python framework for TON.
  - [Multisig with TypeScript](https://docs.ton.org/develop/smart-contracts/tutorials/multisig-js) - JS implementation guide.
  - [Tolk Development Guide](https://github.com/dankorotin/ton-tutorials) - Smart contract development with Tolk.

- FT (Jettons) & NFT
  - [NFT Collection Minting Guide](https://docs.ton.org/develop/dapps/tutorials/collection-minting) - Full NFT deployment.
  - [Jetton Minting Tutorial](https://docs.ton.org/develop/dapps/tutorials/jetton-minter) - Creating fungible tokens.

- Telegram Bot
  - [Storefront Bot with TON Payments](https://docs.ton.org/develop/dapps/tutorials/accept-payments-in-a-telegram-bot) - Building a store.
  - [Bot with Self-managed Balance](https://docs.ton.org/develop/dapps/tutorials/accept-payments-in-a-telegram-bot-2) - Advanced integration.
  - [Food Delivery Bot Example](https://docs.ton.org/develop/dapps/tutorials/accept-payments-in-a-telegram-bot-js) - Real-world application.

- TON Connect
  - [Integration Manual](https://docs.ton.org/develop/dapps/ton-connect/integration) - Standard authentication protocol.
  - [Telegram Bot Integration](https://docs.ton.org/develop/dapps/ton-connect/tg-bot-integration) - Bots with wallet connections.
  - [Transaction Messages](https://docs.ton.org/develop/dapps/ton-connect/transactions) - Handling blockchain interactions.

### Smart Contract Examples
- [Official Smart Contract Examples](https://docs.ton.org/develop/smart-contracts/examples) - Reference implementations.

### Guidelines

- Development Guidelines
  - Smart Contracts
    - [Development Overview](https://docs.ton.org/develop/smart-contracts/guidelines) - Best practices.
  
  - Asset Processing
    - [Payments Processing](https://docs.ton.org/develop/dapps/asset-processing/) - Handling TON transfers.
    - [Jetton Processing](https://docs.ton.org/develop/dapps/asset-processing/jettons) - Working with tokens.
    - [NFT Processing](https://docs.ton.org/develop/dapps/asset-processing/nfts) - Non-fungible token handling.
    - [Metadata Parsing](https://docs.ton.org/develop/dapps/asset-processing/metadata) - Working with on-chain data.
  
  - TON Connect
    - [Developer Guide](https://docs.ton.org/develop/dapps/ton-connect/developers) - Implementation guide.
    - [Wallet Integration](https://docs.ton.org/develop/dapps/ton-connect/protocol/wallet-guidelines) - For wallet developers.
    - [Protocol Workflow](https://docs.ton.org/develop/dapps/ton-connect/protocol/workflow) - Technical specifications.

- API Documentation
  - [Chainstack API Reference](https://docs.chainstack.com/reference/getting-started-ton) - Interactive v2/v3 API docs with examples.

---

## 🧑‍💻 Development

### Dev Tools

- Development Frameworks
  - [Blueprint](https://github.com/ton-community/blueprint/) - Smart contract development environment.
  - [Rift](https://github.com/sky-ring/rift) - Python framework for TON smart contracts.
  - [Tact](https://tact-lang.org/) - High-level language for TON smart contracts.
  - [ton-k8s](https://github.com/disintar/ton-k8s) - Self-hosted TON network with Kubernetes and Docker.

- Testing Tools
  - [Testnet Faucet Bot](https://t.me/testgiver_ton_bot) - Telegram bot for testnet TON.
  - [TONX Testnet Faucet](https://faucet.tonxapi.com/) - Web-based faucet service.
  - [Chainstack TON Faucet](https://faucet.chainstack.com/ton-testnet-faucet) - Daily TON testnet refills.
  - [TON Dev Wallet](https://github.com/TonDevWallet/TonDevWallet) - Developer-focused wallet.

- IDE Support
  - [VS Code Plugin](https://marketplace.visualstudio.com/items?itemName=tonwhales.func-vscode) - FunC syntax highlighting and tools.
  - [IntelliJ IDEs Plugin](https://plugins.jetbrains.com/plugin/23382-ton) - TON development for JetBrains IDEs.
  - [Sublime Text Plugin](https://github.com/savva425/func_plugin_sublimetext3) - FunC support for Sublime.

- Debugging
  - [TxTracer](https://txtracer.ton.org) - Tool to emulate and trace any transaction from TON blockchain.

### Libraries & SDKs

- JavaScript/TypeScript
  - [TONX.JS](https://github.com/frigatebird-studio/TONX.js) - JavaScript SDK for TONX API.
  - [ton-core/ton](https://github.com/ton-core/ton) - Cross-platform client by ton-core.
  - [toncenter/tonweb](https://github.com/toncenter/tonweb) - Web client by TonCenter.
  - [orbs-network/ton-access](https://github.com/orbs-network/ton-access) - Decentralized RPC access.
  - [foton](https://github.com/VanishMax/foton) - Comprehensive toolkit for TON dApps.

- Python
  - [disintar/tonpy](https://github.com/disintar/tonpy) - Full-featured SDK with TLB support and TVM.
  - [yungwine/pytoniq](https://github.com/yungwine/pytoniq) - SDK with LiteClient and TLB.
  - [nessshon/tonutils](https://github.com/nessshon/tonutils) - High-level SDK and toolkit.
  - [tonfactory/tonsdk](https://github.com/tonfactory/tonsdk) - Cells and contract wrappers.
  - [toncenter/pytonlib](https://github.com/toncenter/pytonlib) - Python wrapper for Tonlib.
  - [yungwine/TonTools](https://github.com/yungwine/TonTools) - High-level library for HTTP/ADNL.

- Other Languages
  - Go
    - [xssnick/tonutils-go](https://github.com/xssnick/tonutils-go) - Comprehensive Go SDK.
    - [tonkeeper/tongo](https://github.com/tonkeeper/tongo) - Modern Go SDK.
    - [ton-blockchain/tonlib-go](https://github.com/ton-blockchain/tonlib-go) - Official Golang TonLib wrapper.
  - [tonutils-dart](https://github.com/novusnota/tonutils-dart) - Dart/Flutter SDK for mobile apps.
  - [tonlib-rs](https://github.com/ston-fi/tonlib-rs) - Rust SDK for TON.
  - [SwiftyTON](https://github.com/labraburn/SwiftyTON) - Swift SDK with async/await support.
  - [node-tonlib](https://github.com/labraburn/node-tonlib) - Node.js C++ addon for TON.
  - [ton-kotlin](https://github.com/andreypfau/ton-kotlin) - Kotlin SDK for JVM applications.
  - [TonSdk.NET](https://github.com/continuation-team/TonSdk.NET) - C# (.NET, Unity) SDK.

### Community Support

- Developer Communities
  - [TON Overflow](https://answers.ton.org) - Q&A platform for TON developers.
  - [TON Dev Chat](https://t.me/tondev_eng) - English developer community.
  - [TON 开发者社区](https://t.me/tondev_zh) - Chinese developer community.
  - [TON Разработка](https://t.me/tondev) - Russian developer community.

- Documentation Resources
  - [TON Learn](https://docs.ton.org/learn/) - Learning resources and guides.
  - [TON API References](https://docs.ton.org/reference/) - API documentation.

---

## 🔌 Core Integrations

### Authentication
- [TON Connect](https://github.com/ton-connect/) - Standard protocol for dApps and wallets.
- [delab-team/connect](https://github.com/delab-team/connect) - Multi-protocol SDK with unified interface.
- [@tonconnect/sdk](https://www.npmjs.com/package/@tonconnect/sdk) - JavaScript SDK for TON Connect 2.0.
- [tonutils/tonconnect](https://github.com/nessshon/tonutils?tab=readme-ov-file#ton-connect-integration) - Python SDK for TON Connect.
- [pytonconnect](https://pypi.org/project/pytonconnect/) - Alternative Python SDK.
- [darttonconnect](https://github.com/romanovichim/dartTonconnect) - Dart SDK for mobile apps.

### Telegram Web Apps (TWAs)
- [Official Documentation](https://core.telegram.org/bots/webapps) - Telegram's guidelines.
- [Community Documentation](https://docs.telegram-mini-apps.com/) - Developer community resources.
- [ton-community/twa-template](https://github.com/ton-community/twa-template) - TWA template with TON integration.
- [twa-dev/boilerplate](https://github.com/twa-dev/Boilerplate) - Starter boilerplate for TWAs.
- [twa-dev/sdk](https://github.com/twa-dev/sdk) - SDK package for TWA development.
- [twa-dev/Mark42](https://github.com/twa-dev/Mark42) - UI library optimized for TWAs.

### API Services
- [TONX API](https://www.notion.so/TONX-TONX-API-TONX-Lab-f9e86e5382604c6193a2ef2243b283fc?pvs=21) - Enterprise-grade API platform.
- [Chainstack](https://chainstack.com/build-better-with-ton/) - Managed RPC nodes with geo balancing.
- [toncenter.com](https://toncenter.com/) - Fast and reliable HTTP API.
- [dton.io/graphql](https://dton.io/graphql) - GraphQL API for TON.
- [tonapi.io](https://tonapi.io/) - Comprehensive API service.
- [anton.tools](https://anton.tools/) - Analytics API tools.

---

## 🛠️ Utilities

- Analytics & Monitoring
  - [TonStat.com](https://www.tonstat.com/) - Key metrics dashboard for TON ecosystem.
  - [Chainstack Compare](https://compare.chainstack.com/dashboard) - Node performance comparison.
  - [TON Grafana](https://tonmon.xyz/) - Blockchain metrics visualization.

- Network Tools
  - [Tonutils Proxy](https://github.com/xssnick/Tonutils-Proxy) - User-friendly TON Proxy implementation.
  - [TON Notify Bot](https://t.me/TONNotifyBot) - Transaction notifications via Telegram.
  - [Blockchain Network Visualizer](https://github.com/qpwedev/blockchain-network-visualizer) - Network visualization tool.

- Staking Services
  - [KTON](https://kton.io/) - Next-Gen Liquid Staking for TON.

- Address Management
  - [vaniton](https://github.com/AntonMeep/vaniton) - Vanity address generator for TON wallets.
  - [custon](https://github.com/TON-NFT/custon) - Custom wallet address generator in JavaScript.
  - [TON Multisender](https://ton.multisender.app/) - Batch transaction tool for TON and Jettons.
  - [TON Bulksender](https://ton.bulksender.app) - Enterprise-grade bulk transaction tool.

- Market Analysis
  - [Anonymous Numbers Market Analytics](https://github.com/qpwedev/anonymous-numbers-market-analytics) - Fragment market statistics.

---

## 🎨 Design Resources

- [TON Design System](https://github.com/designervoid/ton-design-system) - Tailwind-based component library.
- [TON Brand Assets](https://ton.org/brand-assets) - Official logos, colors, and brand guidelines.

---

## 🤝 Contribute
> [Contributing to Awesome-TON](contributing.md)

1. Fork this repository
2. Press `.` on your fork to open the online editor (VSCode)
3. Make your changes following our contribution guidelines
4. Submit a Pull Request with a clear description of your additions/changes
5. Join the TON contributors community!
