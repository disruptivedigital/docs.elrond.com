---
id: erdpy
title: erdpy
---

erdpy CLI and Python SDK

**erdpy** (the CLI tool) can be found here: [elrond-sdk-erdpy](https://github.com/ElrondNetwork/elrond-sdk-erdpy). It targets a broad audience of **users** and **developers**, as depicted below:

| Feature                                                                              | Audience                                                            |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------- |
| Compile Smart Contracts (Rust, C, C++) to WASM                                       | Smart Contract developers                                           |
| Deploy, execute (call), query Smart Contracts                                        | Smart Contract developers, application developers, tech enthusiasts |
| Run _Mandos_ (testing platform) JSON tests against Smart Contracts                   | Smart Contract developers                                           |
| Sign & send [System Smart Contract transactions](/validators/staking/staking-smart-contract)   | Validator owners                                          |
| Sign & send regular transactions                                                     | Application developers, tech enthusiasts                            |
| Query Network status, transactions status / details                                  | Application developers, tech enthusiasts                            |
| Query account details                                                                | Application developers, tech enthusiasts                            |
| Generate PEM files, recover private key from mnemonic                                | Tech enthusiasts                                                    |
| Miscellaneous support features (e.g. bech32 conversion)                              | Tech enthusiasts                                                    |

**erdpy** libraries:

| Package                                                                         |Description                                                                     |
|---------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| [erdpy_core](https://github.com/ElrondNetwork/sdk-erdpy-core)                   | Basic components for interacting with the blockchain and with smart contracts. |
| [erdpy_wallet](https://github.com/ElrondNetwork/sdk-erdpy-wallet)               | Core wallet components (generation, signing).                                  |
| [erdpy_network](https://github.com/ElrondNetwork/sdk-erdpy-network-providers)  | Network providers (API, Gateway).                                              |
