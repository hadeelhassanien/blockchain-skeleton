# python-blockchain-sim

A minimal single-node blockchain simulation built from scratch in Python.

## What it does
- Creates a genesis block on initialization
- Supports adding transactions to a pending pool
- Mines new blocks using a basic **Proof of Work** algorithm
- Validates each block's hash and chain linkage before appending

## Run it

```bash
python blockchain.py
```

## Concepts demonstrated
- SHA-256 hashing
- Nonce-based Proof of Work
- Block chaining via `previous_hash`
- Transaction pooling and mining