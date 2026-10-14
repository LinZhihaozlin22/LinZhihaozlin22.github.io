---
title: "Read the Room Before Your Model Generates"
collection: publications
category: conferences
permalink: /publications/2026-10-13-read-the-room
excerpt: 'Muyao Kong\*, Zhihao Lin\* (\*equal contribution). Introduces **Scenario-Actor**, which learns scenario embeddings from Transformer hidden states and uses them to choose a sampling temperature for each prompt.'
date: 2026-10-13
venue: 'AACL-IJCNLP 2026 (Main Conference)'
link: 'https://arxiv.org/abs/2610.18820'
paperurl: 'https://arxiv.org/pdf/2610.18820'
citation: 'Muyao Kong*, Zhihao Lin*. (2026). &quot;Read the Room Before Your Model Generates.&quot; <i>AACL-IJCNLP 2026 (Main Conference)</i>. arXiv:2610.18820.'
---

**Authors:** Muyao Kong\*, Zhihao Lin\* (\*equal contribution)

**arXiv:** [2610.18820](https://arxiv.org/abs/2610.18820)

Most LLM deployments pick a sampling temperature with a fixed global setting or token-level calibration, neither of which reflects the communicative situation a prompt sets up. We propose **Scenario-Actor**, a scenario-adaptive decoding framework that extracts scenario-relevant structure from Transformer hidden states, learns a scenario embedding, and selects the sampling temperature for each prompt from that embedding.

On Llama-3.1-8B-Instruct, Scenario-Actor achieves strong goal completion in interactive social scenarios, improves open-ended instruction following, and stays competitive on multi-turn conversation against several decoding baselines.
