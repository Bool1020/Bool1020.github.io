---
title: 'Distilling Large Embeddings via Hyperspherical Householder Quantization'
authors:
- me
- Bin Wu
- Yueyang Su
- Tianfu Zhang
- Yiqi Du
- Lei Yu
- Jiafeng Guo
- Xueqi Cheng
date: '2026-04-01'
publishDate: '2026-04-01T08:17:55.997950Z'
publication_types:
- paper-conference
featured: true
publication: '*Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics* (ACL 2026)'
abstract: 'Large embedding models have become the backbone of modern retrieval systems, offering strong semantic representations at the cost of substantial storage and computation. While recent work explores quantizing embeddings into discrete document identifiers for generative retrieval, most existing approaches rely on Euclidean quantization, which is poorly aligned with the angular geometry induced by contrastive embedding training and often requires long identifier sequences to preserve semantic fidelity. In this work, we propose Hyperspherical Householder Quantization (HHQ), a geometry-aware distillation method that compresses large embeddings into short discrete representations via iterative Householder transformations on the unit hypersphere. By explicitly preserving cosine similarity at each step, HHQ distills semantic structure into compact identifiers that remain faithful to the original embedding space. To support reliable generation of these identifiers, we introduce constrained supervised fine-tuning and tree-aware dynamic masking to enforce structural validity during training and inference. Experiments on NQ and MS MARCO show that HHQ achieves competitive or superior retrieval performance using only five tokens per document, substantially reducing decoding cost while retaining strong semantic retrieval accuracy.'
url_pdf: https://aclanthology.org/2026.acl-long.482.pdf
---
