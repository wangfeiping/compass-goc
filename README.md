# Compass

compass will launch as a consumer chain through a governance proposal in the `provider` chain. Read the [Consumer Chain Start Process](/docs/Consumer-Chain-Start-Process.md) page for more details about the workflow.

This project is based on the `cosmos/interchain-security` repo tag [v0.2.1](https://github.com/cosmos/interchain-security/releases/tag/v0.2.1). You can generate the binary following the [build instructions](https://github.com/cosmos/interchain-security#instructions).

## Build and Run Instructions

**Prerequisites**

```bash
## For OSX or Linux

# go 1.18 (https://formulae.brew.sh/formula/go)
# jq (optional, for testnet) (https://formulae.brew.sh/formula/jq)
# docker (optional, for integration tests, testnet) (https://docs.docker.com/get-docker/)
```

**Installing and running binaries**

```bash
# install interchain-security-pd and moed binaries
make install
# run provider
interchain-security-pd
# run consumer
compassd
```

## Compass Chain of Testnet Information

**We are launching the `compass` chain with the goal of testing `rly` (the `go` relayer). Please do not operate any other relayer (Hermes, etc.) with this chain.**

You can join the testnet following the [Compass Chain of Testnet Information](https://github.com/wangfeiping/ics-testnets/tree/main/game-of-chains-2022/compass)

