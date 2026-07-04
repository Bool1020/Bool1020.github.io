---
title: 'Detoxification for LLM: From Dataset Itself'
authors:
- Wei Shao
- me
- Gaoyu Zhu
- Ziqiang Cheng
- Lei Yu
- Jiafeng Guo
- Xueqi Cheng
date: '2026-04-01'
publishDate: '2026-04-01T08:16:55.997950Z'
publication_types:
- paper-conference
featured: true
publication: '*Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics* (ACL 2026)'
abstract: 'Existing detoxification methods for large language models mainly focus on post-training stage or inference time, while few tackle the source of toxicity, namely, the dataset itself. Such training-based or controllable decoding approaches cannot completely suppress the model’s inherent toxicity, whereas detoxifying the pretraining dataset can fundamentally reduce the toxicity that the model learns during training. Hence, we attempt to detoxify directly on raw corpora with SoCD (Soft Contrastive Decoding), which guides an LLM to localize and rewrite toxic spans in raw data while preserving semantics, in our proposed HSPD (Hierarchical Semantic-Preserving Detoxification) pipeline, yielding a detoxified corpus that can drop-in replace the original for fine-tuning or other training. On GPT2-XL, HSPD attains state-of-the-art detoxification, reducing Toxicity Probability (TP) from 0.42 to 0.18 and Expected Maximum Toxicity (EMT) from 0.43 to 0.20. We further validate consistent best-in-class results on LLaMA2-7B, OPT-6.7B, and Falcon-7B. These findings show that semantics-preserving, corpus-level rewriting with HSPD effectively suppresses downstream toxicity while retaining data utility and allowing seamless source-level mitigation, thereby reducing the cost of later model behavior adjustment.'
url_pdf: https://aclanthology.org/2026.acl-long.1079.pdf
---
