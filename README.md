# Awesome Noir

A curated list of resources for learning and programming in Noir.

⚠️  This repository or the contained links are not endorsed as safe and secure by Aztec Labs or the Noir team. Users are advised to exercise caution before utilizing any content or code provided herein.

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/Noir.svg?style=social&label=Follow%20%40Noir)](https://twitter.com/NoirLang)

## Contents

- [Awesome Noir](#awesome-noir)
  - [Contents](#contents)
  - [Official Resources](#official-resources)
  - [Get Coding](#get-coding)
    - [Dev Tools](#dev-tools)
    - [Boilerplates](#boilerplates)
    - [Proving Backends](#proving-backends)
    - [Benchmarks](#benchmarks)
    - [Libraries](#libraries)
      - [Data Types](#data-types)
        - [Numerics](#numerics)
        - [Dates \& Times](#dates--times)
      - [Data Type Manipulation](#data-type-manipulation)
        - [Numerics](#numerics-1)
        - [Bytes](#bytes)
        - [Text](#text)
      - [Cryptography](#cryptography)
        - [Hashes](#hashes)
        - [Message Authentication Code (HMAC)](#message-authentication-code-hmac)
        - [Encryption](#encryption)
        - [Signatures](#signatures)
        - [Merkle Trees](#merkle-trees)
        - [Randomness](#randomness)
        - [Pairing](#pairing)
      - [Ethereum](#ethereum)
      - [Machine Learning](#machine-learning)
      - [Miscellaneous](#miscellaneous)
  - [Learning](#learning)
    - [Learning By Doing](#learning-by-doing)
    - [Talks \& Workshops](#talks--workshops)
    - [Blog Posts \& Articles](#blog-posts--articles)
    - [International Resources](#international-resources)
  - [Projects](#projects)
    - [Authentication](#authentication)
    - [Gaming](#gaming)
    - [Governance](#governance)
    - [KYC](#kyc)
    - [Social](#social)
    - [Miscellaneous](#miscellaneous-1)
  - [Contribute](#contribute)
  - [License](#license)

---

## Official Resources

- [Docs](https://noir-lang.org/)
- [GitHub](https://github.com/noir-lang/noir)
- [Discord](https://discord.gg/RJdCBN373S)

## Get Coding

### Dev Tools

- [VS Code Extension](https://marketplace.visualstudio.com/items?itemName=noir-lang.vscode-noir) - Syntax highlight, error highlight, codelens, etc. ([Source Code](https://github.com/noir-lang/vscode-noir))
- [Neovim Plugin](https://github.com/noir-lang/noir-nvim) - Syntax highlight, error highlight, etc.
- [Emacs Plugin](https://melpa.org/#/noir-mode) - Syntax highlight ([Source Code](https://github.com/hhamud/noir-mode))
- [Zed Plugin](https://github.com/shuklaayush/zed-noir) - Syntax highlight, LSP support
- [Tree-sitter-noir](https://github.com/hhamud/tree-sitter-noir) - Tree-sitter grammar for Noir language
- [Emacs Tree-sitter Plugin](https://melpa.org/#/noir-ts-mode) - Syntax highlight ([Source Code](https://github.com/hhamud/noir-ts-mode))
- [hardhat-noir](https://www.npmjs.com/package/hardhat-plugin-noir) - Hardhat plugin ([Source Code](https://github.com/olehmisar/hardhat-noir))
- [Python2Noir](https://github.com/storswiftlabs/python2noir) - From Python to Noir language transpiler
- [noir_rs](https://github.com/visoftsolutions/noir_rs) - Rust-based zkSNARK Proving&Verifying tool for noir-lang
- [noir_java](https://github.com/visoftsolutions/noir_java) - Java-based zkSNARK Proving&Verifying tool for noir-lang (Java & Android)
- [noir_swift](https://github.com/visoftsolutions/noir_swift) - Swift-based zkSNARK Proving&Verifying tool for noir-lang (macOS & IOS & watchOS)
- [hunter](https://github.com/nfurfaro/hunter) - A tool for performing mutation-testing on Noir programs
- [merkle tree generator](https://github.com/eyalron33/mpz/) - A tool to help generate Noir-optimized merkle trees

### Boilerplates

- [noir-starter](https://github.com/noir-lang/noir-starter) - Template repository containing example projects using Noir (Vite + Hardhat, Foundry, etc.)
- [hardhat-noir-starter](https://github.com/olehmisar/hardhat-noir-starter) - Hardhat starter that seamlessly integrates with Noir.
- [noir-react-native-starter](https://github.com/madztheo/noir-react-native-starter) - Template repository containing an example minimal project using React Native
- [noir-library-starter](https://github.com/noir-lang/noir-library-starter) - Template used by the noir-lang org when creating internally maintained libraries

### Proving Backends

- [Barretenberg (UltraHonk / MegaHonk)](https://github.com/AztecProtocol/barretenberg) by Aztec Labs
- [Plonky2](https://github.com/blocksense-network/noir) by Blocksense
- [Plonky2](https://github.com/eryxcoop/acvm-backend-plonky2) by Eryx
- [Nova, HyperNova](https://github.com/privacy-scaling-explorations/sonobe/tree/main) by 0xPARC and PSE
- [Plonky3](https://github.com/vacekj/air-fried-gyatt) by Josef (needs updating)
- [Halo2](https://github.com/Ethan-000/halo2_backend) by Ethan (needs updating)
- [Groth16](https://github.com/TomAFrench/acvm-backend-groth16) (needs updating)
- [Marlin](https://github.com/noir-lang/marlin_arkworks_backend) (needs updating)

### Benchmarks

- [ZK-Bench](https://zkbench.dev) - Compare Noir to other ZK frameworks (Risc Zero, Leo, Miden, etc)

### Libraries

[Noir Directory](https://noir.directory) - A directory of Noir libraries.

#### Data Types

##### Numerics

- [BigNum](https://github.com/noir-lang/noir-bignum) - a library for arithmetic computations of large unsigned integers of any length
- [Fraction](https://github.com/resurgencelabs/fraction) - a library for accessing fractional number data type in Noir, allowing results that aren't whole numbers
- [ZKFloat](https://github.com/0x3327/ZKFloat) - a floating point library for Noir
- [Complex Numbers](https://github.com/doctoruber/complexnr) - This library offers a comprehensive suite of operations for complex numbers
- [Fixed Point Library](https://github.com/doctoruber/noir-fixed-point) - The FixedPoint library offers precise fixed-point arithmetic operations tailored for Noir

##### Dates & Times

- [Noir Dates](https://github.com/madztheo/noir-date) - A Noir library to parse and abstract away Dates
- [DateTimeNr](https://github.com/doctoruber/DateTimeNr) - A Noir library to parse and abstract away DateTime objects

#### Data Type Manipulation

##### Numerics

- [Matrix Operations](https://github.com/storswiftlabs/matrix_operations) - a library for matrix operations provides functionality for performing various matrix operations
- [Statistical Library](https://github.com/doctoruber/statnr) - Noir Statistical Library is a comprehensive library for statistical computations in the Noir language
- [Quantized arithmetic](https://github.com/storswiftlabs/quantized_arithmetic) - a library for quantized value operations of zero-point quantization

##### Bytes

- [U(int)2B(ytes)](https://github.com/colinnielsen/noir-u2b) - a library for converting `u8`->`u120`s to `[u8]` array

##### Text

- [Base64](https://github.com/vlayer-xyz/noir-base64) - a library for base64 encoding
- [JSON parser](https://github.com/noir-lang/noir_json_parser) - This library adheres to the revered [IETF RFC 8259](https://datatracker.ietf.org/doc/html/rfc8259) specifications, ensuring precise interpretation of JSON-friendly strings
- [String Utils](https://github.com/madztheo/noir-string-utils) - A wrapper for String in Noir that adds some useful methods for common string operations
- [Base64 Lib](https://github.com/Envoy-VC/noir_base64_lib) - Extension of `noir_base64` with support for Vectors and Base64 URL encoding and decoding.

#### Cryptography

##### Hashes

- [Griffin for BN254](https://github.com/TaceoLabs/noir-griffin) - zk-friendly hash function
- [Hash to curve](https://github.com/skaunov/hash_to_curve) - Noir lib for hashing to bigger curves
- [Poseidon{2}](https://github.com/TaceoLabs/noir-poseidon) - an improved implementation of Poseidon and its successor Poseidon2
- [SHA-1](https://github.com/michaelelliot/noir-sha1) - a library for generating hashes using SHA-1 hashing function
- [SHA-2](https://github.com/michaelelliot/noir-sha2) - a library for generating hashes using SHA-2 hashing function

##### Message Authentication Code (HMAC)

- [Noir HMAC](https://github.com/Envoy-VC/noir_hmac) - HMAC implementation in Noir Language.

##### Encryption

- [AES](https://github.com/TaceoLabs/noir-aes) - a (naive) implementation of AES encryption and decryption
- [ChaCha20 Implementation](https://github.com/SleepingShell/noir-chacha20) - a Noir implementation of ChaCha20 as defined by [RFC7539](https://www.rfc-editor.org/rfc/rfc7539)
- [ElGamal Encryption](https://github.com/jat9292/noir-elgamal/) - Exponential ElGamal Encryption on the Baby Jubjub curve
- [Hydra for BN254](https://github.com/TaceoLabs/noir-hydra) - symmetric encryption and decryption
- [ECIES](https://github.com/informalsystems/noir-ecies) - simple implementation of ECIES on the Baby Jubjub curve
- [ECDH](https://github.com/privacy-scaling-explorations/zk-kit.noir/tree/main/packages/ecdh) - simple implementation of ECDH on the Baby Jubjub curve

##### Signatures

- [RSA](https://github.com/noir-lang/noir_rsa) - RSA signature verification
- [BLS12_381 Elliptic Curve Pairing and Signature Verification Library](https://github.com/onurinanc/noir-bls-signature)
- [PLUME](https://github.com/distributed-lab/noir-plume) - Noir implementation of the https://blog.aayushg.com/nullifier/ library for zk-signatures
- [WebAuthn/Passkeys](https://github.com/olehmisar/noir_webauthn) - WebAuthn/Passkeys signature verification. Verifies signatures produced by `credentials.get`
- [JWT](https://github.com/saleel/noir-jwt) - Noir library to verify JWT tokens and prove claims. Currently only supports RS256 with 2048 bit keys. 

##### Merkle Trees

- [Merkle Root](https://github.com/tomoima525/noir-merkle-root) - a library for calculating Merkle root from given inputs. Using the Poseidon function for hashing
- [Sparse Merkle Tree Implementation](https://github.com/jordan-public/zk-optimized-sparse-merkle-tree) - a typescript library to generate optimized sparse merkle trees
- [Sparse Merkle Tree Verifier](https://github.com/vocdoni/smtverifier-noir) - a library for verification of sparse Merkle trees
- [Sparse Merkle Tree Verify/Add/Update/Delete](https://github.com/privacy-scaling-explorations/zk-kit.noir/tree/main/packages/merkle-trees) - a Noir library to verify (non-)membership proofs and add/update/delete leafs

##### Randomness

- [Cryptographically Secure Pseudo-Random Number Generator](https://github.com/doctoruber/CSPRNG)

##### Pairing

- [Pairing over BLS12-381](https://github.com/ewynx/noir_bls12_381_pairing) - Implementation of pairing over BLS12-381 that uses the new Noir [BigNum](https://github.com/noir-lang/noir-bignum) library

#### Ethereum

- [ECrecover](https://github.com/colinnielsen/ecrecover-noir) - a library to verify an ECDSA signature and return the source Ethereum address
- [Ethereum Storage Proof Verification](https://github.com/aragonzkresearch/noir-trie-proofs) - a library that contains the primitives necessary for RLP decoding (in the form of look-up table construction) and Ethereum state and storage proof verification (or verification of any trie proof involving 32-byte long keys)

#### Machine Learning

- [Convolution](https://github.com/storswiftlabs/convolution) - a library for Convolutional Neural Network (CNN) library in Noir, including Convolutional layers, Pooling layers, and Linear (fully connected) layers
- [ML](https://github.com/metavind/noir-ml) - a library for implementing neural networks in Noir
- [SKProof](https://github.com/0x3327/skproof) - a Scikit-learn compatible Python library for generating ZK proofs of execution
- [zkML-Noir](https://github.com/storswiftlabs/zkml-noir) - a library for Python ML model transcoding Noir, including various algorithms such as Decision tree, K-Means, XGBoost, FNN, CNN

#### Miscellaneous

- [Standard Library](https://github.com/noir-lang/noir/tree/master/noir_stdlib) - the Noir Standard Library
- [nodash](https://github.com/olehmisar/nodash) - a generic utility library. "Lodash for Noir"
- [Noir JWT](https://github.com/Envoy-VC/noir_jwt) - Verify JWTs and attest claims in Noir Language
- [Noir Social Verify](https://github.com/Envoy-VC/noir_social_verify) - Wrapper around zkemailnr to verify social accounts and extract details like X username, and emails.

## Learning

### Learning By Doing

- [Practice Exercises] [NoirGuardians](https://www.noirguardians.io/)
  - 3 quests that use storytelling and lore to teach basic programming in Noir, along with some advanced features that Noir offers
  - Get a first introduction to the Noir language, and learn how to integrate Noir programs into Solidity contracts
- [Educational Curriculum] [ZKCamp's Open Source Noir course](https://github.com/ZKCamp/aztec-noir-course)
  - 6 lectures to give participants the knowledge and skills necessary to build decentralized applications based on ZKPs using Noir
  - Lessons include ZKP Fundamentals; An Introduction to Aztec Ecosystem; Noir Basics; Building a Noir Application; and Advanced Noir
- [Video Series] [BattleZips-Noir](https://www.youtube.com/playlist?list=PLWACGbvIsEgnR2aUCr9i-PpmTVhF5Zuik) ([Source Code](https://github.com/BattleZips/BattleZips-Noir))
  - Walkthrough of building an on-chain Battleships game using zero-knowledge
  - Follow along and build your own game using Noir
- [Practice Exercises] [Circuit Examples](https://github.com/thor314/circuit-examples)
  - Demonstration of dot products & Merkle proofs in Noir, in comparison to Circom and RISC0
- [Educational Demo] [scaffold-eth-2-noir](https://github.com/Kryha/scaffold-eth-2-noir)
  - Small demo of a dApp with ZK-age restriction. UI, smart contracts and ZK-circuits.
  - Built with [scaffold-eth](https://github.com/scaffold-eth/scaffold-eth-2).

### Talks & Workshops

- [10 mins] [Writing Circuits with Noir](https://www.youtube.com/watch?v=I5M8LhOECpM&t=2879s) ([Source Code](https://github.com/vezenovm/basic_mul_noir_example))
  - Nargo setup
  - Basic Noir syntax
  - Noir interactions in TypeScript
- [20 mins] [Painless Zero-Knowledge Circuitry with Noir at ETHDam](https://www.youtube.com/watch?v=5KLTroMcldg&list=PLc5OGwyCUIhXny_mY4NPE5JfYNcTh8jUs&index=28)
  - Introduction to Noir
  - Simple demo and test
- [20 mins] [Private Value Transfer in 10 Lines](https://www.youtube.com/watch?v=wYqqXas8_O4) ([Source Code](https://github.com/vezenovm/simple_shield))
  - Tornado-like private asset transfer using Merkle proofs
- [25 mins] [Noir as a Smart Contract Language](https://www.youtube.com/watch?v=tYdUaCbACtk)
  - Noir as the smart contract language for the Aztec rollup
  - Noir smart contracts
- [45 mins] [Outlandish Noir Stuff; Workshop at ETHCC](https://www.youtube.com/watch?v=pdrZ7Y__obU)
  - How to use Noir to build a bunch of outlandish stuff
- [1 hr] [Circuit Safety and an Introduction to Noir](https://www.youtube.com/watch?v=rLvu61DA-hk)
  - Common circuit bugs
  - Proving system vulnerabilities
  - Unconstrained functions
- [1.5 hrs] [ZK dApps - Why, What and How?](https://www.youtube.com/watch?v=DpCbeGcX0cI)
- [1.5 hrs] [Sudoku in Noir](https://drive.google.com/file/d/1D4XCdiIZVjUW1JHDoMW3pG-15mgjMm9E/) ([Source Code](https://github.com/guipublic/crypdoku))
- [2 hrs] [ZK HACK III - Introduction to Noir](https://www.youtube.com/watch?v=5CziMfChveY) ([Source Code](https://github.com/joss-aztec/quadratic_voting_noir))
  - Code-together: Quadratic Voting
- [1.1 hrs] [Noir on Scroll Workshop](https://www.youtube.com/watch?v=xLQfMu-shYA) ([Part of Source Code](https://github.com/Turupawn/NoirScrollDemo))

### Blog Posts & Articles

- [Understanding the Technical Aspects of Aztec and Noir](https://hackmd.io/XZX9_pZ8Q1aa_ySDPeQopg)
- Noir 101 for Solidity devs in ([English](https://mirror.xyz/crisgarner.eth/IRRxnP-HVP-7qLZ-bTI2HRpKTmSRPCDl-Q6gm2NTj4g)) and ([Spanish](https://mirror.xyz/crisgarner.eth/Iek7PhbhU4WpIJ6eixFq80_7R6czH7fbdCoN0Bd7NfI))
- [Privacy-preserving KYC with Noir](https://medium.com/@tisura/privacy-preserving-kyc-57002ab8d3f2)
- [An incomplete guide to zk-KYC apps](https://medium.com/@tisura/an-incomplete-guide-to-zk-kyc-apps-d7b4c684795c)

### International Resources

- [Introduction to Noir in Spanish](https://www.youtube.com/watch?v=m4P-sAqa8_o)
   - ([Written Tutorial and Code](https://dev.to/turupawn/circuitos-de-aztec-noir-en-tu-navegador-zk-es-semana-3-78a))
- [Building a ZK dApp in Cantonese](https://www.youtube.com/watch?v=IAQrO1j20pg)
   - [Slides](https://docs.google.com/presentation/d/1Zh8McXfdjREg0Y6iG9Q1_d-8Sgi7QT_7gJdOSmLqEEI/)

## Projects

A curated list of projects powered by Noir.

### Authentication

- [SafeRecover](https://github.com/porco-rosso-j/safe-recovery-noir) - Recovery of ownership of Gnosis Safe accounts
- [ZCaptcha](https://github.com/signorecello/zcaptcha) - A ZK version of Captcha
- [ZKPic](https://github.com/0xrishabh/zkPic) - generate zero knowledge proofs for image edits
- [Safecat](https://neimanslab.org/2024-02-19/safecat.html) - a simple CLI tool to generate, sign, and verify digital signatures using EdDSA Baby Jubjub Elliptic Curve signatures and a Poseidon hash function

### Gaming

- [BattleZips](https://battlezips.com/) ([Source Code](https://github.com/BattleZips/BattleZips-Noir)) - On-chain Battleship
- [Dappicom](https://tonk-gg.github.io/dappicom-site/) - zk Nintendo Entertainment System (NES) emulation
- [Sudoku, Wordle, and Trivia](https://github.com/ruizehung/Zero-Knowledge-Sudoku-Wordle-Trivia) - Sudoku, Wordle, and Trivia games in Aleo and Noir

### Governance

- [Nouns Anonymous Voting](https://github.com/aragonzkresearch/nouns-anonymous-voting) - Anonymous voting research project for NounsDAO

### KYC

- [Educational zk-KYC app](https://github.com/tisura-labs/zk-kyc-app) - NoirJS app to check age, country and recent salaries.

### Social

- [FruityFriends](https://github.com/guelowrd/fruity-lib) - Various circuits (Proof of Intersection, Proof of Proximity, Proof of Proper Secret) to be used in social applications
- [Rate Limiting Nullifiers](https://github.com/Rate-Limiting-Nullifier/noir-rln) - a zero-knowledge gadget that enables spam prevention in anonymous environments

### Miscellaneous

- [Graphite](https://github.com/AlexCheema/Graphite) - Python tool for proving graph algorithms
- [zkVRF](https://github.com/zkvrf/zkvrf) - Provable random number generation service
- [Past hackathon winners](https://github.com/AztecProtocol/dev-rel/tree/main/hackathons#previous-winners)

## Contribute

Propose link additions by visiting [README.md](./README.md) and click the "pen" icon in the top right corner. Make changes to the file and follow the instructions to create a pull request.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

