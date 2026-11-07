---
title: "Diffusion Priors for Controllable Image Editing"
venue: "CVPR 2024"
date: 2024-06-18
citation: "Scott, J., Rossi, L., and Tanaka, K. Diffusion Priors for Controllable Image Editing. In Proceedings of CVPR, 2024."
paperurl: "/files/diffpriors.pdf"
excerpt: "Reusing the internal priors of a pretrained diffusion model for precise, localized image edits."
permalink: /publications/diffpriors/
---

Text-guided image editors often trade edit fidelity for preservation of
unrelated content. We show that the intermediate attention maps of a
pretrained diffusion model already encode strong spatial priors. DiffPriors
extracts these priors and constrains the denoising trajectory with a
region-aware guidance term. The resulting editor supports localized object
replacement and attribute changes while leaving the rest of the scene
unchanged.
