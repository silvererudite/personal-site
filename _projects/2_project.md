---
layout: page
title: Identifying RAG outputs in an LLM-generated response
description: LLMs responses that are augmented using external knowledge are hard to cross-check which parts of the external knowledge are used. I demonstrate a simple technique, a blend of COT and token manipulation. The result is a practical method that lets users highlight the retrieved parts in a generated text in a different color making the responses more interpretable.  
img: assets/img/12.jpg
importance: 1
category: llm
related_publications: false
github: https://github.com/silvererudite/generative-ai/tree/main/interpretable_generative_ai
key_findings:
  - LLMs often know when they lack information, the more compact the model the greater this ability
  - They can tag external information that was not present in their parametric knowledge

models: LLama-3.2-Instruct
other: python
---

