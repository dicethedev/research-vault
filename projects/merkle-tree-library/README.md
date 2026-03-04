# 🌳 High-Performance Merkle Tree Library for Blockchain Applications

> Development of an Optimized Merkle Tree Implementation Library with Multiple Variants and Proof Generation Capabilities

**Status:** 🟡 In Progress  
**Started:** February 2026  
**Institution:** MIVA Open University — Department of Software Engineering  
**Type:** Final Year Project (B.Sc. Software Engineering)

---

## Overview

This research project focuses on developing a comprehensive, high-performance Merkle tree library in Rust that implements multiple tree variants (binary, sparse, and Patricia tries), supports multiple cryptographic hash functions, and provides rigorous benchmarking infrastructure. The library will be published on [crates.io](https://crates.io) as an open-source contribution to the blockchain developer ecosystem.

## Research Questions

1. How can multiple Merkle tree variants be unified under a single trait-based API without sacrificing type safety or performance?
2. What are the measurable performance tradeoffs between binary, sparse, and Patricia Merkle trees across different hash functions and data sizes?
3. How do research-backed optimisations (node batching, incremental updates, parallel proof generation) translate to real-world performance improvements in a Rust implementation?

## Objectives

1. Design and implement a unified trait-based architecture supporting binary, sparse, and Patricia Merkle trees
2. Develop optimised implementations incorporating research-backed techniques
3. Implement pluggable hash function support (SHA-256, Keccak-256, BLAKE2)
4. Create a comprehensive Criterion benchmarking suite with comparative analysis
5. Publish the library on crates.io with documentation and a research paper

## Project Navigation

```
merkle-tree-library/
├── README.md               ← You are here
├── proposal/               ← Research proposals
│   └── v1-initial-proposal.md
├── literature-review/      ← Paper notes and gap analysis
│   ├── papers/             ← Individual paper summaries
│   └── gap-analysis.md     ← Running gap analysis
├── findings/               ← Research findings and results
├── artifacts/              ← Code, benchmarks, diagrams
│   ├── code/               ← Prototype code and snippets
│   ├── benchmarks/         ← Benchmark results and data
│   └── diagrams/           ← Architecture and design diagrams
└── references/             ← BibTeX and reference management
    └── references.bib
```

## Timeline

| Phase | Weeks | Status |
|-------|-------|--------|
| Core Infrastructure (traits, hashes, CI) | 1-2 | ⚪ Not Started |
| Binary Merkle Tree | 3-4 | ⚪ Not Started |
| Sparse Merkle Tree | 5-6 | ⚪ Not Started |
| Merkle Patricia Trie | 7-8 | ⚪ Not Started |
| Benchmarking & Optimisation | 9-10 | ⚪ Not Started |
| Documentation & Publication | 11-12 | ⚪ Not Started |

## Key References

See [`references/references.bib`](./references/references.bib) for the full list.

Core papers informing this work:
- Kuznetsov et al. (2024) — Adaptive Merkle trees for blockchain scalability
- Dahlberg et al. (2016) — Efficient Sparse Merkle Trees
- Ma et al. (2023) — One-Phase Batch Update on SMTs for Rollups
- Deng et al. (2024) — GPU-Accelerated Merkle Patricia Trie

---

## Research Log

_Reverse chronological — newest entries at the top._

### February 2026
- **Feb 12** — Project proposal approved by supervisor. Initial literature review compiled (31 references). Proposal document drafted.
