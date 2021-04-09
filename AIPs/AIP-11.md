---
AIP: 11
Title: '[LedgerMaster](https://www.opusm.io/)' to receive the Dapp Incubation Fund from AERGO
Author: PO of [LedgerMaster](https://www.opusm.io/), YHKIM (@LedgerMaster-yhkim)
Status: Stage I
Category: dodona
Created: 2021-04-09

---



# [LedgerMaster](https://www.opusm.io/) to receive the Dapp Incubation Fund from AERGO



## Project overview

![img](https://i.imgur.com/AtCpFdF.png)




## Introduction

Hundreds of platforms are competing right now in the blockchain industry, advocating their own unique token ecosystems designed to accomplish various goals. However, most blockchain platforms, including AERGO, are difficult to approach for developers and planners in charge of system construction in a legacy environment. Often, a team of specialized developers must be organized in order to implement blockchain technology into a service that a company is envisioning. Even those specialists must select a platform that best fits their company's services from blockchain platforms in various, unstandardized forms, and then spend a considerable time learning it.

## The first function to be implemented in LedgerMaster for AERGO

### Powerful Data Processing - Smart Contract

Blockchain technology has various potential uses, but its most well-known role to many planners and developers is its role as a distributed ledger. This means that in the viewpoint of existing legacy architecture, blockchain technology, ultimately, is being treated as a data processing system on the same level as RDBMS, NOSQL, or big data. Data processing systems all add specific values to the data, and the value that blockchain technology adds to normal data is the value of 'trust'. Blockchain technology provides reliable data even between parties who cannot trust each other.

However, despite the importance of the data processing function and its performance, most blockchain platforms cannot provide the level of data processing function and performance that can be used as is, especially for enterprise systems. In the most primitive systems, data structures are created directly in the binary data area of a transaction. Even when data is stored in a smart contract, there is the limitation that you have to rely only on basic variables, lists, and map data structures provided by the scripting language. Therefore, data structures that require more than a certain level of complexity have no choice but to operate a separate database, and using blockchain technology loses its meaning in the first place.

What our team has learned from doing enterprise business for many years is that large amounts of log data that does not require the priceless value of 'trust' must be processed outside the blockchain, and that for most data that requires the value of 'trust' together with an efficient data structure, there is no place to go. Also, data of this type is small enough in size to contain in a blockchain. Focusing on these points, we are aiming to construct a data structure similar to a table of a relational database inside the blockchain through a smart contract, process it through SQL queries, and then provide a basic index structure so that it can meet most customers needs, while porting our existing experience to the public blockchain AERGO.

This technology can be implemented in NFT issuance, and provides a highly productive tool that enables not only the digital copyright market, such as Opensea, but also real estate, healthcare, public, and general companies to implement NFTs.

  
![img](https://i.imgur.com/BzvOTDB.png)
![img](https://i.imgur.com/g9wMO82.png)

OpenSea, the largest digital copyright market - Source: https://opensea.io/

### Legacy Architecture Interworking Module

Until now, most cases of public blockchains interworking with enterprise architecture had a simple format; the public blockchain's client, in a DMZ area with free internet connection, would include simple hash value information in a transaction and store it in the public blockchain, in a process called anchoring. This is mainly because there are many policy restrictions that make it difficult to link subsystems accessed through the Internet with internal systems in public institutions, large corporations, and financial institutions. In the future, it is expected that cases of interlocking public blockchains with systems that are relatively less constrained in terms of network security issues will gradually increase.
  
![img](https://i.imgur.com/rc9N5i9.png)
 A demonstration screen of OPUSM's LedgerMaster

In light of these changes to the market situation, OPUSM Inc. is aiming to develop an enterprise-class interworking module for AERGO equipped with various functions when accessing public blockchain networks from legacy architecture. There will be no need to develop everything from scratch, since the module will be based on the client provided by the blockchain platform. The module's functions will include simple interlinking with Spring Boot, load balancing, usability processing, prevention of input data loss, and Smart Contract-linked data processing introduced above.

## In the Future

The architecture and technologies of the enterprise domain, which have developed and improved over decades, are so vastly large and complex that even the largest companies in the world, such as Google, IBM, or Microsoft cannot monopolize them. Incorporating the unique ecosystem and technical achievements of blockchains, which have developed independently in the field of cryptocurrency, into the existing enterprise domain is no simple task. Many companies will make a joint effort, and as a result the market will grow in size and develop continuously. Throughout 2019 and 2020, when numerous blockchain developers and companies focused on high-risk Dapp fields like cryptocurrency and De-Fi, the very few teams like OPUSM Inc., seriously researching and developing blockchain technology in the enterprise area step by step, will eventually gain market power. We plan on continuing this journey together with AERGO.

The OPUSM Inc., team is currently researching and developing not only data processing Smart Contracts and legacy architecture interworking modules based on private blockchains, but also developmental framework, monitoring tools for operation, and various modules that increase the stability and availability of blockchain systems.  Private blockchains and public blockchains have many differences in usage and environment, but we are confident that AERGO will become a must-have partner by establishing itself as a public blockchain that has powerful utility in the enterprise area.

## Proposal

We at LedgerMaster of OPUSM Inc. propose to use the Aergo Mainnet and Aergo Enterprise Solution.

We are planning on using AERGO for JDBC in various industries that LedgerMaster can be applied, such as healthcare, legal tech, prop tech, FinTech, and InsureTech. Customers from various companies will create AERGO wallets in order to save and share crucial information.

Also, the tokens used in trading or brokering this data will be issued in the ARC1 standard, and the assets registered on LedgerMaster will use NFTs issued in the ARC2 standard.

## License
Copyright and related rights waived via [CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/).

![CC BY-NC-SA](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTczNDQ2MzE4NiwxNDY1MjA4Njg4LDkxND
g5NzM3Niw3ODE2NjgzNjZdfQ==
-->