---
title: "PolyVoice: Mixture-of-Experts Routing for Multilingual Speech Translation"
venue: "Interspeech 2025"
date: 2025-08-20
citation: "Scott, J., Nakamura, H., and Okafor, D. PolyVoice: Mixture-of-Experts Routing for Multilingual Speech Translation. In Proceedings of Interspeech, 2025."
paperurl: "/files/polyvoice.pdf"
excerpt: "A language-aware routing layer that lets a single speech translation model serve many language pairs efficiently."
permalink: /publications/polyvoice/
---

Multilingual speech translation models are usually trained as one large dense
network, which wastes capacity on language pairs that are easy and starves the
hard ones. PolyVoice adds a light-weight mixture-of-experts routing layer that
selects experts per utterance and per target language. The router is trained
with a load-balancing objective and a latency penalty. Across eight language
pairs, PolyVoice improves BLEU by 2.1 points on average while using 42% less
inference compute than the dense baseline.
