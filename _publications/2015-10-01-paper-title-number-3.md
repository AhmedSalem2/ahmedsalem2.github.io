---
title: "MLCapsule: Guarded Offline Deployment of Machine Learning as a Service"
collection: publications
permalink: ''
excerpt: ''
date: 2019-12-01
venue: 
paperurl: 'https://arxiv.org/pdf/1808.00590.pdf'
citation: 
---
With the widespread use of machine learning (ML) techniques, ML as a service has become increasingly popular. In this setting, an ML model resides on a server and users can query the model with their data via an API. However, if the user's input is sensitive, sending it to the server is not an option. Equally, the service provider does not want to share the model by sending it to the client for protecting its intellectual property and pay-per-query business model. In this paper, we propose MLCapsule, a guarded offline deployment of machine learning as a service. MLCapsule executes the machine learning model locally on the user's client and therefore the data never leaves the client. Meanwhile, MLCapsule offers the service provider the same level of control and security of its model as the commonly used server-side execution. In addition, MLCapsule is applicable to offline applications that require local execution. Beyond protecting against direct model access, we demonstrate that MLCapsule allows for implementing defenses against advanced attacks on machine learning models such as model stealing/reverse engineering and membership inference.
