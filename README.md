# Chain Network Node Setup

This document provides the necessary information to set up and run a Chain Network Node, including hardware requirements and support for various Ethereum networks.

## Hardware Requirements

To ensure optimal performance of your Chain Network Node, the following hardware configuration is recommended:

- **RAM**: Minimum of 16 GB
- **Storage**: Minimum of 2 TB SSD space

## Launching Node & Geth

To launch and start the Sepolia Chain Network node, use the following command:

```shell
docker compose up --build
```
This command initializes the Docker containers required for running the node, based on the configurations defined in docker-compose.yml file.

### Supported Networks

The following table provides an overview of the support status for various Ethereum Networks:

| Ethereum Network | Supported (✅) | Not Supported (❌) |
|:-----------------|:--------------:|:------------------:|
| Sepolia Testnet  |       ✅       |                    |
| Mainnet          |                |         ❌         |

- ✅ - Indicates full support for the network.
- ❌ - Indicates no support for the network.

