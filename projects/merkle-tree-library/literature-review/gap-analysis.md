# Gap Analysis: Merkle Tree Implementations in Rust

_Last updated: 2026-02-12_

This document tracks identified gaps in existing research and implementations that this project aims to address. Updated as new papers are reviewed.

---

## Gap 1: No Unified Multi-Variant Library

**What exists:** rs-merkle (binary only), merkle_light (binary only, unmaintained), merkle-tree-rs (Ethereum airdrops only), rs-merkle-tree (append-only)

**What's missing:** A single library providing binary, sparse, and Patricia tries under one API with consistent trait abstractions.

**Our approach:** Layered trait hierarchy (HashFunction → MerkleTree → ProofGenerator/Verifier) with variant-specific modules.

---

## Gap 2: No Systematic Cross-Library Benchmarks

**What exists:** Individual papers benchmark their own approaches, but no published work compares Rust implementations head-to-head.

**What's missing:** Standardised benchmarks measuring construction, proof gen, proof verify, memory, and proof size across libraries and variants.

**Our approach:** Criterion benchmark suite with reproducible methodology, statistical rigour, and open datasets.

---

## Gap 3: Research Optimisations Not Integrated

**What exists in papers:**
- Adaptive tree restructuring — 30-35% improvement (Kuznetsov 2024)
- One-phase batch updates — 50% cost reduction (Ma 2023)
- Node batching — hex-tree performance with binary proofs (Ouvrard 2018)
- Parallel proof generation (Deng 2024)

**What's in libraries:** None of these are implemented in available Rust crates.

**Our approach:** Integrate node batching (SMT), incremental updates (binary), and explore parallel proof gen where applicable.

---

## Gap 4: Limited Hash Function Flexibility

**What exists:** Most libraries hardcode one hash or use cumbersome trait extensions.

**What's missing:** Clean, compile-time generic hash support for SHA-256, Keccak-256, BLAKE2 with zero overhead.

**Our approach:** Generic `HashFunction` trait with associated types, implemented for all three hash families.

---

## Gap 5: No Property-Based Testing

**What exists:** Basic unit tests in existing libraries.

**What's missing:** Property-based tests verifying cryptographic invariants (proof correctness, root determinism, collision behaviour).

**Our approach:** proptest-based test suite verifying invariants across randomised inputs.

---

## Papers Still Needed

_Papers to find to strengthen the gap analysis for Chapter 2:_

- [ ] Authenticated data structures beyond Merkle trees (accumulators, commitment schemes)
- [ ] Merkle trees in certificate transparency and IPFS
- [ ] Rust systems programming patterns (zero-copy, SIMD)
- [ ] ZK-proof-friendly hash functions (Poseidon)
- [ ] Original Merkle 1979 paper (full text)
- [ ] Ethereum Yellow Paper (formal MPT specification)
- [ ] More comparative hash function benchmarks
