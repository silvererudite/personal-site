---
layout: page
title: Factual image captioning using VLM and knowledge graphs
description: VLMs struggle to output factually correct image captions, they either generate partial facts or completely hallucinate. Increasing model size further worsens the ability. My experiments suggest that hallucination in VLMs is often linked to poor hierarchical knowledge because spatial understanding is a crucial factor in Visual understanding. I demonstrate how incorporating hierarchical and structured knowledge such as country → city → landmark help make vlm responses for factual image captioning a promising path to explore. I also systematically ablate different kinds of hierarchical knowledge augmentation and compare their results. 
img: assets/img/12.jpg
importance: 1
category: vlm
related_publications: false
github: https://github.com/silvererudite/generative-ai/blob/main/vision_language_models/kg-augmented-vlm-for-factual-image-captioning.ipynb
key_findings:
  - VLMs ability to fact-check benefits more with hierarchical knowledge than simply scaling up models
  - hierarchical knowledge augmentation helps traverse more nuanced reasoning pathways
models: Qwen/Qwen2-VL-2B-Instruct
other: Graphx, python
---

