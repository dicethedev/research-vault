# 📚 Digital Library: Research & Specifications

This document provides direct access to the source papers utilized for the OMTL implementation. Files are categorized by their primary contribution to the project architecture.

## 1. Foundational & Standards
* **1979_Merkle_CertifiedDigitalSignatures.pdf** [View Paper](https://doi.org/10.1007/0-387-34805-0_21) | [Alternate Link](https://www.ralphmerkle.com/papers/Thesis1979.pdf)  
    *Purpose: Core logic for $O(\log n)$ proof paths.*

* **2008_Nakamoto_BitcoinWhitepaper.pdf** [View Paper](https://bitcoin.org/bitcoin.pdf)  
    *Purpose: SPV (Simple Payment Verification) and transaction batching logic.*

* **2014_Wood_Ethereum_YellowPaper.pdf** [View Paper](https://ethereum.github.io/yellowpaper/paper.pdf)  
    *Purpose: Formal specification for Merkle Patricia Trie (MPT) and RLP.*

## 2. Optimization & Adaptive Trees
* **2024_Kuznetsov_AdaptiveMerkleTrees.pdf** [View Paper](https://doi.org/10.1016/j.iot.2024.101267)  
    *Purpose: Logic for trees that restructure based on access frequency.*

* **2024_Cassuto_TrafficAwareMerkleTrees.pdf** [View Paper](https://eprint.iacr.org/2024/1451)  
    *Purpose: Reducing proof sizes based on real-world network traffic.*

* **2025_Kuznetsov_OptimizingProofSize.pdf** [View Paper](https://doi.org/10.3390/fi17020072)  
    *Purpose: Probabilistic framework for shrinking path lengths.*

* **2023_Nguyen_OptimizingStructure_DC.pdf** [View Paper](https://doi.org/10.1007/978-3-031-41456-5_1)  
    *Purpose: Mathematical approach to tree structure optimization.*

## 3. Sparse Merkle Trees & Rollups
* **2018_Buterin_OptimizingSparseMerkleTrees.pdf** [View Post](https://ethresear.ch/t/optimizing-sparse-merkle-trees/3751)  
    *Purpose: Shortcut nodes and default hash caching for SMTs.*

* **2023_Ma_OnePhaseBatchUpdates.pdf** [View Paper](https://doi.org/10.48550/arXiv.2310.13328)  
    *Purpose: Reducing Layer-2 update costs by 50%.*

* **2016_Dahlberg_EfficientSparseMerkleTrees.pdf** [View Paper](https://eprint.iacr.org/2016/683)  
    *Purpose: Caching strategies for non-membership proofs.*

## 4. Hashing & Cryptographic Performance
* **2024_Pun_HashAlgorithmComparison.pdf** [View Paper](https://doi.org/10.30880/aitcs.2024.05.01.002)  
    *Purpose: Benchmark data for SHA-256, Keccak, and BLAKE.*

* **2013_Aumasson_BLAKE2_RFC7693.pdf** [View RFC](https://www.rfc-editor.org/rfc/rfc7693)  
    *Purpose: Technical spec for high-speed BLAKE2 implementation.*

* **2024_Deng_AcceleratingMPT_GPU.pdf** [View Paper](https://doi.org/10.14778/3659437.3659441)  
    *Purpose: Identifying bottlenecks in CPU-based Patricia Tries.*

## 5. Rust Systems & Development
* **2023_Klabnik_RustProgrammingLanguage.pdf** [Online Version](https://doc.rust-lang.org/book/)  
    *Purpose: Implementation of Zero-Cost Abstractions and Safety.*

---
**Note:** Links are updated periodically.