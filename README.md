# API3 x ETHIstanbul :hammer::city_sunset:
Hackers, we hope you are excited for the ETHIstanbul Hackathon! We are looking forward to seeing what you build.

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

## API3 Bounties

### 🥇 Best use of dAPI price feeds - $4000

Utilize crypto, commodities, equities, or forex data by activating a feed through the [API3 Market](https://market.api3.org/dapis?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul).

Project Ideas:

- Paymasters using account abstraction
- Perpetual Swaps
- Oracle Protected Swaps
- Lending Protocols

[Here's an example of using Paymasters with dAPIs on zkSync Era Testnet](https://github.com/api3-ecosystem/zksync-paymaster-dapis?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul)

### 🥇 Best use of API3 QRNG - $3000

Add unpredictable dynamics to your application with random numbers by using API3 QRNG in your smart contract.

Project Ideas:

- Randomized Airdrops
- Loot boxes
- Randomized NFT Mints
- Light strategy games

[Click here to check out all the API3 QRNG demo projects to get started](https://docs.api3.org/guides/qrng/qrng-remix/?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul)

### API3 Runners up - $1000 x3

Use either QRNG or dAPI price feeds in your dApp to qualify as an API3 runner-up.

## Introduction to API3

First-party oracles provide a more secure and reliable oracle, whilst enabling dApps to verify the data source. API3's first-party oracles are powered by Airnode, a serverless oracle node that enables API providers to run their own oracle nodes.
You can [learn more about first-party oracles](https://docs.api3.org/guides/airnode/calling-an-airnode/?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul) within the API3 Documentation.

There are three key elements within API3's Oracle Stack:

### Data feeds: dAPIs

dAPIs provide smart contracts with access to continuously updated feeds of market data by oracles hosted by highly reputable financial data providers. API3's price feeds can be accessed in two methods:

Self-funded dAPIs see users add collateral for oracle operation and are permissionless. They provide a data feed source with off-chain aggregation as a single source.

Managed dAPIs are powered by multiple first-party oracles with native-chain aggregation offering a verifiable, decentralized oracle solution.
Once a dAPI has been integrated a smart contract can access a range of data feed services through the [API3 Market](https://market.api3.org/dapis?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul).

- [Learn how to get started with dAPIs](https://docs.api3.org/guides/dapis/subscribing-self-funded-dapis/?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul)

- [Learn how to use dAPIs](https://docs.api3.org/guides/dapis/read-a-dapi/?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul)

- [Check out the API3 Market](https://market.api3.org/dapis?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul)

- [Check out dAPI Reader example Github repo](https://github.com/api3dao/data-feed-reader-example?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul)

### API3 QRNG

API3 QRNG is a public utility API3 provides on behalf of well-established, prestigious organizations serving Quantum random number generation (QRNG). QRNG is a method of random number generation based on quantum phenomena and considered within the scientific community to be the most secure method of random number generation.
It operates as a public good, where users simply add gas to a wallet correlated to the oracle node, enabling the oracle node to return a random number when requested by a contract.

- [Learn how to get started with QRNG](https://docs.api3.org/guides/qrng/?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul)

### ChainAPI: Airnode Integration Tool

With ChainAPI your smart contract can connect almost any API, whether open or authenticated, by using API3's first-party oracle node, Airnode. ChainAPI enables you to integrate and deploy the open-source Airnode with an intuitive step-by-step integration and deployment process.

- [Learn how to call an Airnode](https://docs.api3.org/guides/airnode/calling-an-airnode/?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul)

- [Check out ChainAPI](https://chainapi.com/?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul)

## Tutorials: 

Here's a list of all the demo projects that use QRNG, dAPIs and Airnode to get you started:

- [on-chain sports betting](https://github.com/api3-ecosystem/getting-started?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul)
- [Making on-chain Payments and mint an NFT receipt using dAPIs](https://medium.com/@vanshwassan/making-an-on-chain-payment-and-minting-an-nft-receipt-with-permissionless-price-oracles-a7339f7b8c3e?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul)
- [zkSync Paymasters with dAPIs](https://era.zksync.io/docs/dev/tutorials/api3-usd-paymaster-tutorial.html?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul)
- [Building a roulette table with QRNG](https://docs.api3.org/guides/qrng/roulette-guide/?utm_source=Github&utm_medium=Github&utm_campaign=Eth+Istanbul&utm_id=Eth+Istanbul)

## References For ETHIstanbul Hackathon

Links to different repos for examples and help.

- ETH London Workshop Repo:
https://github.com/api3-ecosystem/Eth-London-Demo?utm_source=Github&utm_medium=Github&utm_campaign=Eth+Istanbul&utm_id=Eth+Istanbul

- ETH CHI Workshop Repo:
https://github.com/api3-ecosystem/API3-PriceFeeds-Hardhat-Foundry?utm_source=Github&utm_medium=Github&utm_campaign=Eth+Istanbul&utm_id=Eth+Istanbul

- Prediction bet between two parties
https://github.com/api3-ecosystem/Prediction-Contract?utm_source=Github&utm_medium=Github&utm_campaign=Eth+Istanbul&utm_id=Eth+Istanbul

- Modified Paymaster for zkSync (Use dAPI to calculate USDC prices of Gas instead of ETH)
https://github.com/api3-ecosystem/zk-paymaster-dapi-vip?utm_source=Github&utm_medium=Github&utm_campaign=Eth+Istanbul&utm_id=Eth+Istanbul

- Fork of Aave with a simulation of a flashloan
https://github.com/api3-ecosystem/Aave-Api3?utm_source=Github&utm_medium=Github&utm_campaign=Eth+Istanbul&utm_id=Eth+Istanbul

- Starter kit: Starting a borrow/lend setup with WAGMI/rainbowkit front end
https://github.com/api3-ecosystem/oracle-zkevm?utm_source=Github&utm_medium=Github&utm_campaign=Eth+Istanbul&utm_id=Eth+Istanbul

- Offchain API Royalty share: Pull a Youtube API and use it to pay royalties onchain
https://github.com/api3-ecosystem/offchain-music?utm_source=Github&utm_medium=Github&utm_campaign=Eth+Istanbul&utm_id=Eth+Istanbul

- Or get started now with the [API3 Market](https://market.api3.org/dapis?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul).

## Community link

Looking for help or just want to hang with industry-leading developers? Head to the API3 Discord and drop questions in the #dev-support channel: https://discord.gg/api3dao

## Submission Requirements

All hackathon participants who are competing for the API3 bounties are required to submit a project that meets the following requirements:

- The project should be submitted to ETHIstanbul Hackathon 2023 by the deadline.
- Use of API3’s self-funded dAPIs that facilitates a proper use-case.
- The project should be live with a working frontend deployed.
- The project should be open-source with a public Github repository with the codebase. 
- The repo must be licenced with one of the following open source licences: GPL-3.0, or MIT.

## Judging criteria

Participants may submit a maximum of 1 project by the hackathon deadline. After submission, projects will be judged by the following criteria:

- **Real-world Functionality**: How well does the project work? Does it meet the minimum requirements?

- **Technical Difficulty**: How technically challenging was it to build the project?

- **Originality**: How original is the idea? How much does it differ from other existing solutions?

- **Design**: How well-designed is the project? Is it easy to use? Is it visually appealing?

- **BONUS** - Adding functionality to the Airnode protocol that will improve performance, interoperability, or further develop use cases.

## Questions? Support from API3 developers

Looking for help? Head to the API3 Discord and drop questions in the #dev-support channel: https://discord.gg/api3dao -- Or look out for API3 team members at ETHIstanbul. 

## Leave your feedback 

API3 is offering $20 for hackers who provide feedback on their experience of API3's documentation. 

![Feedback graphic](./Feedback.png)
