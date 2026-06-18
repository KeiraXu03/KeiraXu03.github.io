---
title: "Transformer-based Vision–Language Jigsaw Puzzle Assembly"
excerpt: "Vision–language model that reassembles shuffled image patches using text as a global semantic anchor. <b>Accepted to the AAAI-26 Student Abstract Program.</b>"
collection: portfolio
---

**May 2025 – Sept. 2025 · Accepted to the AAAI-26 Student Abstract Program**

A transformer-based framework for reassembling shuffled image fragments that
introduces **textual descriptions as global semantic anchors** to resolve
patch-level ambiguity.

- Extracted visual and text features via **ViT** and **BLIP**, aligning cross-modal
  representations at both patch and image granularities with an **InfoNCE**
  contrastive loss and **Hungarian matching** for optimal permutation assignment.
- Implemented Multi-Head Attention Fusion and permutation assignment in PyTorch.
- Led the full research pipeline — modular data/preprocessing, reproducible training,
  experiment tracking, and ablations over local/global alignment branches.
- The proposed method achieves significant permutation-accuracy gains over
  pure-vision baselines, validating the role of language semantics in
  disambiguating visually similar fragments.
