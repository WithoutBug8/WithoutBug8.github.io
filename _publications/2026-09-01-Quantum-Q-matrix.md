---
title: "Quantum Sparse Autoencoders for Q-Matrix Estimation in Cognitive Diagnosis"
collection: publications
category: preprints
permalink: /publication/2026-09-01-quantum-q-matrix
date: 2026-09-01
venue: "arXiv preprint arXiv:2609.01537"
excerpt: "This work introduces a quantum sparse autoencoder for data-driven Q-matrix estimation and evaluates its accuracy and stability on simulated and real-world assessment datasets."
link: "https://arxiv.org/abs/2609.01537"
paperurl: "https://arxiv.org/pdf/2609.01537"
citation: >-
  Arif Hassan Zidan, Yi Pan, <strong>Bowen Guo</strong>, Xiang Li, Yu Bao,
  Yingfeng Wang, Tianming Liu, and Wei Zhang. (2026). &quot;Quantum Sparse
  Autoencoders for Q-Matrix Estimation in Cognitive Diagnosis.&quot;
  <i>arXiv preprint arXiv:2609.01537</i>.
---

## Abstract

Q-matrices play a central role in cognitive diagnosis within educational data mining (EDM), specifying which latent skills each assessment item requires. Data-driven Q-matrix estimation remains challenging when assessments involve many correlated skills and when real response patterns depart from idealized generative assumptions. We introduce a novel quantum sparse autoencoder (QSAE) for Q-matrix estimation, which, to the best of our knowledge, is the first application of quantum machine learning (QML) to cognitive diagnosis.

Overall, the QSAE embeds each student's binary response vector into a quantum circuit using an encoder, compresses it into a sparse latent representation, and maps that representation to the Q-matrix. We benchmark the QSAE against a classical autoencoder (CAE) across 60 simulated datasets and 9 real-world assessment datasets. The results reveal complementary strengths. Although the CAE partially achieves higher average accuracy under several simulation conditions, the QSAE is substantially more stable across replications, exhibiting lower variance in 49 of the 60 conditions. Moreover, on real assessment data, the QSAE outperforms the CAE on 6 of the 9 datasets.

These findings suggest that the principal advancement of QML in this setting is not universal accuracy improvement, but enhanced robustness and capability to explore latent-structure complexity in real datasets.
