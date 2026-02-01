# ZeldHash

[![Website](https://img.shields.io/badge/🌐_Website-zeldhash.com-blue?style=for-the-badge)](https://zeldhash.com)

A system that rewards Bitcoin transactions with aesthetically pleasing transaction IDs — those starting with leading zeros.

**100% decentralized. No premine. No VC. Just math.**

## Repositories

### ZeldHash-Specific

These repositories are purpose-built for the ZeldHash protocol:

| Repository | Description | Badges |
|------------|-------------|--------|
| [zeldhash-protocol](https://github.com/zeldhash/zeldhash-protocol) | Rust implementation of the ZELD protocol — storage and block parser agnostic | [![Crates.io](https://img.shields.io/crates/v/zeldhash-protocol.svg)](https://crates.io/crates/zeldhash-protocol) [![Docs.rs](https://docs.rs/zeldhash-protocol/badge.svg)](https://docs.rs/zeldhash-protocol) [![Coverage](https://codecov.io/gh/zeldhash/zeldhash-protocol/branch/main/graph/badge.svg)](https://codecov.io/gh/zeldhash/zeldhash-protocol) |
| [zeldhash-parser](https://github.com/zeldhash/zeldhash-parser) | Bitcoin blockchain parser optimized for ZELD balance computation | [![Crates.io](https://img.shields.io/crates/v/zeldhash-parser.svg)](https://crates.io/crates/zeldhash-parser)  [![Coverage](https://codecov.io/github/zeldhash/zeldhash-parser/graph/badge.svg?token=QKMVNDU06E)](https://codecov.io/github/zeldhash/zeldhash-parser) |
| [zeldhash-api](https://github.com/zeldhash/zeldhash-api) | REST API for querying ZELD balances and transaction data | [![Crates.io](https://img.shields.io/crates/v/zeldhash-api.svg)](https://crates.io/crates/zeldhash-api) [![Coverage](https://codecov.io/gh/zeldhash/zeldhash-api/branch/main/graph/badge.svg)](https://codecov.io/gh/zeldhash/zeldhash-api) |
| [zeldhash-miner](https://github.com/zeldhash/zeldhash-miner) | Bitcoin vanity transaction miner with GPU acceleration | [![Crates.io](https://img.shields.io/crates/v/zeldhash-miner.svg)](https://crates.io/crates/zeldhash-miner) [![npm](https://img.shields.io/npm/v/zeldhash-miner.svg)](https://www.npmjs.com/package/zeldhash-miner) [![Coverage](https://codecov.io/gh/zeldhash/zeldhash-miner/branch/main/graph/badge.svg)](https://codecov.io/gh/zeldhash/zeldhash-miner) |
| [zeldwallet](https://github.com/zeldhash/zeldwallet) | Browser wallet SDK with BIP32/39/44/84/86 and Taproot support | [![npm](https://img.shields.io/npm/v/zeldwallet.svg)](https://www.npmjs.com/package/zeldwallet) [![Coverage](https://codecov.io/gh/zeldhash/zeldwallet/graph/badge.svg?token=L5P886HP35)](https://codecov.io/gh/zeldhash/zeldwallet) |
| [zeldhash-website](https://github.com/zeldhash/zeldhash-website) | Official website and wallet interface | — |

### Generic Infrastructure

These repositories are general-purpose tools that can be used for any project:

| Repository | Description | Badges |
|------------|-------------|--------|
| [rollblock](https://github.com/zeldhash/rollblock) | High-performance key-value store with rollback capabilities | [![Crates.io](https://img.shields.io/crates/v/rollblock.svg)](https://crates.io/crates/rollblock) [![Docs.rs](https://docs.rs/rollblock/badge.svg)](https://docs.rs/rollblock) [![Coverage](https://codecov.io/gh/zeldhash/rollblock/branch/main/graph/badge.svg)](https://codecov.io/gh/zeldhash/rollblock) |
| [protoblock](https://github.com/zeldhash/protoblock) | Bitcoin block streaming and parsing infrastructure | [![Crates.io](https://img.shields.io/crates/v/protoblock.svg)](https://crates.io/crates/protoblock) [![Docs.rs](https://docs.rs/protoblock/badge.svg)](https://docs.rs/protoblock) [![Coverage](https://codecov.io/github/zeldhash/protoblock/graph/badge.svg?token=KB51O71CZR)](https://codecov.io/github/zeldhash/protoblock) |

## License

Licensed under either of Apache License 2.0 or MIT License at your option.

