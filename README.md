# Awesome EVM proof verifiers

> [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
> An awesome, curated list of (zk) proof verifiers implemented for the EVM

## Contents

- [Awesome EVM proof verifiers](#awesome-evm-proof-verifiers)
  - [Contents](#contents)
  - [Mission and vision](#mission-and-vision)
  - [Generic statements](#generic-statements)
    - [Groth16](#groth16)
    - [Plonk](#plonk)
    - [Halo2](#halo2)
    - [STARK](#stark)
    - [Nova](#nova)
  - [Specific statements](#specific-statements)
    - [Polynomial commitments](#polynomial-commitments)
    - [Verifiable delay functions](#verifiable-delay-functions-vdf)
    - [Signatures](#signature-verification)
    - [Sigma protocols](#sigma-protocols)
    - [Powers-of-tau and other common-reference string verifiers](#powers-of-tau-and-other-common-reference-string-verifiers)
    

## Mission and vision
In blockchain applications using (zero-knowledge) proof systems, proofs are stored and verified on-chain via smart contracts. This design makes the verifier vital. In deploying zero-knowledge proofs on blockchains, the verifier's correct implementation is crucial for the security of the proof system. An incorrect verifier (e.g., incorrect Fiat-Shamir transformation or omitted checks) jeopardizes the application, risking user funds.

This repository aims to catalog up-to-date verifiers for major, popular proof systems on the Ethereum Virtual Machine (EVM). This aids practitioners, researchers, and security experts in understanding deployed proof systems and evaluating EVM's proof verification capabilities.

For contributions guideline, see the Contributing.md file.

Inspired by Matter Lab's [Awesome zero-knowledge proofs](https://github.com/matter-labs/awesome-zero-knowledge-proofs) repository.

## Generic statements

### Groth16
- [Arkworks solidity verifier](https://github.com/Tetration-Lab/arkworks-solidity-verifier)
### Plonk
- [Consensys implementation](https://github.com/Consensys/plonk-solidity-audit)
- [Matter Labs implementation](https://github.com/matter-labs/solidity_plonk_verifier)
- [Recursive Plonk verifier](https://github.com/fluidex/solidity_recursive_plonk_verifier)
- [Plonky2](https://github.com/polymerdao/plonky2-solidity-verifier)
### Halo2
- [Halo2 verifier](https://github.com/privacy-scaling-explorations/halo2_solidity_verifier)
### STARK
### Nova
- [Lurk lab implementation](https://github.com/lurk-lab/solidity-verifier)

## Specific statements

### Polynomial and vector commitments 
- [KZG](https://github.com/weijiekoh/libkzg) 
- [Merkle trees](https://github.com/miguelmota/merkletreejs-solidity), [Alternative implementation](https://github.com/ameensol/merkle-tree-solidity), [with multiproofs](https://github.com/miguelmota/merkletreejs-multiproof-solidity)
- [Merkle-Patricia trie](https://github.com/lorenzb/proveth)
- [FRI polynomial commitment scheme](https://etherscan.io/address/0x3e6118da317f7a433031f03bb71ab870d87dd2dd#code) 

### Verifiable delay functions (VDF)
- [Wesolowski VDF](https://github.com/0xProject/VDF)

### Signature verification
- [ECDSA](https://github.com/miguelmota/sol-ecverify)
- [BLS](https://github.com/gakonst/solidity-bls), [libBLS](https://github.com/skalenetwork/libBLS), [solidity-bls](https://github.com/razor-network/solidity-bls)
- [Schnorr](https://github.com/noot/schnorr-verify)
- [RSA PKCS1](https://github.com/adria0/SolRsaVerify)
- [P256](https://github.com/alembic-tech/P256-verify-signature)
- [BGLS](https://github.com/Project-Arda/bgls-on-evm)
- [Ed25519](https://github.com/chengwenxi/Ed25519)

### Sigma protocols
- [Schnorr proof of knowledge](https://github.com/HarryR/solcrypto)
- [Schnorr proof of knowledge in hidden order groups](https://github.com/a16z/cicada)

### Powers-of-tau and other common-reference string verifiers
- [Powers-of-tau contribution correctness](https://github.com/a16z/evm-powers-of-tau)