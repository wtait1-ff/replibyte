<p align="center"> <img src="assets/RepliByte%20Logo.png" alt="replibyte logo"/> </p>

<h3 align="center">Seed Your Development Database With Real Data ⚡️</h3>
<p align="center">Replibyte is a powerful tool to seed your databases </br>with real data and other cool features 🔥</p>

<p align="center">
<img src="https://img.shields.io/badge/stability-stable-green.svg?style=flat-square" alt="stable badge">
<img src="https://github.com/Qovery/replibyte/actions/workflows/build-and-test.yml/badge.svg?style=flat-square" alt="Build and Tests">
<a href="https://discord.qovery.com"> <img alt="Discord" src="https://img.shields.io/discord/688766934917185556?label=discord&style=flat-square"> </a>
</p>

## Features

- [x] Support data backup and restore for PostgreSQL, MySQL and MongoDB
- [x] Replace sensitive data with fake data
- [x] Works on large database (> 10GB) (read [Design](./docs/DESIGN.md))
- [x] Database Subsetting: Scale down a production database to a more reasonable size 🔥
- [x] Start a local database with the prod data in a single command 🔥
- [x] On-the-fly data (de)compression (Zlib)
- [x] On-the-fly data de/encryption (AES-256)
- [x] Fully stateless (no server, no daemon) and lightweight binary 🍃
- [x] Use [custom transformers](examples/wasm)

Here are the features we plan to support

- [ ] Auto-detect and version database schema change
- [ ] Auto-detect sensitive fields
- [ ] Auto-clean backed up data

## Getting Started

1. Initial setup: 
   1. [Install](https://www.replibyte.com/docs/getting-started/installation)
   2. [Configure](https://www.replibyte.com/docs/getting-started/configuration)
2. Step-by-step guides:
   1. [Create a dataset](https://www.replibyte.com/docs/guides/create-a-dataset)
   2. [Transform data](https://www.replibyte.com/docs/guides/transform-data)
   3. [Restore data](https://www.replibyte.com/docs/guides/restore-data)
   4. [Database subset](https://www.replibyte.com/docs/guides/database-subset)

## Demo

[![What is RepliByte](assets/video_.png)](https://www.youtube.com/watch?v=IKeLnZvECQw)

## Contributing

Check [here](https://www.replibyte.com/docs/contributing).

## Thanks

Thanks to all people sharing their ideas to make Replibyte better. We do appreciate it. I would also thank [AirByte](https://airbyte.com/),
a great product and a trustworthy source of inspiration for this project.

---

Replibyte is initiated and maintained by [Qovery](https://www.qovery.com?ref=replibyte-readme)
