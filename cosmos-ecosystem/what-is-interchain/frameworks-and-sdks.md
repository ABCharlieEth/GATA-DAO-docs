---
description: The possibility of using alternative blockchain frameworks and SDKs
---

# Frameworks and SDKs

As the Cosmos SDK is modular, developers can port existing codebases in Go on top of the SDK. This allows developers to build on the Interchain without having to compromise too much on the toolset and environment used.

For example, with [Ethermint](https://github.com/evmos/ethermint) developers can use the Ethereum Virtual Machine (EVM) from the main Go Ethereum client as a Cosmos SDK module, which is compatible and combinable with existing modules.

All Ethereum tools (such as Truffle and Metamask) are compatible with Ethermint. Developers can even port their Solidity smart contracts to interact with the Interchain Ecosystem. Building a chain is not necessary to develop Interchain-compatible smart contracts, it can be all done with Ethermint. However, while Ethermint allows running vanilla Ethereum as a Cosmos application-specific blockchain, developers benefit from the CometBFT.
