# The ProxySwap Protocol

## Introduction

The ProxySwap protocol is the first Uniswap V3 fork decentralized exchange (DEX) protocol, forked and modified from the Uniswap protocol, is a peer-to-peer<sup>[1](#1-ethereum-protocols-are-sometimes-referred-to-as-peer-to-contract-systems-as-well-these-are-similar-to-a-peer-to-peer-systems-but-with-immutable-persistent-programs-known-as-smart-contracts-taking-the-place-of-a-peer)</sup> system designed for exchanging cryptocurrencies (ERC-20 Tokens) on the [DegenChain](https://bridge.degen.tips/) L3 blockchain. 

The protocol is implemented as a set of persistent, non-upgradable smart contracts; designed to prioritize censorship resistance, security, self-custody, and to function without any trusted intermediaries who may selectively restrict access. Nevertheless, the protocol is still in its nascent stages of development and may see more features being developed as part of its periphery libraries.

The ProxySwap protocol is forked from one of the multiple Uniswap protocols. Uniswap V1 and V2 are open source and licensed under GPL. V3 however, the version based on which ProxySwap protocol is created, is open source with slight modifications, which are viewable [here](https://github.com/Uniswap/uniswap-v3-core/blob/main/LICENSE). This very version of ProxySwap, once deployed, will function in perpetuity, with 100% uptime, provided the continued existence of the [DegenChain](https://bridge.degen.tips/) L3 blockchain.

<br/><br/>
## How does the ProxySwap protocol compare to a typical market?
To understand how the ProxySwap protocol, just like the Uniswap protocol, differs from a traditional exchange, it is helpful to first look at two subjects: how the Automated Market Maker design deviates from traditional central limit order book-based exchanges, and how permissionless systems depart from conventional permissioned systems.

### Order Book VS AMM
Most publicly accessible markets use a central limit order book style of exchange, where buyers and sellers create orders organized by price level that are progressively filled as demand shifts. Anyone who has traded stocks through brokerage firms will be familiar with an order book system.

The ProxySwap protocol takes a different approach, using an Automated Market Maker (AMM), sometimes referred to as a Constant Function Market Maker, in place of an order book.

At a very high level, an AMM replaces the buy and sell orders in an order book market with a liquidity pool of two assets, both valued relative to each other. As one asset is traded for the other, the relative prices of the two assets shift, and a new market rate for both is determined. In this dynamic, a buyer or seller trades directly with the pool, rather than with specific orders left by other parties. The advantages and disadvantages of Automated Market Makers versus their traditional order book counterparts are under active research by a growing number of parties. Uniswap Labs has collected some notable examples on their research page.

### Permissionless Systems
The second departure from traditional markets is the permissionless and immutable design of the ProxySwap protocol. These Uniswap design decisions were inspired by Ethereum's core tenets, and Uniswap's commitment to the ideals of permissionless access and immutability as indispensable components of a future in which anyone in the world can access financial services without fear of discrimination or counter-party risk.

Permissionless design means that the protocol's services are entirely open for public use, with no ability to selectively restrict who can or cannot use them. Anyone can swap, provide liquidity, or create new markets at will. This is a departure from traditional financial services, which typically restrict access based on geography, wealth status, and age.

The protocol is also immutable, in other words not upgradeable. No party is able to pause the contracts, reverse trade execution, or otherwise change the behavior of the protocol in any way. It is worth noting that ProxySwap Governance DAO has the right (but no obligation) to divert a percentage of swap fees on any pool to a specified address. However, this capability is known to all participants in advance, and to prevent abuse, the percentage is constrained between 10% and 25%.

Where can I find more information
For research into the economics of AMMs, game theory, or optimization research, check out Uniswap Labs [research](https://docs.uniswap.org/concepts/research) page.

For features implemented in V3 that expand and refine the AMM design, see the [V3 Concepts](https://docs.uniswap.org/concepts/protocol/concentrated-liquidity) page.

----------

###### 1. Ethereum protocols are sometimes referred to as peer-to-contract systems as well. These are similar to a peer-to-peer systems, but with immutable, persistent programs known as smart contracts taking the place of a peer.

