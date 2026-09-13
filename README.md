# base-l2-cli

> base · l2 · derive

[![Go 1.22+](https://img.shields.io/badge/go-1.22+-00ADD8)](https://go.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Build](https://img.shields.io/badge/build-passing-brightgreen)]()

Base L2 account CLI — local vault, stub RPC.

## Features

- ETH derivation path m/44'/60'/0'
- Local vault JSON with XOR wrap
- SHA-256 stand-in keys — no live RPC
- stdlib CLI via flag

## Prerequisites

- Go 1.22+
- Git

## Getting Started

```bash
git clone <repo-url>
cd base-l2-cli
make build
./bin/basel2 -help
```

## CLI Usage

```bash
make test
go run ./cmd/basel2 -help
```

## Project Structure

```
cmd/basel2/main.go
internal/config/config.go
internal/crypto/keys.go
internal/wallet/wallet.go
internal/wallet/wallet_test.go
```

## Background

Base Go notes use base-l2-cli.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.


---

## Topics

![base](https://img.shields.io/badge/base-111827?style=flat-square) ![l2](https://img.shields.io/badge/l2-111827?style=flat-square) ![cli](https://img.shields.io/badge/cli-111827?style=flat-square) ![base-l2-cli](https://img.shields.io/badge/base%20l2%20cli-111827?style=flat-square) ![cryptocurrency](https://img.shields.io/badge/cryptocurrency-111827?style=flat-square) ![wallet](https://img.shields.io/badge/wallet-111827?style=flat-square) ![blockchain](https://img.shields.io/badge/blockchain-111827?style=flat-square) ![web3](https://img.shields.io/badge/web3-111827?style=flat-square)

`base` `l2` `cli` `base-l2-cli` `cryptocurrency` `wallet` `blockchain` `web3` `bitcoin` `ethereum` `hd-wallet` `open-source` `golang` `go`

Search: base-l2-cli · base · l2 · derive · Base L2 account CLI — local vault, stub RPC.

---

<sub>Base L2 account CLI — local vault, stub RPC.</sub>
