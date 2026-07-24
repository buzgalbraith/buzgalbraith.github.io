---
title: "Similarity-Based Load-Balancing for Distributed Genomic Indices"
excerpt: "A Rust load-balancing strategy that uses sketching data structures to efficiently distribute genomic sequences across distributed indices.<br/>"
collection: portfolio
---

**Authors:** Woodward Galbraith, Ilgar Mammadov, Shreyaan Pathak, Benjamin M. Gyori, Prashant Pandey
**Presented at:** VLDB BioDMS 2026 (talk, abstract)

A general-purpose, similarity-aware load-balancing strategy for distributing genomic sequences across distributed indices.

* Implemented in Rust a general-purpose load-balancing strategy that leverages sketching data structures to efficiently distribute genomic sequences over distributed indices.
* Conducted comprehensive system benchmarking against baseline load-balancing methods, varying both file size and worker number.
* Found that the method reduces index color-table size by up to 8% and stored k-mer count by up to 15% over baseline.
