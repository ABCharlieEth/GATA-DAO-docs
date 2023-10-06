# The Cosmos Hub

The [Cosmos Hub](https://hub.cosmos.network/main/hub-overview/overview.html) was the first blockchain built with the Interchain Stack. It is a public Proof-of-Stake (PoS) blockchain with a native token, ATOM.&#x20;

ATOM is used to secure the network and pay for transaction fees, but is also the token that has funded the development of the Interchain Stack and other projects in the wider ecosystem.

The Cosmos Hub can be understood as a router facilitating transactions between the chains connected to it. For example, the Cosmos Hub allows for transaction fees to be paid in different tokens, as long as the zone trusts the Cosmos Hub and the other zones connected to it.

_How do you connect your chain to a non-Tendermint (non-CometBFT) chain?_&#x20;

The IBC connection is not limited to Tendermint-based chains. If another, non-Tendermint blockchain uses a fast-finality consensus algorithm, a connection can be established by adapting IBC to work with the non-Tendermint consensus mechanism.

If the other chain is a probabilistic-finality chain, a simple adaptation of IBC is not sufficient. A proxy chain called a peg-zone helps establish interoperability.&#x20;

Peg-zones are fast-finality blockchains which track chain states to establish finality. The peg-zone chain itself is IBC-compatible and acts as a bridge between the rest of the IBC network's chains and the probabilistic-finality chain.



<details>

<summary>German/Deutsch - Der Cosmos Hub</summary>

Die erste Blockchain, die mit dem Interchain Stack aufgebaut wurde

Beim Cosmos Hub handelt es sich um eine öffentliche “Proof-of-Stake” (PoS)-Blockchain mit einem eigenen Token, ATOM.&#x20;

ATOM kommt zum Einsatz, um das Netzwerk zu sichern und Transaktionsgebühren zu bezahlen, kommt ATOM zum Einsatz. Zugleich ist es aber auch der Token, der die Entwicklung des Interchain Stack und anderer Projekte im weiteren Ökosystem finanziert hat.

Der Cosmos Hub kann als Router verstanden werden, der Transaktionen zwischen den mit ihm verbundenen Chains erleichtert. So ermöglicht es der Cosmos Hub beispielsweise, dass die Transaktionsgebühren in verschiedenen Token bezahlbar sind, solange die jeweilige Zone dem Cosmos Hub und den anderen mit ihm verbundenen Zonen vertraut.

Wie lässt sich eine Blockchain mit einer anderen verbinden, die nicht auf Tendermint (CometBFT) basiert?&#x20;

IBC-Verbindungen sind nicht auf Tendermint-basierte Blockchains beschränkt. Wenn eine andere, nicht Tendermint-basierte Blockchain einen Fast-Finality-Konsensalgorithmus verwendet, kann eine Verbindung hergestellt werden, indem IBC so angepasst wird, dass es mit dem Nicht-Tendermint-Konsensmechanismus funktioniert.

Handelt es sich bei der anderen Kette jedoch um eine Kette mit probabilistischer Finalität, reicht eine einfache Anpassung der IBC nicht aus. Eine Proxy-Kette, Peg-Zone genannt, hilft hier bei der Herstellung der Interoperabilität.&#x20;

Peg-Zonen sind Blockchains mit schneller Endgültigkeit, die den Zustand der Kette verfolgen, um die Endgültigkeit herzustellen. Die Peg-Zone-Kette selbst ist IBC-kompatibel und fungiert als Brücke zwischen den übrigen Ketten des IBC-Netzwerks und der probabilistischen Finalitätskette.

\


</details>
