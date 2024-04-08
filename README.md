# metachain-core
 Official Golang implementation of Metachain - a layer 1 Proof of Work blockchain designed for decentralization, innovation, and community-driven development. This repository hosts the core codebase for the Metachain network, providing a robust and secure foundation for decentralized applications (DApps), smart contracts, and token ecosystems.

# No uncle rewards
 We have excluded uncle rewards, so for mining uncle blocks miners will receive no coin. So the max supply will be fixed as 17M.

## Building the source

For prerequisites and detailed build instructions please read the [Installation Instructions](https://geth.ethereum.org/docs/getting-started/installing-geth).

Building `geth` requires both a Go (version 1.19 or later) and a C compiler. You can install
them using your favourite package manager. Once the dependencies are installed, run

```shell
make geth
```

or, to build the full suite of utilities:

```shell
make all
```

### Hardware Requirements

Minimum:

* CPU with 2+ cores
* 4GB RAM
* 1TB free storage space to sync the Mainnet
* 8 MBit/sec download Internet service

Recommended:

* Fast CPU with 4+ cores
* 16GB+ RAM
* High-performance SSD with at least 1TB of free space
* 25+ MBit/sec download Internet service


