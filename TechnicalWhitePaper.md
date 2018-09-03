# Bitbox Technical White Paper

**June 4, 2018**

## Bitbox: A Platform for Securing all Blockchain Networks

**Abstract:**
The bitbox hardware/software appliance introduces a new easy to use platform for securing all blockchain networks.
In order for a blockchain to be secure the network must be greatly decentralized.
To accomplish this, many individual network nodes must be setup, constantly running, and continually updated.
Unfortunately, the process to setup a full node is difficult, different for every blockchain, and requires an elevated level of technical expertise.
In the current environment it is impossible for the layman to participate in securing the network and advanced concepts such as Proof-of-Stake mining. This also makes it difficult for new projects and enthusiasts to deploy new blockchain networks.

The bitbox solution will solve these issues by removing the technical barriers to entry with a, small, elegant, and easy to use hardware device that enables users to add any blockchain full node or masternode they care to support.
The bitbox platform will also bootstrap new blockchain projects by providing a functioning massively decentralized network with an open source protocol for full node containerization. Blockchain developers can then incentivize bitbox owners to run their blockchain in two ways: by paying them with bitbox coins or through their own masternode via their blockchains Proof-of-Stake mining.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Bitbox Technical White Paper](#bitbox-technical-white-paper)
  - [Bitbox: A Platform for Securing all Blockchain Networks](#bitbox-a-platform-for-securing-all-blockchain-networks)
    - [1 Introduction](#1-introduction)
      - [1.1 Background](#11-background)
      - [1.2 Moto](#12-moto)
      - [1.3 Bitbox Core Design Principles](#13-bitbox-core-design-principles)
    - [2 Bitbox Node - What to expect from bitbox nodes](#2-bitbox-node---what-to-expect-from-bitbox-nodes)
    - [3 Bitbox Token - What can I use the BOX Token for?](#3-bitbox-token---what-can-i-use-the-bbx-token-for)
      - [3.1 "Token" Main Chain](#31-token-main-chain)
      - [3.2 Achievements Side Chain](#32-achievements-side-chain)
      - [3.3 Skill-tree Side Chain](#33-skill-tree-side-chain)
    - [4 Bitbox Rewards](#4-bitbox-rewards)
      - [4.1 "Token" Reward Program](#41-token-reward-program)
      - [4.2 "Achievements" Reward Program](#42-achievements-reward-program)
      - [4.3 "Skill-tree" Reward Program](#43-skill-tree-reward-program)
      - [4.4 Bitbox mining](#44-bitbox-mining)
      - [4.5 Masternodes / Proof-of-Stake](#45-masternodes--proof-of-stake)
      - [4.6 Crypto Mining From Behind Your Own bitbox Node w/ Block Reward Sharing](#46-crypto-mining-from-behind-your-own-bitbox-node-w-block-reward-sharing)
      - [4.6 Crypto Mining From Behind Your Own bitbox Node w/o Block Reward Sharing](#46-crypto-mining-from-behind-your-own-bitbox-node-wo-block-reward-sharing)
    - [5 API's / Protocols](#5-apis--protocols)
      - [5.1 Node Status](#51-node-status)
      - [5.2 Node BOX Wallet](#52-node-bbx-wallet)
      - [5.3 Bitbox Store](#53-bitbox-store)
      - [5.4 Reward](#54-reward)
      - [5.5 Bitbox Block Producer Pool Reward Sharing](#55-bitbox-block-producer-pool-reward-sharing)
    - [6 Mobile App](#6-mobile-app)
      - [6.1 Badge Notification](#61-badge-notification)
      - [6.2 Collectibles](#62-collectibles)
      - [6.3 Skill Tree](#63-skill-tree)
    - [7 Security Considerations](#7-security-considerations)
    - [8 Philosophy](#8-philosophy)
    - [7 Conclusion](#7-conclusion)
    - [References](#references)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

### 1 Introduction
**Problem:** Decentralization and adoption are key to the security and strength of a blockchain network; however, the current ecosystem is user-hostile enabling only tech-savvy users to run full nodes and participate in Proof-of-Stake mining.

**Solution:** We create an easy to use hardware appliance (bitbox) that allows users to easily add nodes for all blockchains they use and want to support with a simple user-friendly interface.

#### 1.1 Background
Blockchain technology was introduced in 2008 with the launch of the Bitcoin crypto currency, since then entrepreneurs and developers have attempted to generalize the technology to support a wider range of applications creating thousands of blockchain networks.

Blockchains rely on full nodes to validate transactions and blocks. Almost all full nodes help the network by accepting, validating, and relaying transactions to other nodes on the network. Full nodes sometimes also support lightweight clients and wallets. If not enough full nodes are providing these services blockchains can be compromised or fail. 

Volunteers run full nodes using spare computers and bandwith resources, but more are needed ([bitcoin.org, Participate-> Running a full node](https://bitcoin.org/en/full-node)). Running a full node has energy, internet bandwith, and time costs that volunteers must consider on top of the initial setup which can be a very daunting task for the non-tech savvy user. 

All that must be done for just one blockchain. If a user wants to run multiple full nodes they must repeat the process. Depending on how different the other blockchain full node is the user may have to go through additional technical documentation and tutorials.

This is why we're making bitbox. We want to create an elegant, open, user friendly ecosystem that invites and incentivises as many people as possible to particpate.

#### 1.2 Motto
Simply securing the blockchain.

#### 1.3 Bitbox Core Design Principles
These are the principles that will define bitbox.

1. **Simplicity**: First and foremost bitbox is all about simplicity. We are going to make the barriers of entry into the revolutionary space of blockchain disappear.
2. **Security**: We make security simple as bitbox comes stock with many protections provided by an official stable build of the Debian Linux operating system which is thoroughly tested and regularly inspected by professionals within a community.
3. **Scalability**: Bitbox is designed to work across as many blockchain decentralized networks as possible. The computational power of your bitbox will be easily upgradeable and at a reasonable price. It will allow the bitbox owner to scale to however many nodes he/she wishes to support.

### 2 Why bitbox
One of the most notable reasons why blockchain technology is relevant now more than ever stems from the lack of trust. In a recent 2018 report "No market saw steeper declines than the United States, with a 37-point aggregate drop in trust across all institutions." That's a HUGE loss of trust! Everyone is feeling this loss of trust and are looking for something to put their trust in. A few are now seeing blockchain technology as a way to build trust again, by trusting a network of distributed nodes that no one person or organization controls. By running a node with the shared rules of a particular institution of blockchain technology like Bitcoin or Ethereum. You cast your vote to support rules validating and then recording each block of data procesed on the network. You now have the power with bitbox to simply startup your own node at a click of a button to vote for the blockchain networks that you believe in and trust (and are verifying!).

### 3 What is the difference between the ERC20 token and the BOX coin?
The bitbox token sale will fund the project and hopefully increase in value providing early investors with some return. The token will be redemable for the BOX coin if/when the bitbox blockchain is launched. 

### 4 Bitbox Incentive System
Bitbox Proof-of-Stake mines and provides an ecosystem for blockchain organizations and developers (guest) to incentivise bitbox owners (host) to run their blockchain nodes in several ways:
* Develop their own Proof-of-Stake blockchain and provide a full node container
    * Stake, time, and return may very based on the specifc guest blockchain rules
* Provide a full node container and stake BOX on behalf of the bitbox owner
    * The guest provides BOX coin to a contract with specifc time and amount of BOX, if the host runs the node for the alloted time they receive the entire stake reward for the coin staked at the end of the time
* Provide full node container with options that when enabled for x time the host receives BOX coin, e.g. run lightning node ontop of your bitcoin node for at least 30 days and receive .01 BOX! 

#### 4.1 BOX Proof-of-Stake Mining
Every bitbox comes preloaded with the bitbox blockchain and will Proof-of-Stake mine with a minimum .000000001 BOX. The BOX blockchain can be removed by the user if they so choose.

#### 4.2 Masternodes / Proof-of-Stake
Full node containers can be built for any masternode Proof-of-Stake blockchain. Users will be able to simply tap an icon for the node they want added to their bitbox. This action will download the container, sync the chain (with throttling options available to limit bandwith overages), and provide an address for deposit.

#### 4.3 Achievements Reward Program
The bitbox blockchain will provide a few out of the box achievments that when completed will provide some BOX reward. Other blockchain platforms can build full node containers with optional achievements and provide their own rewards. Some example achievments may include:
* Run three blockchains for six months, get 1 BOX
* Run Bitcoin node with lightning network for 30 days, get 10 BOX
* Run Ethereum with 5 ETH stake for one year, get 5 BOX 

#### 4.4 Crypto Mining from Behind Your Own bitbox Node w/ Block Reward Sharing
* The biggest difference between this and a conventional mining pool is you would be pulling your own transaction from the mempool not receiving them from the mining pool.
* All rewards would be shared like in a mining pool, shares would be assigned based on provable work

#### 4.5 Crypto Mining from Behind Your Own bitbox Node w/o Block Reward Sharing
* This is pure solo mining at its finest. You will us your bitbox node to run you own local blockchain full node.

### 5 API's and Protocols
Bitbox will be developed as an open source project and use open source tools. The bitbox software will be free to use and users can build their own hardware if they so choose.

The community will use open source containerization software to build a standardized library of full nodes that can be used by bitbox devices. These containers will form the basis of the protocol for blockchain nodes to be "one-click" ready for bitbox 

#### 5.1 RESTFul API
Bitbox will have a full set of RESTful APIs for developers and third parties to build custom apps. These APIs may include:
* getNodeStatus(node)
* getAllNodeStatus
* getDataUsage
* startNode(node)
* stopNode(node)
* getBalance(node)
* getAllBalance

#### 5.2 Node BOX Wallet
Bitbox will have its own software wallet on device, but will also be compatible with popular hardware wallets such as the Nano S ledger and Trezor.

### 6 Mobile App
Mobile apps may be developed by the bitbox project or by the community, these apps can interact with the users bitbox via RESTful APIs.

### 7 Philosophy
The design philosophy for bitbox is intended to follow the following principles:

1. **Simplicity**: First and foremost bitbox is all about simplicity. We are going to make the barriers of entry into the revolutionary space of blockchain disappear.
2. **Universality**: bitbox is designed to work across as many blockchain decentralized networks as possible.
3. **Modularity**: bitbox is designed to be modular and leverage off the same base platform. This will make upgrading possible and easy.
4. **Agility**: bitbox is a fast plug and play way to get a block chain node up and running.
5. **Non-discrimination** and **non-censorship**: These nodes will run without any knowledge of who you are and without censorship of any kind.

### 8 Conclusion
Decentralization and adaoption are paramount for the security and success of blockchain networks. Bitbox was created by passionate individuals working in the blockchain space who want to see this technoloy thrive. Please join us in making this a reality.




### References

1. [Bitcoin White Paper](https://bitcoin.org/bitcoin.pdf)
2. [Ethereum White Paper](https://github.com/ethereum/wiki/wiki/White-Paper)
3. [2018 Edelman Trust Barometer](https://www.edelman.com/trust-barometer/)
4. [bitcoin.org ](https://bitcoin.org/en/full-node#ubuntu-1604)

Copyright © 2018 bitbox

Without permission, anyone may use, reproduce or distribute any material in this white paper for non-commercial and educational
use (i.e., other than for a fee or for commercial purposes) provided that the original source and the applicable copyright notice
are cited.

**DISCLAIMER:** This bitbox Technical White Paper is for information purposes only. bitbox does not guarantee the accuracy of or the conclusions reached in this white paper, and this white paper is provided “as is”. bitbox does not make and expressly disclaims all representations and warranties, express, implied, statutory or otherwise, whatsoever, including, but not limited to: (i) warranties of merchantability, fitness for a particular purpose, suitability, usage, title or noninfringement; (ii) that the contents of this white paper are free from error; and (iii) that such contents will not infringe third-party rights. bitbox and its affiliates shall have no liability for damages of any kind arising out of the use, reference to, or reliance on this white paper or any of the content contained herein, even if advised of the possibility of such damages. In no event will bitbox or its affiliates be liable to any person or entity for any damages, losses, liabilities, costs or expenses of any kind, whether direct or indirect, consequential, compensatory, incidental, actual, exemplary, punitive or special for the use of, reference to, or reliance on this white paper or any of the content contained herein, including, without limitation, any loss of business, revenues, profits, data, use, goodwill or other intangible losses.
