---
title: "Communication bounds for convolutional neural networks"
collection: publications
permalink: /publication/2022-07-12-Communication-bounds-for-convolutional-neural-networks
excerpt: 'Convolutional neural networks (CNNs) are important in a wide variety of machine learning tasks and applications, so optimizing their performance is essential.'
date: 2022-07-12
venue: 'PASC 22: Proceedings of the Platform for Advanced Scientific Computing Conference'
paperurl: 'https://dl.acm.org/doi/10.1145/3539781.3539784'
citation: 'Anthony Chen, James Demmel, Grace Dinh, Mason Haberle, and Olga Holtz. 2022. Communication bounds for convolutional neural networks. In Proceedings of the Platform for Advanced Scientific Computing Conference (PASC '22). Association for Computing Machinery, New York, NY, USA, Article 1, 1–10. https://doi.org/10.1145/3539781.3539784'
---

Convolutional neural networks (CNNs) are important in a wide variety of machine learning tasks and applications, so optimizing their performance is essential. Moving words of data between levels of a memory hierarchy or between processors on a network is much more expensive than the cost of arithmetic, so minimizing communication is critical to optimizing performance. In this paper, we present new lower bounds on data movement for mixed precision convolutions in both single-processor and parallel distributed memory models, as well as algorithms that outperform current implementations such as Im2Col. We obtain performance figures using GEMMINI, a machine learning accelerator, where our tiling provides improvements between 13% and 150% over a vendor supplied algorithm.

[Download paper here](https://arxiv.org/abs/2204.08279)

Recommended citation: Anthony Chen, James Demmel, Grace Dinh, Mason Haberle, and Olga Holtz. 2022. Communication bounds for convolutional neural networks. In Proceedings of the Platform for Advanced Scientific Computing Conference (PASC '22). Association for Computing Machinery, New York, NY, USA, Article 1, 1–10. https://doi.org/10.1145/3539781.3539784