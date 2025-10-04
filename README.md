# Arcium

## 1. Server Update : 

```bash
sudo apt update -y && sudo apt upgrade -y
```
## 2. Install Packages:

```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen file unzip lz4 -y
```

## Install Protobuf Compiler

```bash
sudo apt install -y protobuf-compiler
```

## Rust ; 

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

- 1, Enter.

```bash
source $HOME/.cargo/env
```
