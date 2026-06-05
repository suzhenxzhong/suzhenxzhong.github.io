---
title: "Developer-LLM Conversations: An Empirical Study of Interactions and Generated Code Quality"
collection: publications
category: preprints
permalink: /publication/2025-developer-llm-conversations
date: 2025-09-12
venue: "arXiv preprint"
paperurl: "https://arxiv.org/abs/2509.10402"
link: "https://arxiv.org/abs/2509.10402"
excerpt: "An empirical study of 82,845 real-world developer–LLM conversations examining how interaction patterns affect generated code quality across 20+ programming languages."
keywords:
  - developer LLM conversations
  - LLM code generation
  - code quality large language models
  - ChatGPT code quality
  - developer AI interaction
  - empirical software engineering
  - CodeChat dataset
  - AI generated code
---

Large Language Models (LLMs) are increasingly used in software development, yet little is known about how developers interact with them in practice and how conversational dynamics influence code quality. We introduce **CodeChat**, a dataset of 82,845 real-world developer–LLM conversations containing 368,506 code snippets across 20+ programming languages, derived from WildChat.

Key findings:
- LLM responses are significantly longer than developer prompts, with a median token-length ratio of **14:1**
- **68% of conversations are multi-turn**, driven by shifting requirements, incomplete prompts, or clarification requests
- Top developer tasks include web design (9.6%) and neural network training (8.7%)
- LLM-generated code frequently contains defects such as undefined variables (83.4% in Python, 75.3% in JavaScript)
- Prompts that explicitly point out mistakes and request fixes are the most effective for resolving errors
- Java documentation quality improved by up to 14.7% over 5 conversation turns

**Authors:** Suzhen Zhong, Ying Zou, Bram Adams  
**arXiv:** [2509.10402](https://arxiv.org/abs/2509.10402)  
**Dataset:** [CodeChat on Hugging Face](https://huggingface.co/datasets/Suzhen/CodeChat)
