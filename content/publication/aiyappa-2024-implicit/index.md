---
title: Implicit degree bias in the link prediction task
authors:
- Rachith Aiyappa
- Xin Wang
- Munjung Kim
- Ozgur Can Seckin
- Jisung Yoon
- Yong-Yeol Ahn
- Sadamori Kojaku
date: '2024-06-01'
publishDate: '2024-06-02T08:01:25.786208Z'
publication_types:
- article-journal
publication: '*arXiv preprint arXiv:2405.14985*'
url_pdf: https://arxiv.org/abs/2405.14985
abstract: Link prediction -- a task of distinguishing actual hidden edges from random unconnected node pairs -- is one of the quintessential tasks in graph machine learning. Despite being widely accepted as a universal benchmark and a downstream task for representation learning, the validity of the link prediction benchmark itself has been rarely questioned. Here, we show that the common edge sampling procedure in the link prediction task has an implicit bias toward high-degree nodes and produces a highly skewed evaluation that favors methods overly dependent on node degree, to the extent that a ``null'' link prediction method based solely on node degree can yield nearly optimal performance. We propose a degree-corrected link prediction task that offers a more reasonable assessment that aligns better with the performance in the recommendation task. Finally, we demonstrate that the degree-corrected benchmark can more effectively train graph machine-learning models by reducing overfitting to node degrees and facilitating the learning of relevant structures in graphs.
---
