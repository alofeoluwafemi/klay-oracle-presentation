## Key Features

### Interact with Node via Command Line

KlayOracle is bundled with the kloc command, which is used to interact with the KlayOracle node. It currently supports the following commands:

- [Create a Klaytn wallet](https://klayoracle.gitbook.io/klayoracle-documentation/components/kloc-command) for a node, so that it can fulfill oracle requests.
- [Get node information](https://klayoracle.gitbook.io/klayoracle-documentation/components/kloc-command)
- [Run the Node](https://klayoracle.gitbook.io/klayoracle-documentation/components/kloc-command) to start watching for jobs and fulfilling Oracle requests from smart contracts.

![Kloc Terminal](https://github.com/alofeoluwafemi/klay-oracle-presentation/blob/master/images/demo-kloc.png)


### Lite Nodes

KlayOracle Node is very minimal in size and can watch and process hundreds of jobs easily (from current tests). This makes it easy to host your own node if you decide not to use publicly hosted ones. However, KlayOracle comes with a publicly hosted node which is currently free to access.

### Customizable Adapter
A KlayOracle adapter defines the job specification for getting specific off-chain data for an Oracle request. An adapter is made up of different parts, which are: 

* Status
* Name
* Job Type (Data Feed / Random Number)
* Adapter ID (Unique 32-length string)
* Oracle Address
* Feeds (Which defines rules to manipulate off-chain data to be returned to the Oracle contract)

![Kloc Data Feed](https://github.com/alofeoluwafemi/klay-oracle-presentation/blob/master/images/demo-feed.png)

Developers can easily create adapters of their own to get price feeds, random numbers, or beyond that, make HTTP requests for custom data intended to be passed to the smart contract e.g Weather Report data.

[Slide 5](https://github.com/alofeoluwafemi/klay-oracle-presentation/blob/master/Slide-5.md)
