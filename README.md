Solana Gossip Service
=====================

Simple example how to run the _GossipService_ to get the TPU nodes (validator identity and IP+port).

Gossip runs on port 8001 (default).

Run against testnet
===================
__Note: it takes very long for the gossip interaction to settle!__
```
 # use mango dallas node
 cargo run -- --gossip-entrypoint 139.178.82.223:8001 --output-file validators.bin
```

Example Node List
=================
```
- FunoozCzy3zV8t8cepfNzWBHYRtsvF65T4oCBMX1S45y: 69.197.17.58:28504
- 983hEVpz464mLff3NohfNYjw4NxN5U1kKv5yH1iGuA4: 69.197.7.39:8004
- D2NjDkcv8Y1dWGdtWAKPT4em2D3sYzM8AzMTpCG1RVf7: 69.197.6.12:8004
- tw2NAkBpTwST2c4NDW9xFmWgqSL5ErPy5QYbfYa3KXi: 147.75.93.165:8004
- 4wibT3LW6gVrRGjNDk1iqRh5ketvtHsQohDTcJXDHSx5: 72.20.2.19:8003
...
