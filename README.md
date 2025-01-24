# TRON Docker

This repository provides guidance and tools for the community to quickly get started with TRON network and development.

## Features

### Quick start for single FullNode

This repository includes Docker configurations to quickly start a single TRON FullNode connected to the Mainnet or NileNet. Simply follow the instructions to get your node up and running in no time.

### Private chain setup

You can also use this repository to set up a private TRON blockchain network. This is useful for development and testing purposes. The provided configurations make it straightforward to deploy and manage your own private chain.

### Node monitoring with Prometheus and Grafana

Monitoring the health and performance of your TRON nodes is made easy with integrated Prometheus and Grafana services. The repository includes configurations to set up these monitoring tools, allowing you to visualize and track various metrics in real time.

### Tools

We also provide tools to facilitate the CI and testing process:
- Gradle Docker: Using Gradle to automate the build and test processes for java-tron image.
- DB Fork: This tool helps launch a private Java-Tron network based on the state of the Mainnet database to support shadow fork testing.

## Getting Started

### Prerequisites

- Docker
- Docker Compose

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/tronprotocol/tron-docker.git
   cd tron-docker
   ```

2. **Start the services:**
   Navigate to the corresponding directory and follow the instructions in the respective README. Then you can easily start the services.
   - To start a single FullNode, use the folder [single_node](./single_node).
   - To set up a private TRON network, use the folder [private_net](./private_net).
   - To monitor the TRON node, use the folder [metric_monitor](./metric_monitor).
   - To use Gradle with Docker, check [gradle docker](./tools/docker/README.md).
   - To do shadow fork testing, check [db fork guidance](./tools/dbfork/README.md).

## Troubleshooting
If you encounter any difficulties, please refer to the [Issue Work Flow](https://tronprotocol.github.io/documentation-en/developers/issue-workflow/#issue-work-flow), then raise an issue on [GitHub](https://github.com/tronprotocol/tron-docker/issues). For general questions, please use [Discord](https://discord.gg/cGKSsRVCGm) or [Telegram](https://t.me/TronOfficialDevelopersGroupEn).

# Contributing

Contributions are welcome. All contributed code will be covered by the Apache License v2 of this project. Check [contribution](CONTRIBUTING.md) for more details.

# License

This repository is released under the [LGPLv3 license](https://github.com/tronprotocol/tron-docker/blob/main/LICENSE).
