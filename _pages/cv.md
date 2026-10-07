---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="{{ base_path }}/files/zhihao_lin_cv.pdf" class="btn btn--primary">Download CV (PDF)</a>

Research Experience
======

* **AI Systems Research Assistant**, University of Virginia, Sep 2026 – Present, Remote
  * Profiling vLLM-based agentic workloads to identify concurrency and inference bottlenecks, focusing on KV-cache management and serving efficiency.

* **Independent Researcher, Large Language Models**, Jan 2026 – Sep 2026, Seattle, WA
  * Built a Python LLM pipeline using OpenAI APIs for GPT-4o annotation of 37K+ prompts and GPT-4-turbo evaluation, with confidence-based filtering and validation against human-labeled gold sets.
  * Co-developed Scenario-Actor on Llama-3.1-8B-Instruct; led all experiments in PyTorch, implementing hidden-state extraction, scenario-representation training, and prompt-level temperature selection.
  * Paper: *Read the Room Before Your Model Generates.* Muyao Kong\*, Zhihao Lin\* (\*equal contribution). Accepted to the AACL-IJCNLP 2026 Main Conference.

* **Research Assistant**, Santa Clara University, Jan 2022 – Apr 2022
  * Advisor: Prof. Yi Fang
  * **Sentiment Analysis for Email Interaction**
    * Contributed to an NLP research project on sentiment analysis for email interaction through literature review, research discussions, and experimental model deployment on AWS EC2.
    * Built a Chrome/Gmail sentiment-analysis plugin prototype that integrated NLP inference into email workflows for lightweight sentiment interpretation.
  * **Reporter Image Analysis for Fake-News Research**
    * Developed reusable research software that crawled web images associated with news reporters and combined Amazon Rekognition with DeepFace for face attribute analysis, producing structured reporter data for downstream fake-news detection research; packaged the software for use by a PhD researcher.

Education
======

* **M.S. in Computer Science**, Santa Clara University, Sep 2020 – Dec 2022
  * GPA: 3.77/4.0
* **B.S. in Computer Science**, University at Buffalo, The State University of New York, Aug 2016 – Jun 2020
  * *cum laude*; Dean's List (2019)

Industry Experience
======

* **Software Development Engineer**, Amazon Web Services, Amazon Connect, Feb 2023 – Apr 2026, Seattle, WA
  * Built and operated metrics services powering near-real-time contact-center analytics, handling 280K TPS and supporting metric computation, data storage, validation, and API-based data delivery as daily customer interactions grew from 10M+ to 20M+.
  * Owned and productionized a metrics validation service using AWS Lambda, DynamoDB, OpenSearch, and S3, expanding pre-launch validation coverage to over 90%, reducing customer complaints related to metric definitions by approximately 70%, and cutting investigation time for related support tickets from one day to two hours.
  * Extended the validation service with retrieval-grounded LLM workflows used internally for metric onboarding, validation, and debugging, using schemas, dependencies, and calculation logic from DynamoDB and OpenSearch.
  * Built structured tool interfaces exposing backend services for schema inspection, metric validation, and script execution, with validation guardrails for reliable AI-assisted workflows.
  * Owned the design and delivery of an asynchronous cross-region OpenSearch data-deletion workflow with load-aware throttling, idempotent execution, and verification to meet compliance requirements without impacting availability.
  * Led service expansion into six new AWS regions, coordinating cross-team dependencies and launch readiness; introduced an AI-assisted SOP-to-workflow automation that reduced expansion cycles from two weeks to one.
  * Owned CI/CD, monitoring, and on-call operations for services maintaining 99.95%+ availability, leading incident response and root-cause analysis while partnering across engineering and product teams.

* **Software Development Engineer Intern**, Amazon Web Services, Amazon Connect, Jun 2022 – Sep 2022, Seattle, WA
  * Prototyped the metrics validation service that was later productionized during my full-time role.

Skills
======

* **Programming:** Python, Java, TypeScript, Bash
* **AI / ML:** PyTorch, Hugging Face Transformers, vLLM, Llama, OpenAI API, RAG, LLM inference, tool calling, LLM evaluation, scikit-learn, NumPy, pandas
* **Systems and tools:** Distributed systems, data pipelines, CI/CD, observability, Linux, Git, Docker
* **Cloud:** AWS (EC2, Fargate, Lambda, SageMaker AI, DynamoDB, OpenSearch, S3, SNS/SQS, CloudWatch, CloudFormation)

Research Interests
======

Large Language Models, LLM Inference and Serving, AI Systems, AI Agents, Representation Learning, and Multimodal / Embodied AI.
