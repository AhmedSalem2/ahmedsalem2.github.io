---
title: "Updates-Leak: Data Set Inference and Reconstruction Attacks in Online Learning"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: ''
date: 2019-12-12
year: 2020
venue: 'In Proceedings of the 29th USENIX Security Symposium (USENIX 2020)'
paperurl: 'https://arxiv.org/pdf/1904.01067.pdf'
citation: 
---
Machine learning (ML) has progressed rapidly during the past decade and the major factor that drives such development is the unprecedented large-scale data. As data generation is a continuous process, this leads to ML model owners updating their models frequently with newly-collected data in an online learning scenario. In consequence, if an ML model is queried with the same set of data samples at two different points in time, it will provide different results.
In this paper, we investigate whether the change in the output of a black-box ML model before and after being updated can leak information of the dataset used to perform the update, namely the updating set. This constitutes a new attack surface against black-box ML models and such information leakage may compromise the intellectual property and data privacy of the ML model owner. We propose four attacks following an encoder-decoder formulation, which allows inferring diverse information of the updating set. Our new attacks are facilitated by state-of-the-art deep learning techniques. In particular, we propose a hybrid generative model (CBM-GAN) that is based on generative adversarial networks (GANs) but includes a reconstructive loss that allows reconstructing accurate samples. Our experiments show that the proposed attacks achieve strong performance.
