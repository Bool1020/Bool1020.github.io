---
title: 🎉 Two Papers Accepted to ACL 2026 Main Conference!
summary: 'Our two papers, "Detoxification for LLM: From Dataset Itself" and "Distilling Large Embeddings via Hyperspherical Householder Quantization," have been accepted to the ACL 2026 Main Conference! 🎉'
date: 2026-04-07
authors:
  - me
tags:
  - NLP
  - conference
  - paper
image:
  caption: 'Image credit: [**ACL**](https://2026.aclweb.org/)'
---

We are thrilled to share that **two of our papers have been accepted to the ACL 2026 Main Conference**! 🎉🎉

The accepted papers are: **"Detoxification for LLM: From Dataset Itself"** and **"Distilling Large Embeddings via Hyperspherical Householder Quantization"**

In **"Detoxification for LLM: From Dataset Itself,"** we revisit LLM safety from a data-centric perspective. Instead of relying only on post-training alignment or decoding-time control, we propose **HSPD (Hierarchical Semantic-Preserving Detoxification)**, a pipeline that directly rewrites toxic training corpora while preserving their semantic content. Built on **SoCD (Soft Contrastive Decoding)**, our method guides models to localize and revise toxic spans in raw text, producing detoxified corpora that can directly replace the original training data. Experiments show that this approach substantially reduces downstream toxicity while maintaining data utility and model capability. 

In **"Distilling Large Embeddings via Hyperspherical Householder Quantization,"** we propose **HHQ (Hyperspherical Householder Quantization)**, a geometry-aware embedding distillation method for generative retrieval. Unlike conventional Euclidean quantization, HHQ operates directly on the unit hypersphere and preserves cosine-based semantic structure through iterative Householder transformations. To make the resulting compact identifiers more reliable for generation, we further introduce **constrained supervised fine-tuning** and **tree-aware dynamic masking**. Experiments on **NQ** and **MS MARCO** show that HHQ achieves competitive or superior retrieval performance using only **five tokens per document**, substantially reducing decoding cost while retaining strong semantic retrieval accuracy.
We feel incredibly honored to see both works recognized by **ACL 2026**. These two papers reflect our ongoing interest in building language technologies that are not only more effective, but also more efficient and safer. 🙏

Huge thanks to all collaborators, mentors, and supporters who made this possible. We look forward to sharing more details when the conference approaches. Stay tuned! ✨

---
