# Shelby Explorer Tools

A lightweight toolkit for interacting with the Shelby network explorer.

This repository provides simple utilities and scripts for monitoring events, tracking blobs, and analyzing storage activity on the Shelby decentralized storage network.

## About Shelby

Shelby is a decentralized **hot storage protocol** designed for high-speed data access in Web3 applications.
The network allows developers to store frequently accessed data in a distributed infrastructure while maintaining fast retrieval times.

Official Explorer: [https://explorer.shelby.xyz/](https://explorer.shelby.xyz/)

## Features

* Fetch latest **Blob Events**
* Monitor **storage providers**
* Track **network activity**
* Analyze **blob uploads**
* Simple API interaction scripts

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/shelby-explorer-tools.git
cd shelby-explorer-tools
```

Install dependencies:

```bash
npm install
```

## Usage

Run the event watcher:

```bash
node scripts/events.js
```

Example output:

```
New Blob Event Detected
Blob ID: 0x83a9...
Size: 2.3MB
Timestamp: 2026-03-08
```

## Project Structure

```
shelby-explorer-tools
│
├── scripts
│   ├── events.js
│   ├── blobs.js
│   └── providers.js
│
├── utils
│   └── api.js
│
└── README.md
```

## Use Cases

* Blockchain data analytics
* Monitoring Shelby storage activity
* Research on decentralized storage networks
* Building dashboards or bots

## Disclaimer

This project is **not affiliated with the Shelby team**.
It is an independent community tool built for research and experimentation.

## License

MIT License

