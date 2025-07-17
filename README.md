# Awesome Walrus [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<a href="https://walrus.xyz/"><img alt="Walrus logo" src="media/logo.svg" align="right" width="150" /></a>

> A curated list of _awesome_ developer tools and infrastructure projects within the Walrus ecosystem.

Walrus is the next generation of data storage. It is secure, efficient, and decentralized.

> ⚠️ This warning icon means that the tool may not be functioning correctly at the moment. Please check these tools carefully.

[**Submit your own developer tool here**](CONTRIBUTING.md)

## Contents
- [SDKs](#sdks)
- [Visualization](#visualization)
- [Cli Tools](#cli-tools)
- [Walrus Sites](#walrus-sites)
- [Operator Tooling](#operator-tooling)

## SDKs
- [Mysten Labs Typescript SDK](https://sdk.mystenlabs.com/walrus) - The walrus SDK exposes high level methods for reading and writing blobs, as well as lower level methods for the individual steps in the process that can be used to implement more complex flows when you want more control to implement more optimized implementations.
- [Seal SDK](https://www.npmjs.com/package/@mysten/seal) - TypeScript SDK for [Seal](https://github.com/MystenLabs/seal), a decentralized secrets management service that secures your data using threshold encryption and on-chain access control.
- [Golang SDK](https://github.com/namihq/walrus-go) - Walrus Go SDK maintained by the Nami Cloud.
- [Tusky](https://github.com/tusky-io/ts-sdk) - TypeScript SDK for a complete file system on Walrus. It includes end-to-end encryption, file management and access control.
- [S3 Compatible Storage API](https://docs.nami.cloud/api-reference/storage/authentication) - S3 Compatible Walrus Storage API maintained by Nami Cloud. It supports Authentication, Bucket Operations, and Object Operations.
- [Standard Crypto Walrus Python SDK](https://github.com/standard-crypto/walrus-python) - A Python client for interacting with the Walrus HTTP API.

## Visualization
- Brightlystake - Online dashboards show state's of operators and shards
  - [Walrus Operators Dashboard](https://walrus-stats.brightlystake.com) - [Shards Dashboard](https://walrus-stats.brightlystake.com/shard-owners) - [Further Information](details/brightly-stake.md)
  - Load balanced SUI RPC with geo affinity enabled [https://lb-sui-testnet.brightlystake.com:443](https://lb-sui-testnet.brightlystake.com:443)
- [Walrus Grafana Tools](https://github.com/bartosian/walrus-tools) - A collection of Grafana tools for the Walrus ecosystem monitoring.
- [Walrus Endpoint Latency Dashboard](https://walrus-latency.nodeinfra.com) - Monitors the latency of public aggregator endpoints of Walrus.
- [Walrus ChainViz](https://walrus.chainviz.io) - ChainViz is an interactive explorer for the Walrus network, providing a comprehensive view of decentralized storage. It features a 3D globe for visualizing the network, live monitoring of nodes, aggregators, and publishers, as well as advanced filtering and search capabilities.
- [Walrus Blob Explorer](https://walrus.scan.space/) - A high-performance, web-based explorer by Space and Time that surfaces detailed storage, event, operator, and network analytics for Walrus Protocol. Features search-driven exploration, blob object metrics, real-time event feeds, operator dashboards, and time-series analytics. [Further Information](details/walrus_blob_explorer.md)
- [Blob Board](https://blobboard.wal.app) | [Code](https://github.com/reset-codes/blobboard) - A user-friendly dashboard for calculating and visualizing storage and write costs, as well as potential revenues, for the Walrus decentralized storage platform. Features cost calculations, storage projections, revenue estimations, and live crypto prices with USD conversions.

## Analytics API
- [Blockberry Walrus API](https://docs.blockberry.one/reference/walrus-quickstart) - The Blockberry Walrus API provides endpoints that reveal data about major entities on Walrus, including accounts, blobs, and analytics.

## Mainnet Publisher
- [Nami Cloud Mainnet Publisher](https://docs.nami.cloud/api-reference/walrus/introduction) - Nami Cloud provides easy access to Walrus services through API endpoints that allow you to interact with the Walrus network without running your own infrastructure.

## CLI Tools
- [Morsa](https://gitlab.com/blockscope-net/walrus-morsa) - A storage node monitoring CLI tool that alerts via PD, Slack, Discord and TG.
- [Suibase](https://suibase.io/walrus) - Scripts for peace of mind that every operations is done with the proper binary+config+wallet matching the network.
- [walrus-completion](https://github.com/StakinOfficial/walrus-completion) - A bash, zsh and Python completion for Walrus CLI.
- [wal-dev](https://wal-dev.pages.dev) - Npm package | Quick start toolkit for Walrus.
- [walrus-sites-deploy](https://www.npmjs.com/package/walrus-sites-deploy) - A Suibase-based CLI tool for seamless deployment of a site to Walrus Sites.

## Walrus Sites
- Walrus Sites GA - Reusable GitHub Action for deploying Walrus Sites
  - [GitHub](https://github.com/zktx-io/walrus-sites-ga) - [Marketplace](https://github.com/marketplace/actions/walrus-sites-ga) - [Examples](https://github.com/zktx-io/walrus-sites-ga-example) - [Further Information](details/walrus_sites_ga.md)

## Operator Tooling
- [Walrus Aggregator cache config](https://gist.github.com/DataKnox/983d834202e235dc25e9f5ae69e6c2fb) - Steps to configure the Walrus Aggregator Cache with NGinx and LetsEncrypt.
- [Walrus Monitoring Tools by Chainode Tech](https://github.com/Chainode/Walrus-Tools) - It enables monitoring of your Walrus Storage Node, Publisher, Aggregator, and the underlying hardware.
- [Walrus Ansible Deployment](https://github.com/imperator-co-org/walrus-ansible) - Ansible playbook for deploying a walrus node: Storage, Aggregator & Publisher with Docker-Compose.
- [Walrus Faucet](https://faucet.stakepool.dev.br/walrus) - A public faucet for developers who need test tokens in the Walrus ecosystem.
- [Walrus Commission Claim](https://github.com/suicore/operator-tools) - Enables operators to claim commission using Sui Wallet-compatible wallets, including: zkLogin wallets, Hardware wallets, Passphrase wallets.
