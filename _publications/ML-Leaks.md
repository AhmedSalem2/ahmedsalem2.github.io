---
title: "ML-Leaks: Model and Data Independent Membership Inference Attacks and Defenses on Machine Learning Models"
collection: publications
permalink: 
excerpt: ''
date: 2019-01-01
year: 2019
venue: 26th Annual Network and Distributed System Security Symposium (NDSS 2019)
paperurl: 'https://arxiv.org/pdf/1806.01246.pdf'
citation: 
---
Machine learning (ML) has become a core component of many real-world applications and training data is a key factor that drives current progress. This huge success has led Internet companies to deploy machine learning as a service (MLaaS). Recently, the first membership inference attack has shown that extraction of information on the training set is possible in such MLaaS settings, which has severe security and privacy implications. 
<br>
However, the early demonstrations of the feasibility of such attacks have many assumptions on the adversary such as using multiple so-called shadow models, knowledge of the target model structure and having a dataset from the same distribution as the target model's training data. We relax all 3 key assumptions, thereby showing that such attacks are very broadly applicable at low cost and thereby pose a more severe risk than previously thought. We present the most comprehensive study so far on this emerging and developing threat using eight diverse datasets which show the viability of the proposed attacks across domains. 
<br>
In addition, we propose the first effective defense mechanisms against such broader class of membership inference attacks that maintain a high level of utility of the ML model.
