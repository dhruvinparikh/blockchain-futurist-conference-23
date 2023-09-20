* starknet bounty- 2000, 1500 and 1000 USDC

* Starknet - fast, cheap and secure network

* L1 scaling problem
* once it proposes a new block - it gives validaty proof
* no need to re-execute the transaction, just validate the proof
* Showed execution vs verification - Sequencer(n) to validators(logn^2)
* STARK vs SNARK
 * parameters : verification, proof size, proving time etc
* TPS - 54.33 with milticall
* Starkware has Powerful ZK language - Cairo
* Cairo- provabale programs, computational integrity, verify w/o re-execution, turing complete, rust like syntax, strongly types and powerful complier, no need to know anything about zk

```
struct Rectanglr { <- custom data types
    height: u64,
    width: u64, <- scalar type
}
```

* startnet has native account abstract
 * every single wallet implements AA decoupling of signer and Account
 * Multi ops in single tx
 * Custom logic to verufy tx 
 * and more..

* Bundling user Ops
 * multicall on Starknet

* Smart wallets aka Account Abstraction (protocol level)
* Using AA, using turn your smartphone into a hardware wallet
* Hardware signer - secp256r1

* Join discord channel to get slides

* Starknet has vibrant ecosystem
 * Dojo - collection of tools for full on-chain games aka autonomous worls. Sozo(migration planner), Katana (local devnet)
 * Giza - On chain ML models, integrat existing models, dpeloy your own models
 * Beerus - starknet light net, turns a trusted RPC in to trustless. Uses helios for L1 information, small enough to be embeded, build with rust
 * herodotus - prove ownership of an L1 asset on L2 ala Storage proofs. A safer alternative to bridges, Any L1 asset at any block heoght
 * Kakarot - zk-EVM type 3 on top of Starknet. evm to cairoVM bytecode interpreter. Deploy solidity smart contracts to starknet w/o cairo rewrite.

 - By David Baretto
