# Garden Grafana Stack

This project provides a Grafana stack using Garden, including Grafana, Loki, Tempo, and Mimir for local observability on a local Kubernetes cluster.

## Prerequisites

- [Garden](https://docs.garden.io/getting-started/installation)

## Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd garden-grafana-stack
    ```

2. Start the project:
    ```sh
    garden dev
    ```

3. Deploy the project in the Garden console:
    ```sh
    deploy
    ```

## TODO

- [x] Grafana
- [ ] Loki
- [ ] Tempo
- [ ] Mimir
- [ ] Local persisting
- [ ] Provisioning of dashboards and datasources