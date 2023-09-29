---
description: The Inter-Blockchain Communication Protocol (IBC)
---

# IBC

[The Inter-Blockchain Communication Protocol (IBC)](https://ibcprotocol.org/) is the basis for interoperability in the Interchain. It leverages the instant finality of Tendermint to allow for the transfer of value (token transfers) and communication between heterogeneous chains. Blockchains with different applications and architecture specifications become interoperable whether or not they share a validator set.

Without IBC, the interoperability of heterogeneous chains is difficult to achieve because they may implement the consensus, networking, and application layers in different ways. As soon as a blockchain is compatible with IBC, it becomes interoperable with other blockchains.

The Interchain implements a modular architecture with two blockchain classes: hubs and zones.

Zones are heterogeneous blockchains carrying out the authentication of accounts and transactions, the creation and distribution of tokens, and the execution of changes to the chain. Hubs are blockchains designed to connect the so-called zones. Once a zone connects to a hub through an IBC connection, it gets automatic access to the other zones connected to that hub. At this point, data and value can be sent and received between the zones without risk of, for example, double-spending tokens. This helps reduce the number of chain-to-chain connections that need to be established for interoperability.

There is no enforcement of an actual topology. A hub can be understood as a zone with many connections to other zones. Application zones can be expected to join the hubs in the ecosystem, but they are free to coalesce into any topology the developers find appropriate.



<details>

<summary><mark style="color:blue;">German - Lesen Sie dies auf Deutsch</mark></summary>



</details>
