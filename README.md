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

## Use cases

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
