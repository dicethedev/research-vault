# 🌳 High-Performance Merkle Tree Library for Blockchain Applications

> Development of an Optimized Merkle Tree Implementation Library with Multiple Variants and Proof Generation Capabilities

**Status:** 🟡 In Progress  
**Started:** February 2026  
**Institution:** MIVA Open University — Department of Software Engineering  
**Type:** Final Year Project (B.Sc. Software Engineering)

---

## Overview

This research project addresses the fragmentation in the blockchain developer ecosystem by developing the Optimized Merkle Tree Library (OMTL) in Rust. This comprehensive toolkit unifies high-performance variants, including Binary, Sparse, and Patricia trees, under a single, zero-cost abstraction API. By translating cutting-edge academic research into production-ready code, the project provides a modular framework for secure data integrity, optimized for modern blockchain scaling solutions like Layer-2 rollups and stateless clients.

## Research Questions

1. How can a trait-based architecture in Rust unify Binary, Sparse, and Patricia variants while maintaining zero-cost abstraction and cryptographic type safety?
2. What are the measurable impacts of "Pluggable Hashing" (SHA-256 vs. BLAKE3 vs. Keccak) on tree construction latency and proof generation across varying dataset scales?
3.To what extent do theoretical optimizations—specifically Adaptive Restructuring, One-Phase Batch Updates, and Path Length Analysis—improve real-world throughput and proof size in a systems-level implementation?

## Objectives

1. Design a unified, trait-based library architecture in Rust to provide a consistent API across binary, sparse, and Patricia-Merkle-tree variants while adhering to zero-cost abstraction principles.
2. Develop high-performance tree variants integrated with a modular cryptographic interface, supporting pluggable hash functions (SHA-256, Keccak-256, BLAKE3) and research-backed optimizations like node batching and incremental updates.
3. Evaluate the library's efficiency through systematic benchmarking against existing solutions like rs-merkle and merkle-light, specifically measuring construction latency, proof size, and memory consumption using the Criterion framework.
4. Publish the finalized implementation as an open-source crate, along with comprehensive documentation and a comparative analysis of tree-type trade-offs, to support the wider blockchain developer community.

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
- **Feb 24** — Project proposal approved by my supervisor. Initial literature review compiled (31 references). Proposal document drafted.
