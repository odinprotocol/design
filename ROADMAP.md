## v0

* Download and run Odin full node client
* Odin client pulls data out of Ethereum client running locally via JSON-RPC/IPC and stores it in local Postgres DB
* Build and share transformers, nodes can download and install them
* Simple transformers run as a separate process, written in Python/Go/JS
* Transformer process exposes a GraphQL endpoint

## v1

* Adds basic on-chain (Eth) transformer/validator marketplace, one-to-one links
* Transformers in WASM, add metering

## v2

* Adds incentivization, slashing
* Multiple validators (offers) per bid (consumer)
* Validator P2P link into a "shard" via libp2p

## v3

* Composable transformers

## v4

* Move towards general purpose read-write BFT DB, gossip changes as signed CRDT
