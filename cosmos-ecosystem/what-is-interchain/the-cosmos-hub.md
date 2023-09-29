# The Cosmos Hub

The [Cosmos Hub](https://hub.cosmos.network/main/hub-overview/overview.html) was the first blockchain built with the Interchain Stack. It is a public Proof-of-Stake (PoS) blockchain with a native token, ATOM. ATOM is used to secure the network and pay for transaction fees, but is also the token that has funded the development of the Interchain Stack and other projects in the wider ecosystem.

The Cosmos Hub can be understood as a router facilitating transactions between the chains connected to it. For example, the Cosmos Hub allows for transaction fees to be paid in different tokens, as long as the zone trusts the Cosmos Hub and the other zones connected to it.

_How do you connect your chain to a non-Tendermint (non-CometBFT) chain?_ The IBC connection is not limited to Tendermint-based chains. If another, non-Tendermint blockchain uses a fast-finality consensus algorithm, a connection can be established by adapting IBC to work with the non-Tendermint consensus mechanism.

If the other chain is a probabilistic-finality chain, a simple adaptation of IBC is not sufficient. A proxy chain called a peg-zone helps establish interoperability. Peg-zones are fast-finality blockchains which track chain states to establish finality. The peg-zone chain itself is IBC-compatible and acts as a bridge between the rest of the IBC network's chains and the probabilistic-finality chain.



<details>

<summary><mark style="color:blue;">German - Lesen Sie dies auf Deutsch</mark></summary>



</details>
