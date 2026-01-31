# ZeldHash

[![Website](https://img.shields.io/badge/🌐_Website-zeldhash.com-blue?style=for-the-badge)](https://zeldhash.com)

A system that rewards Bitcoin transactions with aesthetically pleasing transaction IDs — those starting with leading zeros.

**100% decentralized. No premine. No VC. Just math.**

## Repositories

### ZeldHash-Specific

These repositories are purpose-built for the ZeldHash protocol:

| Repository | Description | Badges |
|------------|-------------|--------|
| [zeldhash-protocol](https://github.com/ouziel-slama/zeldhash-protocol) | Rust implementation of the ZELD protocol — storage and block parser agnostic | [![Crates.io](https://img.shields.io/crates/v/zeldhash-protocol.svg)](https://crates.io/crates/zeldhash-protocol) [![Docs.rs](https://docs.rs/zeldhash-protocol/badge.svg)](https://docs.rs/zeldhash-protocol) [![Coverage](https://codecov.io/gh/ouziel-slama/zeldhash-protocol/branch/main/graph/badge.svg)](https://codecov.io/gh/ouziel-slama/zeldhash-protocol) |
| [zeldhash-parser](https://github.com/ouziel-slama/zeldhash-parser) | Bitcoin blockchain parser optimized for ZELD balance computation | [![Crates.io](https://img.shields.io/crates/v/zeldhash-parser.svg)](https://crates.io/crates/zeldhash-parser)  [![Coverage](https://codecov.io/github/ouziel-slama/zeldhash-parser/graph/badge.svg?token=QKMVNDU06E)](https://codecov.io/github/ouziel-slama/zeldhash-parser) |
| [zeldhash-api](https://github.com/ouziel-slama/zeldhash-api) | REST API for querying ZELD balances and transaction data | [![Crates.io](https://img.shields.io/crates/v/zeldhash-api.svg)](https://crates.io/crates/zeldhash-api) [![Coverage](https://codecov.io/gh/ouziel-slama/zeldhash-api/branch/main/graph/badge.svg)](https://codecov.io/gh/ouziel-slama/zeldhash-api) |
| [zeldhash-miner](https://github.com/ouziel-slama/zeldhash-miner) | Bitcoin vanity transaction miner with GPU acceleration | [![Crates.io](https://img.shields.io/crates/v/zeldhash-miner.svg)](https://crates.io/crates/zeldhash-miner) [![npm](https://img.shields.io/npm/v/zeldhash-miner.svg)](https://www.npmjs.com/package/zeldhash-miner) [![Coverage](https://codecov.io/gh/ouziel-slama/zeldhash-miner/branch/main/graph/badge.svg)](https://codecov.io/gh/ouziel-slama/zeldhash-miner) |
| [zeldwallet](https://github.com/ouziel-slama/zeldwallet) | Browser wallet SDK with BIP32/39/44/84/86 and Taproot support | [![npm](https://img.shields.io/npm/v/zeldwallet.svg)](https://www.npmjs.com/package/zeldwallet) [![Coverage](https://codecov.io/gh/ouziel-slama/zeldwallet/graph/badge.svg?token=L5P886HP35)](https://codecov.io/gh/ouziel-slama/zeldwallet) |
| [zeldhash-website](https://github.com/ouziel-slama/zeldhash-website) | Official website and wallet interface | — |

### Generic Infrastructure

These repositories are general-purpose tools that can be used for any project:

| Repository | Description | Badges |
|------------|-------------|--------|
| [rollblock](https://github.com/ouziel-slama/rollblock) | High-performance key-value store with rollback capabilities | [![Crates.io](https://img.shields.io/crates/v/rollblock.svg)](https://crates.io/crates/rollblock) [![Docs.rs](https://docs.rs/rollblock/badge.svg)](https://docs.rs/rollblock) [![Coverage](https://codecov.io/gh/ouziel-slama/rollblock/branch/main/graph/badge.svg)](https://codecov.io/gh/ouziel-slama/rollblock) |
| [protoblock](https://github.com/ouziel-slama/protoblock) | Bitcoin block streaming and parsing infrastructure | [![Crates.io](https://img.shields.io/crates/v/protoblock.svg)](https://crates.io/crates/protoblock) [![Docs.rs](https://docs.rs/protoblock/badge.svg)](https://docs.rs/protoblock) [![Coverage](https://codecov.io/github/ouziel-slama/protoblock/graph/badge.svg?token=KB51O71CZR)](https://codecov.io/github/ouziel-slama/protoblock) |

## License

Licensed under either of Apache License 2.0 or MIT License at your option.

