---
layout: paper-page
title: SCITE
name: SCITE
bibkey: li:2021a
bibfile: models
abstract: >-
    Causality extraction from natural language texts is a challenging open problem in artificial intelligence. Existing methods utilize patterns, constraints, and machine learning techniques to extract causality, heavily depending on domain knowledge and requiring considerable human effort and time for feature engineering. In this paper, we formulate causality extraction as a sequence labeling problem based on a novel causality tagging scheme. On this basis, we propose a neural causality extractor with the BiLSTM-CRF model as the backbone, named SCITE (Self-attentive BiLSTM-CRF wIth Transferred Embeddings), which can directly extract cause and effect without extracting candidate causal pairs and identifying their relations separately. To address the problem of data insufficiency, we transfer contextual string embeddings, also known as Flair embeddings, which are trained on a large corpus in our task. In addition, to improve the performance of causality extraction, we introduce a multihead self-attention mechanism into SCITE to learn the dependencies between causal words. We evaluate our method on a public dataset, and experimental results demonstrate that our method achieves significant and consistent improvement compared to baselines.
---
