---
sip: 1
title: Arbitrum Frax Pool
status: Implemented
author: Sam Kazemian (@samkazemian)
discussions-to: https://www.saddle.community/t/sip-1-arbitrum-frax-pool/44
created: 2021-12-14
---

## **Summary**

We propose a new Saddle pool on Arbitrum that consists of the following stablecoins: FRAX, USDC, and USDT.

## **Background**

**Frax**

Frax is the first fractional-algorithmic stablecoin protocol. Frax is open-source, permissionless, and entirely on-chain – currently implemented on Ethereum and other chains. The end goal of the Frax protocol is to provide a highly scalable, decentralized, algorithmic money in place of fixed-supply digital assets like BTC.

Frax has an advanced Algorithmic Market Operations Controller (AMO), which allows FRAX to expand and contract the supply of FRAX by minting FRAX into liquidity pools and withdrawing and burning from them. This allows them to safely grow the supply when it is warranted, and also to shrink the supply when off peg. This is a powerful lever at their disposal that can also benefit the other stablecoins in this pool. If FRAX is on peg, they could mint it into the Arbitrum Frax pool, and such an action would cause the other tokens to trade at a premium to it. So when FRAX grows, so do its counterparts in the pool.

**Synapse**

Synapse is a cross-chain layer ∞ protocol powering frictionless interoperability between blockchains. By providing decentralized, permissionless transactions between any L1, sidechain, or L2 ecosystem, Synapse powers integral blockchain activities such as asset transfers, swaps, and generalized messaging with cross-chain functionality - and in so doing enables new primitives based off of its cross-chain architecture. Synapse is a bridging partner of Frax.

## **Motivation**

By forming the Arbitrum Frax pool, we can pool our resources together to offer better incentives, deep liquidity, and pave the way for future collaborations.

## **Specification**

We propose using the FRAX gauge farming contracts that support locking LP tokens for an extra boost to keep people long term aligned. This has worked really well for the Saddle D4 pool and a breakthrough in sustainable farming. We propose an initial A of 200 with standard 4 BPS fees (0 admin fees), and that 100% of SDL incentive emmissions on Arbitrum are redirected to this pool.

$FRAX and $SYN incentives will be added as well, pending approval by each protocol’s governance. In the future, Frax will also launch an AMO for this pool.

**For**: Launch the Arbitrum Frax Pool and redirect SDL incentives.

**Against**: No change.

## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
