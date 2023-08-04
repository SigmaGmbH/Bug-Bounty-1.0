# Bug-Bounty-1.0 ✨🔍

This repo consolidates reported issues from swisstronik-evm-module, swisstronik-librustgo, and swisstronik-chain repositories, complemented by all the Bug Bounty 1.0 program details and rewards for developers.

## Swisstronik Overview 🌐

Swisstronik is a privacy-focused layer 1 solution built on Cosmos SDK, leveraging Intel SGX to protect transaction and smart contract privacy. Fully compatible with EVM, it provides encrypted smart contract states, while using friendly-dev tools such as Metamask, Remix IDE, and Hardhat. 🚀

## Who can join this Bug Bounty? 🎯

**Developers:** This includes professionals specializing in various fields such as blockchain core development, Intel SGX development, smart contract and dApp development, using programming languages such as Go, Rust, Javascript, and Solidity. 👨‍💻

**Node Operators:** Individuals who meet the [Node setup requirements](https://swisstronik.gitbook.io/swisstronik-docs/swisstronik-testnet/setup-node) and are interested in setting up a node can actively participate in the Bug Bounty program. ⚙️

## Swisstronik Features 🌟🔐

**Enhanced Privacy:** Execute EVM module within secure Intel SGX enclaves for private and protected transactions. 

**SwisstronikJS Library:** Safeguard data confidentiality with dedicated functions for encrypted transactions and calls. 

**Faucet:** Test SWTR tokens for free on Swisstronik's testnet for versatile testing.
[Faucet link](https://faucet.testnet.swisstronik.com/) 

**EVM Compatibility:** Seamlessly migrate Ethereum-based apps and smart contracts to the Swisstronik ecosystem with added Intel SGX security. 

**Block Explorers:** Access real-time network information through the Cosmos and EVM block explorers.
[Cosmos Block Explorer](https://explorer-cosmos.testnet.swisstronik.com/)
[EVM Block Explorer](https://explorer-evm.testnet.swisstronik.com/)

**Unencrypted Logs for Smart Contract Testing:** Analyze smart contract events for valuable insights during testing. (Remember all the smart contract variable states are encrypted within the Swisstronik blockchain) 

## Assets in Scope 🔍🎯

**Intel SGX**: Bugs reported on the node side related to our implementation of Intel SGX, [swisstronik-librustgo repository](https://github.com/SigmaGmbH/swisstronik-librustgo).

**Blockchain core bugs:** Code issues compromising the safe functionality of the chain and our implementation of the EVM module, potentially leading to blockchain crashes, [swisstronik-chain](https://github.com/SigmaGmbH/swisstronik-chain) & [swisstronik-evm-module](https://github.com/SigmaGmbH/swisstronik-evm-module)

**Blockchain Network & Informational Bugs:** Issues that can arise when setting up nodes, interacting with the blockchain by deploying contracts or making transactions/calls, and problems related to the accuracy or clarity of the documentation. Bugs on the blockchain can disrupt operations, causing technical glitches, transaction errors, and data inaccuracies. 🛠

## Rules 📜🔒

**First come, first served:** The first developer to report a bug adhering to our guidelines will receive the reward, documented in the "Issues" section for transparency. 🏆

**Submission Criteria:** Bug reports must adhere to the guidelines outlined in the [Issue template](./ISSUE_TEMPLATE.md) to ensure effective resolution. (Note: This issue template has already been implemented in each repository.) 

**IMPORTANT: To qualify for the reward, kindly attach your submitted issue to our [Bug Bounty Dashboard](https://www.swisstronik.com/bug-bounty)** 

**Public Recognition:** (optional) Bug bounty winners will be recognized in the [Hall of Fame](./Hall%20Of%20Fame/) folder in the repository, showcasing their achievements. 

**Rewards Transparency:** Transaction records of rewards paid to developers will be publicly accessible in the repository [Hall Of fame](./Hall%20Of%20Fame/) and in the blockchain itself for transparency. 💸

**Deadline:** All bug reports must be created before September 15th to be eligible for rewards and consideration. ⏳🗓️

## Resources 📚💡

**[Swisstronik Documentation:](https://link.swisstronik.com/u7a)** Comprehensive documentation is provided to assist participants in understanding the platform and its features.

**[Discord Channel:](https://link.swisstronik.com/2tz)** A dedicated Discord channel called "TESTNET 1.0 & BUG BOUNTY" is available for participants to ask questions. **We strive to provide responses within 12 hours to ensure prompt support.** 💬🚀
