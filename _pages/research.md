---
permalink: /research/
title: "Research"
author_profile: true
---

**Research interests:** Large Language Models, LLM Inference and Serving, AI Systems, AI Agents, Representation Learning, and Multimodal / Embodied AI.

Current work
------

* **AI Systems Research Assistant, University of Virginia** (Sep 2026 – present).
  * Profiling vLLM-based agentic workloads to identify concurrency and inference bottlenecks, focusing on KV-cache management and serving efficiency.
* **Independent research on large language models** (Jan 2026 – Sep 2026): adaptive LLM generation, representation learning, and inference-time methods.
  * Co-developed **Scenario-Actor**, a scenario-adaptive decoding framework built on Llama-3.1-8B-Instruct that learns scenario representations from hidden states and selects a sampling temperature for each prompt.
  * Led all experiments in PyTorch, implementing hidden-state extraction, scenario-representation training, and prompt-level temperature selection.
  * Built a Python LLM pipeline using OpenAI APIs for GPT-4o annotation of 37K+ prompts and GPT-4-turbo evaluation, with confidence-based filtering and validation against human-labeled gold sets.
  * Paper: *Read the Room Before Your Model Generates.* Muyao Kong\*, Zhihao Lin\* (\*equal contribution). Accepted to the AACL-IJCNLP 2026 Main Conference.

Prior experience
------

* **Research Assistant, Santa Clara University** (Jan 2022 – Apr 2022), advised by Prof. Yi Fang.
  * **Sentiment Analysis for Email Interaction**
    * Contributed to an NLP research project on sentiment analysis for email interaction through literature review, research discussions, and experimental model deployment on AWS EC2.
    * Built a Chrome/Gmail sentiment-analysis plugin prototype that integrated NLP inference into email workflows for lightweight sentiment interpretation.
  * **Reporter Image Analysis for Fake-News Research**
    * Developed reusable research software that crawled web images associated with news reporters and combined Amazon Rekognition with DeepFace for face attribute analysis, producing structured reporter data for downstream fake-news detection research; packaged the software for use by a PhD researcher.
