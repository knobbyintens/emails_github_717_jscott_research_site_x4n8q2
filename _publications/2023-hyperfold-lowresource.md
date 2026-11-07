---
title: "HyperFold: Hyperbolic Alignment for Low-Resource Translation"
venue: "ACL 2023"
date: 2023-05-10
citation: "Scott, J., and Moreau, C. HyperFold: Hyperbolic Alignment for Low-Resource Translation. In Proceedings of ACL, 2023."
paperurl: "/files/hyperfold.pdf"
excerpt: "Aligning source and target sentence representations in hyperbolic space improves low-resource translation."
permalink: /publications/hyperfold/
---

Low-resource translation suffers when source and target embeddings are
aligned in flat Euclidean space, because hierarchical lexical relationships
are distorted. HyperFold embeds both sides of a parallel corpus in a product of
hyperbolic spaces and learns a folded alignment that preserves parent-child
relations in the lexicon. On four low-resource pairs, HyperFold improves
chrF++ by 1.8 points over a strong Transformer baseline with the same data
budget.
