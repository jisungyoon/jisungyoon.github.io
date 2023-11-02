---
title: 'Residual2Vec: Debiasing graph embedding with random graphs'
authors:
- Sadamori Kojaku
- Jisung Yoon
- Isabel Constantino
- Yong-Yeol Ahn
date: '2021-01-01'
publishDate: '2023-11-02T20:37:11.348112Z'
publication_types:
- article-journal
publication: '*Advances in Neural Information Processing Systems*'

url_pdf: https://proceedings.neurips.cc/paper/2021/hash/ca9541826e97c4530b07dda2eba0e013-Abstract.html

abstract: Graph embedding maps a graph into a convenient vector-space representation for graph analysis and machine learning applications. Many graph embedding methods hinge on a sampling of context nodes based on random walks. However, random walks can be a biased sampler due to the structural properties of graphs. Most notably, random walks are biased by the degree of each node, where a node is sampled proportionally to its degree. The implication of such biases has not been clear, particularly in the context of graph representation learning. Here, we investigate the impact of the random walks' bias on graph embedding and propose residual2vec, a general graph embedding method that can debias various structural biases in graphs by using random graphs. We demonstrate that this debiasing not only improves link prediction and clustering performance but also allows us to explicitly model salient structural properties in graph embedding.
---
