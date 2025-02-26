---
title: Networks, Public RPC Endpoints, & APIs
lang: en-US
---

::: tip Developer Tip
We recommend using [Alchemy](https://www.alchemy.com/optimism) for its scalablity, reliability, and data accuracy. 
:::

::: warning
Some API calls, such as the those in the [personal namespace](https://geth.ethereum.org/docs/rpc/ns-personal) make no sense in a shared environment.
Such RPCs are either totally unsupported, or will return nonsensical values.
:::

## Optimism (mainnet)


| Parameter | Value |
| --------- | ----- |
| Network Name | **`Optimism`** |
| Description | **`Mainnet`** |
| Chain ID | **`10`** |
| Explorer | **[https://explorer.optimism.io](https://explorer.optimism.io)** |
| HTTP Endpoint<sup>1</sup> | We recommend [Alchemy](https://docs.alchemy.com/reference/optimism-api-quickstart/?a=818c11a8da). Optimism also provides this endpoint: **`https://mainnet.optimism.io`.** _But it is not for production systems and is rate limited._   |
| L1 Contract Addresses | [link](https://github.com/ethereum-optimism/optimism/tree/develop/packages/contracts/deployments/mainnet#layer-1-contracts) |
| L2 Contract Addresses | [link](https://github.com/ethereum-optimism/optimism/tree/develop/packages/contracts/deployments/mainnet#layer-2-contracts) |
| chainid.link | [https://chainid.link/?network=optimism](https://chainid.link/?network=optimism)

::: tip Developer Tip If you are seeing rate limit issues when testing with the public end point, or if you need websocket functionality, we recommend signing up for [Alchemy's](https://www.alchemy.com/optimism) free trial 
:::

(1) Some API calls, such as those in the [personal namespace](https://geth.ethereum.org/docs/rpc/ns-personal) make no sense in a shared environment.
Such RPCs are either not supported, or will return nonsensical values.


### API Options:

1. Get free access to Optimism through [Alchemy](https://www.alchemy.com/optimism)

2. For small scale tests, you can use our public API:
- HTTP endpoint: [https://mainnet.optimism.io](https://mainnet.optimism.io) (note, this is for testing. For production, use Alchemy) 

You can run a large application for free using [Alchemy](https://www.alchemy.com/optimism). We’ve done extensive diligence and Alchemy is our recommendation due to reliability, scalability, and data correctness. They're the default API provider and developer platform for top projects like OpenSea and Facebook. 

## Optimism Goerli

::: tip Purpose
This is our test network.
:::



| Parameter | Value |
| --------- | ----- |
| Network Name | **`Optimism Goerli`** |
| Description | **`Testnet (public)`** |
| Chain ID | **`420`** |
| Explorer | **[https://goerli-explorer.optimism.io](https://goerli-explorer.optimism.io)** |
| HTTP Endpoint | **`https://goerli.optimism.io`** |
| L1 Contract Addresses | [link](https://github.com/ethereum-optimism/optimism/tree/develop/packages/contracts/deployments/goerli#layer-1-contracts) |
| L2 Contract Addresses | [link](https://github.com/ethereum-optimism/optimism/tree/develop/packages/contracts/deployments/goerli#layer-2-contracts) |
| chainid.link | [https://chainid.link/?network=optimism-goerli](https://chainid.link/?network=optimism-goerli)

### API Options


1. Get free access to Optimism through [Alchemy](https://www.alchemy.com/optimism)

2. For small scale tests, you can use our public API:
- HTTP endpoint: [https://goerli.optimism.io](https://goerli.optimism.io) (note, this is for testing. For production, use Alchemy) 

You can run a large application for free using [Alchemy](https://www.alchemy.com/optimism). We’ve done extensive diligence and Alchemy is our recommendation due to reliability, scalability, and data correctness. 
They're the default API provider and developer platform for top projects like OpenSea and Facebook. 
They also support websocket functionality, which our public endpoint does not.

To see the full list of providers visit [Node & API Providers](./providers.md). 



### Test ETH

[The Optimism Faucet](https://optimismfaucet.xyz/) provides Optimism Goerli ETH.
Alternatively, if you already have Goerli ETH, you can [bridge it](https://app.optimism.io/bridge). For more faucet options see [Network Faucets](./faucets.md).

