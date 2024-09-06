---
title: "QUITO-X: An Information Bottleneck-based Compression Algorithm with Cross-Attention"
collection: publications
permalink: /publication/2024-8-20-paper-title-number-2
excerpt: 
date: 2024-8-20
venue: 'Arvix'
paperurl: 'https://arxiv.org/pdf/2408.10497.pdf'
citation: '<b>Yihang Wang</b>, Xu Huang, Bowen Tian, Yixing Fan, Jiafeng Guo. (2024). &quot;QUITO-X: An Information Bottleneck-based Compression Algorithm with Cross-Attention.&quot; <i>Arvix</i>'
---

**Abstract**

Generative LLM have achieved significant success in various industrial tasks and can effectively adapt to vertical domains and downstream tasks through ICL. However, with tasks becoming increasingly complex, the context length required by ICL is also getting longer, and two significant issues arise: (i) The excessively long context leads to high costs and inference delays. (ii) A substantial amount of task-irrelevant information introduced by long contexts exacerbates the "lost in the middle" problem.

Recently, compressing prompts by removing tokens according to some metric obtained from some causal language models, such as llama-7b, has emerged as an effective approach to mitigate these issues. However, the metric used by prior method such as self-information or PPL do not fully align with the objective of distinuishing the most important tokens when conditioning on query. In this work, we introduce information bottleneck theory to carefully examine the properties required by the metric. Inspired by this, we use cross-attention in encoder-decoder architecture as a new metric. Our simple method leads to significantly better performance in smaller models with lower latency.

We evaluate our method on four datasets: DROP, CoQA, SQuAD, and Quoref. The experimental results show that, while maintaining the same performance, our compression rate can improve by nearly 25% over previous SOTA. Remarkably, in experiments where 25% of the tokens are removed, our model's EM score for answers sometimes even exceeds that of the control group using uncompressed text as context.
