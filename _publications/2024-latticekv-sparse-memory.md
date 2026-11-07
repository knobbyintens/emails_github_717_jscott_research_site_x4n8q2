---
title: "LatticeKV: Sparse Memory Compression for Long-Context Reasoning"
venue: "COLM 2024"
date: 2024-07-15
citation: "Scott, J., Alvarez, M., and Bhatt, R. LatticeKV: Sparse Memory Compression for Long-Context Reasoning. In Proceedings of COLM, 2024."
paperurl: "/files/latticekv.pdf"
excerpt: "A sparse memory lattice that compresses key-value caches for long-context language models without retraining."
permalink: /publications/latticekv/
---

Long-context inference is dominated by the memory footprint of the key-value
cache. We introduce LatticeKV, a sparse memory lattice that stores cache
entries in a hierarchical, learnable structure and evicts them with a
reconstruction-aware policy. The method runs on top of existing transformer
implementations and requires no retraining of the base model. On reasoning
benchmarks with contexts up to 128k tokens, LatticeKV reduces cache memory by
3.4x while preserving 99.1% of the full-cache accuracy.
