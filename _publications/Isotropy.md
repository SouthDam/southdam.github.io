---
title: "On Isotropy Calibration of Transformer Models"
collection: publications
permalink: /publication/Isotropy
date: 2022-05-26
venue: 'Proceedings of the Third Workshop on Insights from Negative Results in NLP'
citation: 'Yue Ding, Karolis Martinkus, Damian Pascual, Simon Clematide, and Roger Wattenhofer. 2022. On Isotropy Calibration of Transformer Models. In Proceedings of the Third Workshop on Insights from Negative Results in NLP, pages 1–9, Dublin, Ireland. Association for Computational Linguistics.'

---

## Abstract

Different studies of the embedding space of transformer models suggest that the distribution of contextual representations is highly anisotropic - the embeddings are distributed in a narrow cone. Meanwhile, static word representations (e.g., Word2Vec or GloVe) have been shown to benefit from isotropic spaces. Therefore, previous work has developed methods to calibrate the embedding space of transformers in order to ensure isotropy. However, a recent study (Cai et al. 2021) shows that the embedding space of transformers is locally isotropic, which suggests that these models are already capable of exploiting the expressive capacity of their embedding space. In this work, we conduct an empirical evaluation of state-of-the-art methods for isotropy calibration on transformers and find that they do not provide consistent improvements across models and tasks. These results support the thesis that, given the local isotropy, transformers do not benefit from additional isotropy calibration.
