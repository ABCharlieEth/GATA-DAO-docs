---
description: The Inter-Blockchain Communication Protocol (IBC)
---

# IBC

The [Inter-Blockchain Communication Protocol (IBC)](https://ibcprotocol.org/) is the basis for interoperability in the Interchain. It leverages the instant finality of Tendermint to allow for the transfer of value (token transfers) and communication between heterogeneous chains. Blockchains with different applications and architecture specifications become interoperable whether or not they share a validator set.

Without IBC, the interoperability of heterogeneous chains is difficult to achieve because they may implement the consensus, networking, and application layers in different ways. As soon as a blockchain is compatible with IBC, it becomes interoperable with other blockchains.

The Interchain implements a modular architecture with two blockchain classes: zones and hubs

* Zones are heterogeneous blockchains carrying out the authentication of accounts and transactions, the creation and distribution of tokens, and the execution of changes to the chain.&#x20;
* Hubs are blockchains designed to connect the so-called zones.

Once a zone connects to a hub through an IBC connection, it gets automatic access to the other zones connected to that hub.&#x20;

At this point, data and value can be sent and received between the zones without risk of, for example, double-spending tokens. This helps reduce the number of chain-to-chain connections that need to be established for interoperability.

There is no enforcement of an actual topology. A hub can be understood as a zone with many connections to other zones. Application zones can be expected to join the hubs in the ecosystem, but they are free to coalesce into any topology the developers find appropriate.



<details>

<summary>German/Deutsch - IBC</summary>

Das Inter-Blockchain Communication Protocol (IBC)

IBC bildet die Grundlage für die Interoperabilität der Interchain. Es nutzt die sofortige Endgültigkeit von Tendermint, um die Übertragung von Werten (Token-Transfers) und die Kommunikation zwischen heterogenen Ketten zu ermöglichen. Blockchains mit unterschiedlichen Anwendungen und Architekturspezifikationen werden mit IBC interoperabel, unabhängig davon, ob sie einen gemeinsamen Validierungssatz haben oder nicht.

Ohne IBC ist die Interoperabilität heterogener Ketten schwierig zu erreichen, da sie die Konsens-, Netzwerk- und Anwendungsschichten auf unterschiedliche Weise implementieren können. Sobald eine Blockchain mit IBC kompatibel ist, wird sie mit anderen Blockchains interoperabel.

Die Interchain implementiert eine modulare Architektur mit zwei Blockchain-Klassen: Hubs und Zonen:

* Zonen sind heterogene Blockchains, die die Authentifizierung von Konten und Transaktionen, die Erstellung und Verteilung von Token sowie die Durchführung von Änderungen an der Kette übernehmen.&#x20;
* Hubs sind Blockchains, die die sogenannten Zonen miteinander verbinden sollen.&#x20;

Sobald sich eine Zone über eine IBC-Verbindung mit einem Hub verbindet, erhält sie automatisch Zugang zu den anderen Zonen, die mit diesem Hub verbunden sind.&#x20;

An diesem Punkt können Daten und Werte zwischen den Zonen gesendet und empfangen werden, ohne dass die Gefahr besteht, dass z. B. Token doppelt ausgegeben werden. Dies trägt dazu bei, die Anzahl der Chain-to-Chain-Verbindungen zu reduzieren, die für die Interoperabilität hergestellt werden müssen.

Es gibt keine Durchsetzung einer tatsächlichen Topologie. Ein Hub kann als eine Zone mit vielen Verbindungen zu anderen Zonen verstanden werden. Es kann erwartet werden, dass sich Anwendungszonen den Hubs im Ökosystem anschließen, aber es steht ihnen frei, sich zu einer beliebigen Topologie zusammenzuschließen, die die Entwickler für jeweils angemessen halten.

</details>
