# Awesome EVM proof verifiers

> [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
> An awesome, curated list of (zk) proof verifiers implemented for the EVM

## Contents

- [Awesome EVM proof verifiers](#awesome-evm-proof-verifiers)
  - [Contents](#contents)
  - [General introduction](#general-introduction)
  - [Use cases](#use-cases)
  - [Generic statements](#snarks)
    - [Groth16](#groth16)
    - [Plonk](#plonk)
    - [Halo2](#halo2)
  - [Specific statements](#snarks)
    - [Polynomial commitments](#polycommits)
    - [Verifiable delay functions](#try-1)
        - [Wesolowski VDF](#wesolowski-vdf)

## Mission and vision
In blockchain applications using (zero-knowledge) proof systems, proofs are stored and verified on-chain via smart contracts. This design makes the verifier vital. In deploying zero-knowledge proofs on blockchains, the verifier's correct implementation is crucial for the security of the proof system. An incorrect verifier (e.g., incorrect Fiat-Shamir transformation or omitted checks) jeopardizes the application, risking user funds.

This repository aims to catalog up-to-date verifiers for major, popular proof systems on the Ethereum Virtual Machine (EVM). This aids practitioners, researchers, and security experts in understanding deployed proof systems and evaluating EVM's proof verification capabilities.

For contributions guideline, see the Contributing.md file.

Inspired by Matter Lab's [Awesome zero-knowledge proofs](https://github.com/matter-labs/awesome-zero-knowledge-proofs) repository.

## Generic statements

### Groth16
### Plonk
- AZTEC implementation
- [Matter Labs implementation](https://github.com/matter-labs/solidity_plonk_verifier)
- [Plonky2](https://github.com/polymerdao/plonky2-solidity-verifier)
### Halo2
- [Halo2 verifier](https://github.com/privacy-scaling-explorations/halo2_solidity_verifier)
### STARK

## Specific statements

### Polynomial and vector commitments 
- [KZG](https://github.com/weijiekoh/libkzg) 
- [Merkle trees](https://github.com/miguelmota/merkletreejs-solidity), [Alternative implementation](https://github.com/ameensol/merkle-tree-solidity), [with multiproofs](https://github.com/miguelmota/merkletreejs-multiproof-solidity)
- [Merkle-Patricia trie](https://github.com/lorenzb/proveth)
- FRI polynomial commitment scheme 

### Verifiable delay functions (VDF)
- Wesolowski VDF

### Signature verification
- [BLS](https://github.com/gakonst/solidity-bls), [libBLS](https://github.com/skalenetwork/libBLS)
- [Schnorr](https://github.com/noot/schnorr-verify)
- [RSA PKCS1](https://github.com/adria0/SolRsaVerify)
- [P256](https://github.com/alembic-tech/P256-verify-signature)
- [BGLS](https://github.com/Project-Arda/bgls-on-evm)

### Sigma protocols
- Discrete Logarithm Equality (Chaum-Pedersen)

### Powers-of-tau and other common-reference string verifiers
