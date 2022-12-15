---
title: "Get a Model! Model Hijacking Attack Against Machine Learning Models"
collection: publications
permalink: 
excerpt: ''
date: 2022-01-01
year: 2022
venue: 29th Annual Network and Distributed System Security Symposium (NDSS 2022)
paperurl: 'https://arxiv.org/abs/2111.04394'
citation: 
---
Machine learning (ML) has established itself as a cornerstone for various critical applications ranging from autonomous driving to authentication systems. However, with this increasing adoption rate of machine learning models, multiple attacks have emerged. One class of such attacks is training time attack, whereby an adversary executes their attack before or during the machine learning model training. In this work, we propose a new training time attack against computer vision based machine learning models, namely model hijacking attack. The adversary aims to hijack a target model to execute a different task than its original one without the model owner noticing. Model hijacking can cause accountability and security risks since a hijacked model owner can be framed for having their model offering illegal or unethical services. Model hijacking attacks are launched in the same way as existing data poisoning attacks. However, one requirement of the model hijacking attack is to be stealthy, i.e., the data samples used to hijack the target model should look similar to the model's original training dataset. To this end, we propose two different model hijacking attacks, namely Chameleon and Adverse Chameleon, based on a novel encoder-decoder style ML model, namely the Camouflager. Our evaluation shows that both of our model hijacking attacks achieve a high attack success rate, with a negligible drop in model utility.
