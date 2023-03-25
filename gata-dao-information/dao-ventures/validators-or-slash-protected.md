---
description: GATA DAO validators are slash protected backed by GATA slashing fund
---

# Validators | Slash Protected

The cosmos hub is based on Tendermint (Ignite) which relies on a set of validators to secure the network. The role of validators is to run a full node and participate in consensus by broadcasting votes that contain cryptographic signatures signed by the validator’s private key. To better understand the concept please read this [document](https://medium.com/the-cosmos-guardian/proof-of-stake-on-cosmos-network-explained-to-my-dog-f7367297e5ae).

List of operational GATA validators protected by GATA slashing fund:

| Blockchain                 | Status                                                                                                         | Delegation link                                                                                                                                              | Auto-Compound                                                                                       | Self-Bond   | Commission |
| -------------------------- | -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------- | ----------- | ---------- |
| Cosmos Hub                 | [GATA Cosmos](https://www.mintscan.io/cosmos/validators/cosmosvaloper10unx6s0cdqntvrumd5hs07rgd5ytcztqh8etw6)  | [Delegate Atom](https://wallet.keplr.app/chains/cosmos-hub)                                                                                                  | [enabled](https://restake.app/cosmoshub/cosmosvaloper10unx6s0cdqntvrumd5hs07rgd5ytcztqh8etw6)       | 2000 Atom   | 3%         |
| Osmosis                    | [GATA Osmosis](https://www.mintscan.io/osmosis/validators/osmovaloper1d5ada26tcd24wltfakqkkdu3656k6n4chnyz8h)  | [Delegate Osmos](https://wallet.keplr.app/chains/osmosis)                                                                                                    | [enabled](https://restake.app/osmosis/osmovaloper1d5ada26tcd24wltfakqkkdu3656k6n4chnyz8h)           | 2000 Osmo   | 5%         |
| Juno                       | [GATA Juno](https://www.mintscan.io/evmos/validators/evmosvaloper1w9m6p7ctu4gkdsr8plle997h25rzsa96xlzfat)      | [Delegate Juno](https://wallet.keplr.app/#/juno/stake?tab=inactive-validators\&modal=stake\&validator=junovaloper1yeaw3dv6jk3hr290l2tsew7rr2vjykynme37s2)    | [enabled](https://restake.app/juno/junovaloper1yeaw3dv6jk3hr290l2tsew7rr2vjykynme37s2)              | 1500 Juno   | 5%         |
| Evmos                      | [GATA Evmos](https://www.mintscan.io/evmos/validators/evmosvaloper1w9m6p7ctu4gkdsr8plle997h25rzsa96xlzfat)     | [Delegate Evmos](https://wallet.keplr.app/#/evmos/stake?modal=stake\&chainId=evmos\_9001-2\&validator=evmosvaloper1w9m6p7ctu4gkdsr8plle997h25rzsa96xlzfat)   | [enabled](https://restake.app/evmos/evmosvaloper1w9m6p7ctu4gkdsr8plle997h25rzsa96xlzfat)            | 10000 Evmos | 5%         |
| Teritori                   | [GATA Teritori](https://teritori.explorers.guru/validator/torivaloper1dyduggaqthztgm8tnk59flkeu3l3qvpzhhd6hn)  | [Delegate Teritori ](https://explorer.teritori.com/teritori/staking)                                                                                         | [enabled](https://restake.app/teritori/torivaloper1dyduggaqthztgm8tnk59flkeu3l3qvpzhhd6hn/delegate) | 15000 Tori  | 5%         |
| NOMIC                      | [GATA Nomic](https://app.nomic.io/)                                                                            | [Delegate Nomic](https://app.nomic.io/)                                                                                                                      | -----                                                                                               | 4175 Nomic  | 3%         |
| Rebus                      | [GATA Rebus](https://rebus.explorers.guru/validator/rebusvaloper1v9z8pjfgjvuj4ar97h692scm88mvwks5plmvvq)       | [Delegate Rebus](https://app.rebuschain.com/staking)                                                                                                         | [enabled](https://restake.app/rebus/rebusvaloper1v9z8pjfgjvuj4ar97h692scm88mvwks5plmvvq/delegate)   | 1500 Rebus  | 5%         |
| Sifchain (Decommissioned)  | [GATA Sifchain](https://www.mintscan.io/sifchain/validators/sifvaloper1u453cen62m939v548nfql54zl886a9zy7ggzqq) | [Delegate sifchain](https://wallet.keplr.app/#/sifchain/stake?modal=detail\&chainId=sifchain-1\&validator=sifvaloper1u453cen62m939v548nfql54zl886a9zy7ggzqq) | -------                                                                                             | 100         | 5%         |

## Slash protection policy

There are two types of slashings validator nodes might face:

&#x20; _-Downtime ( When the validator is unable to sign most of the blocks in the particular window)_

&#x20; _-Double signing (Double signing occurs when a validating entity (private key) submits two signed messages for the same block)_ \
\
**Coverage**

\-100% downtime slashing coverage in a maximum of 14-28 days. \
\-10% double signing coverage in a maximum of 14-28 days.&#x20;

_(we hope to increase the number in the future)_ \
\
Because every network has different slashing parameters, we cannot give you estimates but for $JUNO if you delegate 100 $JUNO to GATA DAO Validation, in case of downtime jail you will be slashed 0.01 JUNO and 5 $JUNO in case of Double signing slashing.\
\
**Refund-time**

14-28 days depending on the network from where we are unbounding to cover the loss. \
\
**Eligible Chains**

* **Evmos**
* **Juno**
* **Atom**
* **Teritori**
