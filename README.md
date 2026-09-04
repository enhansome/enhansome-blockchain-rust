# Awesome Blockchain Rust with stars

*Useful components for building blockchains in Rust. include: cryptography, distributed, p2p, consensus, etc*

* [Blockchains](#blockchains)
* [Blockchain Frameworks](#blockchain-frameworks)
* [Cross-Chain](#cross-chain)
* [Virtual Machines](#virtual-machines)
* [General-Purpose Consensus](#general-purpose-consensus)
* [P2P Network Libraries](#p2p-network-libraries)
* [Cryptography](#cryptography)
* [Layer2](#layer2)
* [Dapps](#dapps)
* [Other](#other)
* [Contribute](#contribute)
* [License](#license)

## Blockchains

* [Fuel](https://github.com/FuelLabs/fuel-core) ⭐ 56,866 | 🐛 201 | 🌐 Rust | 📅 2026-08-30.
  Rust full node implementation of the Fuel protocol.
* [Libra](https://github.com/libra/libra) ⭐ 16,668 | 🐛 368 | 🌐 Rust | 📅 2026-09-04.
  Global currency and financial infrastructure that empowers billions
  of people.
* [Solana](https://github.com/solana-labs/solana) ⚠️ Archived.
  Blockchain Rebuilt for Scale.
* [Sui Network](https://github.com/MystenLabs/sui) ⭐ 7,742 | 🐛 816 | 🌐 Rust | 📅 2026-09-04.
  A next-generation smart contract platform with high throughput, low
  latency, and an asset-oriented programming model powered by the Move
  programming language.
* [Polkadot](https://github.com/paritytech/polkadot) ⚠️ Archived.
  Polkadot Node Implementation.
* [Parity Ethereum](https://github.com/paritytech/parity-ethereum) ⚠️ Archived.
  The fast, light, and robust EVM and WASM client.
* [Grin](https://github.com/mimblewimble/grin) ⭐ 5,096 | 🐛 145 | 🌐 Rust | 📅 2026-08-11.
  Minimal implementation of the MimbleWimble protocol.
* [Lighthouse](https://github.com/sigp/lighthouse) ⭐ 3,467 | 🐛 538 | 🌐 Rust | 📅 2026-09-03.
  Fast and secure Ethereum 2.0 client.
* [Stacks 2.0](https://github.com/blockstack/stacks-blockchain) ⭐ 3,061 | 🐛 695 | 🌐 Rust | 📅 2026-09-04.
  Proof of Transfer blockchain from Blockstack.
* [NEAR](https://github.com/nearprotocol/nearcore) ⭐ 2,613 | 🐛 508 | 🌐 Rust | 📅 2026-09-04.
  NEAR Protocol - scalable and usable blockchain.
* [Namada](https://github.com/anoma/namada) ⭐ 2,514 | 🐛 219 | 🌐 Rust | 📅 2026-09-02.
  Proof-of-Stake L1 for interchain asset-agnostic privacy.
* [NYM](https://github.com/nymtech/nym) ⭐ 1,923 | 🐛 131 | 🌐 Rust | 📅 2026-09-04.
  Selective privacy via a mixnet preventing metadata analysis.
* [Internet Computer Protocol (ICP)](https://github.com/dfinity/ic) ⭐ 1,790 | 🐛 281 | 🌐 Rust | 📅 2026-09-04.
  The world’s first blockchain that runs at web speed and can increase
  its capacity without bound.
* [OpenEthereum](https://github.com/openethereum/openethereum) ⚠️ Archived.
  The Ethereum Rust client
* [Holochain](https://github.com/holochain/holochain) ⭐ 1,394 | 🐛 270 | 🌐 Rust | 📅 2026-09-02.
  The core Holochain framework written in rust, a container, and
  hdk-rust library for writing Zomes.
* [CITA](https://github.com/cryptape/cita) ⭐ 1,301 | 🐛 11 | 🌐 Rust | 📅 2022-12-10.
  A high performance blockchain kernel for enterprise users.
* [Exonum](https://github.com/exonum/exonum) ⭐ 1,245 | 🐛 44 | 🌐 Rust | 📅 2024-02-25.
  An extensible open-source framework for creating
  private/permissioned blockchain applications.
* [Nervos CKB](https://github.com/nervosnetwork/ckb) ⭐ 1,219 | 🐛 81 | 🌐 Rust | 📅 2026-09-04.
  Nervos CKB is a public permissionless blockchain, the common
  knowledge layer of Nervos network.
* [Ethrex](https://github.com/lambdaclass/ethrex) ⭐ 890 | 🐛 995 | 🌐 Rust | 📅 2026-09-03.
  Minimalist, fast and modular implementation of the Ethereum protocol in Rust. L1 and L2 execution client.
* [Parity Bitcoin](https://github.com/paritytech/parity-bitcoin) ⭐ 722 | 🐛 54 | 🌐 Rust | 📅 2023-06-14.
  The Parity Bitcoin client.
* [Conflux](https://github.com/Conflux-Chain/conflux-rust) ⭐ 718 | 🐛 73 | 🌐 Rust | 📅 2026-09-04.
  The Rust implementation of Conflux protocol.
* [Forest](https://github.com/ChainSafe/forest) ⭐ 697 | 🐛 145 | 🌐 Rust | 📅 2026-09-04.
  An implementation of Filecoin written in Rust.
* [Tendermint](https://github.com/informalsystems/tendermint-rs) ⭐ 671 | 🐛 177 | 🌐 Rust | 📅 2026-04-17.
  Tendermint is a high-performance blockchain consensus engine for
  Byzantine fault tolerant applications.
* [Zebra](https://github.com/ZcashFoundation/zebra) ⭐ 602 | 🐛 384 | 🌐 Rust | 📅 2026-09-04.
  An ongoing Rust implementation of a Zcash node.
* [Radix](https://github.com/radixdlt/radixdlt-scrypto) ⭐ 411 | 🐛 26 | 🌐 Rust | 📅 2026-09-03.
  Sharded smart contract DeFi platform.
* [Casper](https://github.com/casper-network/casper-node) ⭐ 400 | 🐛 192 | 🌐 Rust | 📅 2026-08-27.
  A decentralized L1 PoS blockchain designed to accelerate enterprise and developer adoption.
* [Gear](https://github.com/gear-tech/gear) ⭐ 264 | 🐛 117 | 🌐 Rust | 📅 2026-08-23.
  Computational component of Polkadot network.
* [Zero-chain](https://github.com/LayerXcom/zero-chain) ⭐ 261 | 🐛 59 | 🌐 Rust | 📅 2025-02-03.
  A privacy-preserving blockchain on Substrate.
* [CodeChain](https://github.com/CodeChain-io/codechain) ⭐ 256 | 🐛 64 | 🌐 Rust | 📅 2023-01-07.
  Programmable multi-asset chain.
* [Darwinia](https://github.com/darwinia-network/darwinia) ⭐ 245 | 🐛 29 | 🌐 Rust | 📅 2026-09-03.
  Relay chain of Darwinia Network, can connect to Polkadot as
  parachain in Polkadot Model.
* [Shasper](https://github.com/paritytech/shasper) ⚠️ Archived.
  Parity Shasper beacon chain implementation using the Substrate
  framework.
* [Witnet](https://github.com/witnet/witnet-rust) ⭐ 187 | 🐛 129 | 🌐 Rust | 📅 2026-05-19.
  Open source implementation of Witnet decentralized oracle network
  protocol in Rust.
* [Parity Zcash](https://github.com/paritytech/parity-zcash) ⚠️ Archived.
  Rust implementation of Zcash protocol.
* [Polymesh](https://github.com/PolymathNetwork/Polymesh) ⭐ 170 | 🐛 2 | 🌐 Rust | 📅 2026-09-03.
  The Polymesh blockchain (built on Substrate) is an identity orientated chain
  for the issuance, lifecycle management and settlement of regulated securities.
* [Mina Protocol](https://github.com/ChainSafe/mina-rs) ⚠️ Archived.
  A rust implementation of the mina succinct blockchain.
* [Nomic](https://github.com/nomic-io/nomic) ⭐ 154 | 🐛 18 | 🌐 Rust | 📅 2026-05-12.
  Nomic is a high-performance Bitcoin sidechain which is part of the
  Cosmos network.
* [RsNano](https://github.com/simpago/rsnano-node) ⭐ 107 | 🐛 9 | 🌐 Rust | 📅 2026-07-03.
  A rust port of Nano: the eco-friendly & feeless digital currency
* [Enigma](https://github.com/enigmampc/enigma-core) ⚠️ Archived secures the
  decentralized web.
* [Chainflip](https://github.com/chainflip-io/chainflip-backend/) ⭐ 70 | 🐛 48 | 🌐 Rust | 📅 2026-09-04.
  Native Cross-Chain Swaps.
* [Secret Network](https://github.com/SecretFoundation/SecretNetwork) ⭐ 29 | 🐛 0 | 📅 2020-11-14.
  A privacy-first blockchain that uses Rust to enable "secret contracts", ensuring data is encrypted while being processed on-chain.
* [xx-network](https://github.com/xx-labs/xxchain) ⭐ 19 | 🐛 0 | 🌐 Rust | 📅 2026-01-28.
  Post-quantum blockchain, mixnet privacy preventing metadata analysis. (Substrate rust+go)
* [Bitcoin Cash](https://github.com/be-cash/bitcoin-cash) ⭐ 15 | 🐛 0 | 🌐 Rust | 📅 2021-01-26.
  A library for creating and parsing Bitcoin Cash transactions.
* [Internet of People](https://github.com/Internet-of-People/iop-rs) ⭐ 14 | 🐛 0 | 🌐 Rust | 📅 2026-07-30.
  Decentralized software stack that provides the building blocks and
  tools to support a decentralized society.
* [Aleo](https://github.com/AleoNet/snarkOS) ⭐ 1 | 🐛 0 | 📅 2026-05-27.
  Decentralized operating system for zero-knowledge applications.
* [Aleph Zero](https://github.com/aleph-zero-foundation).
  DAG, PoS, snark smart contracts (substrate based).
* [Anoma.network](https://github.com/anoma).
  PoS blockchain with privacy.
* [Aptos Network](https://github.com/aptos-labs).
  Building the safest and most scalable Layer 1 blockchain..
* [Concordium](https://github.com/Concordium).
  Privacy centric (zk) PoS chain, yet with built in identities and rust smart contracts.
* [Dusk.network](https://github.com/dusk-network).
  Privacy PoS using zk (plonk).
* [MultiversX](https://github.com/multiversx).
  Sharded Smart Contracts execution platform with a PoS consensus mechanism.
* [Interledger](https://github.com/interledger-rs/interledger-rs).
  An easy-to-use, high-performance Interledger implementation written
  in Rust.
* [Mir Protocol](https://github.com/mir-protocol).
  A succinct blockchain powered by zero-knowledge proofs. (plonk based)
* [Setheum](https://github.com/Setheum-Labs/Setheum).
  SETHEUM : “Secure Evergreen Truthful Heterogeneous Economically Unbiased Market”
  is an Ethical DeFi-friendly Blockchain (built on Substrate) working on achieving
  mass adoption, security, scalability, affordability, inclusivity and ethical DeFi Governance.
* [Tari](https://github.com/tari-project).
  The Tari Digital Assets Protocol.

## Blockchain Frameworks

* [Substrate](https://github.com/paritytech/substrate) ⚠️ Archived.
  The platform for blockchain innovators.
* [Anchor](https://github.com/coral-xyz/anchor) ⭐ 5,126 | 🐛 139 | 🌐 Rust | 📅 2026-09-03
  is a framework for Solana's Sealevel runtime providing several convenient developer tools for writing smart contracts.
* [Tendermint ABCI](https://github.com/informalsystems/tendermint-rs/tree/master/abci) ⭐ 671 | 🐛 177 | 🌐 Rust | 📅 2026-04-17.
  Tendermint ABCI server, written in the Rust programming language.
* [slingshot](https://github.com/stellar/slingshot) ⚠️ Archived.
  A new blockchain architecture under active development, with a
  strong focus on scalability, privacy and safety.
* [Trident](https://github.com/Ackee-Blockchain/trident) ⭐ 402 | 🐛 19 | 🌐 Rust | 📅 2026-05-18.
  Fuzzing framework for Solana smart contracts.
* [Orga](https://github.com/nomic-io/orga) ⭐ 174 | 🐛 20 | 🌐 Rust | 📅 2025-01-25.
  A high-performance state machine engine designed for
  Tendermint-based blockchain applications.

## Cross-Chain

* [Hermes](https://github.com/informalsystems/hermes) ⭐ 506 | 🐛 220 | 🌐 Rust | 📅 2025-10-29.
  Rust implementation of an Inter-Blockchain Communication (IBC) relayer.
* [ibc-rs](https://github.com/cosmos/ibc-rs) ⭐ 224 | 🐛 116 | 🌐 Rust | 📅 2025-07-10.
  Rust implementation of the Inter-Blockchain Communication (IBC) protocol.
* [AtomicDEX](https://github.com/KomodoPlatform/atomicDEX-API) ⭐ 125 | 🐛 417 | 🌐 Rust | 📅 2026-07-27.
  Cross-chain and cross-protocol p2p orderbook based decentralized exchange and interoperability bridge (self-custodial).
* [Hyperlane](https://github.com/hyperlane-xyz/hyperlane-monorepo) ⭐ 74 | 🐛 959 | 🌐 TypeScript | 📅 2026-09-04.
  Framework for permissionless, modular interoperability. The offchain clients are written in Rust, as well as the smart contracts for Solana VM and CosmWasm.
* [Comit](https://github.com/comit-network/).
  An open protocol facilitating trustless cross-blockchain applications.

## Virtual Machines

* [Wasmer](https://github.com/wasmerio/wasmer) ⭐ 21,013 | 🐛 250 | 🌐 Rust | 📅 2026-09-03.
  A convenient Rust wrapper over WebAssembly backends.
* [Wasmtime](https://github.com/CraneStation/wasmtime) ⭐ 18,594 | 🐛 845 | 🌐 Rust | 📅 2026-09-04.
  Standalone JIT-style runtime for WebAssembly, using Cranelift.
* [EVM Parity](https://github.com/paritytech/parity-ethereum/tree/master/evmbin) ⚠️ Archived.
  Parity implementation of EVM.
* [Lunatic](https://github.com/lunatic-solutions/lunatic) ⭐ 4,886 | 🐛 48 | 🌐 Rust | 📅 2025-03-29.
  Erlang-inspired runtime for WebAssembly.
* [Wasmi](https://github.com/paritytech/wasmi) ⭐ 2,280 | 🐛 27 | 🌐 Rust | 📅 2026-09-01.
  WebAssembly interpreter.
* [CosmWasm](https://github.com/CosmWasm/cosmwasm) ⭐ 1,145 | 🐛 43 | 🌐 Rust | 📅 2026-08-25.
  Multi-chain smart contract platform built for the Cosmos ecosystem.
* [Polygon Miden](https://github.com/maticnetwork/miden) ⭐ 770 | 🐛 187 | 🌐 Rust | 📅 2026-09-04.
  SNARK based VM.
* [CKB-VM](https://github.com/nervosnetwork/ckb-vm) ⭐ 423 | 🐛 13 | 🌐 Rust | 📅 2026-09-03.
  RISC-V virtual machine.
* [FVM](https://github.com/filecoin-project/ref-fvm) ⭐ 423 | 🐛 195 | 🌐 Rust | 📅 2026-09-04.
  The Filecoin Virtual Machine is a hypervisor-inspired Wasm execution environment that supports multiple runtimes, including the EVM.
* [FuelVM](https://github.com/FuelLabs/fuel-vm) ⭐ 370 | 🐛 44 | 🌐 Rust | 📅 2026-07-17.
  Interpreter for the FuelVM, a blazingly fast blockchain virtual machine.
* [Zinc](https://github.com/matter-labs/zinc) ⚠️ Archived.
  Zinc zk smart contract language.
* [SVM](https://github.com/spacemeshos/svm) ⚠️ Archived
  Spacemesh Virtual Machine.
* [Bithoven](https://github.com/ChrisCho-H/bithoven) ⭐ 43 | 🐛 5 | 🌐 Rust | 📅 2026-02-25.
  A High-Level, Imperative Language for Bitcoin Smart Contracts, featuring an LR(1) parser with static analysis for compile-time safety.

## General-Purpose Consensus

* [Raft](https://github.com/pingcap/raft-rs) ⭐ 3,384 | 🐛 78 | 🌐 Rust | 📅 2026-05-13.
  Raft distributed consensus algorithm implemented in Rust.
* [Honey Badger](https://github.com/poanetwork/hbbft) ⭐ 369 | 🐛 44 | 🌐 Rust | 📅 2024-01-06.
  An implementation of the paper "Honey Badger of BFT Protocols" in
  Rust.
* [Narwhal](https://github.com/MystenLabs/narwhal) ⚠️ Archived.
  The consensus layer used by Sui.

## P2P Network Libraries

* [rust-libp2p](https://github.com/libp2p/rust-libp2p) ⭐ 5,610 | 🐛 294 | 🌐 Rust | 📅 2026-08-31.
  The Rust Implementation of the libp2p networking stack.
* [crust](https://github.com/maidsafe/crust) ⚠️ Archived.
  Reliable P2P network connections in Rust with NAT traversal. One of
  the most needed libraries for any server-less / decentralised
  projects.
* [qp2p](https://github.com/maidsafe/qp2p) ⭐ 420 | 🐛 8 | 🌐 Rust | 📅 2023-03-20.
  Peer-to-peer communications library for Rust based on QUIC protocol.
* [sn\_routing](https://github.com/maidsafe/sn_routing) ⚠️ Archived.
  Routing - specialised storage DHT.
* [Tentacle](https://github.com/driftluo/tentacle) ⭐ 227 | 🐛 1 | 🌐 Rust | 📅 2026-08-18.
  A multiplexed p2p network framework that supports custom protocols
* [P2P NAT-Traversal](https://github.com/ustulation/p2p) ⭐ 152 | 🐛 5 | 🌐 Rust | 📅 2018-11-27.
  NAT Traversal techniques for p2p communication.
* [chamomile](https://github.com/placefortea/chamomile) ⭐ 124 | 🐛 13 | 🌐 Rust | 📅 2025-09-19.
  P2P library. Support build robust stable connection on
  p2p/distributed network.

## Cryptography

* [Microsoft Nova](https://github.com/microsoft/Nova) ⭐ 862 | 🐛 25 | 🌐 Rust | 📅 2026-09-03.
  Rust recursive snark without trusted setup.
* [OpenZKP](https://github.com/0xProject/OpenZKP) ⚠️ Archived.
  Pure Rust implementations of Zero-Knowledge Proof systems.
* [Awesome Cryptography Rust](https://github.com/rust-cc/awesome-cryptography-rust) ⭐ 587 | 🐛 1 | 📅 2026-07-01.
* [Za!](https://github.com/adria0/za) ⚠️ Archived.
  An experimental rust zksnarks compiler with embeeded bellman-bn128
  prover.
* [Dalek Cryptography](https://github.com/dalek-cryptography).
* [Arkworks](https://github.com/arkworks-rs).
  An ecosystem for developing and programming with zkSNARKs

## Layer2

* [zkSync](https://github.com/matter-labs/zksync) ⭐ 4,926 | 🐛 106 | 🌐 Rust | 📅 2026-05-08.
  Matter Labs' scaling eth L2 engine secured by zero-knowledge proofs.
* [Noir language](https://github.com/noir-lang/noir) ⭐ 1,397 | 🐛 806 | 🌐 Rust | 📅 2026-09-04.
  Noir is a Domain Specific Language for SNARK proving systems. (Aztec eth L2)
* [Rust-Lightning](https://github.com/rust-bitcoin/rust-lightning) ⭐ 1,372 | 🐛 274 | 🌐 Rust | 📅 2026-09-04
  is a Bitcoin Lightning library written in Rust.
  The main crate, lightning, does not handle networking,
  persistence, or any other I/O. Thus, it is runtime-agnostic,
  but users must implement basic networking logic,
  chain interactions, and disk storage.
* [Penumbra](https://github.com/penumbra-zone/penumbra) ⭐ 482 | 🐛 203 | 🌐 Rust | 📅 2026-01-24.
  PoS network providing privacy to the Cosmos ecosystem.
* [Arbitrum's arb-os](https://github.com/OffchainLabs/arb-os) ⚠️ Archived
  ArbOS is the "operating system" that runs an eth Layer 2 on an Arbitrum chain,

## Dapps

* [Serum-dex](https://github.com/project-serum/serum-dex) ⭐ 696 | 🐛 65 | 🌐 Rust | 📅 2024-06-07.
  A decentralized exchange built on Solana.
* [ink!athon](https://github.com/scio-labs/inkathon) ⭐ 230 | 🐛 2 | 🌐 TypeScript | 📅 2025-12-12.
  Full-Stack DApp Boilerplate for Substrate and ink! Smart Contracts.
* [SewUp](https://github.com/second-state/SewUp) ⭐ 54 | 🐛 48 | 🌐 Rust | 📅 2023-09-11.
  A library to help you build your Ethereum webassembly contract with
  Rust and just like develop in a common backend.
* [Sienna Network](https://github.com/SiennaNetwork/SiennaNetwork).
  A privacy-first and cross-chain decentralized finance platform where
  you can privately swap, lend and convert your tokens into their
  private equivalent.

## Other

* [abscissa](https://github.com/iqlusioninc/abscissa) ⭐ 593 | 🐛 30 | 🌐 Rust | 📅 2026-04-06.
  Micro-framework for CLI tools with strong focus on security.
* [ERC-4337 Bundler](https://github.com/Vid201/aa-bundler/) ⭐ 273 | 🐛 34 | 🌐 Rust | 📅 2025-08-18.
  An ongoing Rust implementation of an ERC-4337 (Account Abstraction) Bundler.
* [merk](https://github.com/nomic-io/merk) ⭐ 249 | 🐛 17 | 🌐 Rust | 📅 2024-12-18.
  High performance Merkle key/value store written in Rust, based on
  RocksDB.
* [Solana VS Code Extension](https://github.com/Ackee-Blockchain/solana-vscode) ⭐ 38 | 🐛 4 | 🌐 Rust | 📅 2026-04-01.
  VS Code extension for Solana with built-in static analysis detectors and fuzzing coverage visualization.
* [tesseracts](https://github.com/adria0/tesseracts).
  A small block explorer for geth PoAs written in rust.

## Contribute

Contributions are most welcome.

GitHub: [Awesome Blockchain
Rust](https://github.com/rust-in-blockchain/awesome-blockchain-rust) ⭐ 2,813 | 🐛 13 | 📅 2026-05-17

## License

[![Creative Commons
License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0
International License](http://creativecommons.org/licenses/by/4.0/).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-04._
