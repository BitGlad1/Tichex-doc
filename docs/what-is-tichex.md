# What is Tichex?

`tichex` is the name of the Go-Tichex application. It comes with 2 main entrypoints:

- `tichexd`: The Tichex Daemon, runs a full-node of the `tichex` application.
- `tichexcli`: The Tichex command-line interface, which enables interaction with a Tichex full-node.

`tichex` is built on the Cosmos SDK using the following modules:

- `x/auth`: Accounts and signatures.
- `x/bank`: Token transfers.
- `x/staking`: Staking logic.
- `x/mint`: Inflation logic.
- `x/distribution`: Fee distribution logic.
- `x/slashing`: Slashing logic.
- `x/gov`: Governance logic.
- `x/ibc`: Inter-blockchain transfers.
- `x/params`: Handles app-level parameters.

Next, learn how to [install Tichex](./installation.md).
