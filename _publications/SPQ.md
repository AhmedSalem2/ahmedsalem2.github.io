---
title: "Privacy-preserving Similar Patient Queries for Combined Biomedical Data"
collection: publications
permalink: 
excerpt: ''
date: 2019-10-01
year: 2019
venue: 'PoPETs (to appear)'
paperurl: https://petsymposium.org/2019/files/papers/issue1/popets-2019-0004.pdf
citation: 
---


The decreasing costs of molecular profiling have fueled the biomedical research community with a plethora of new types of biomedical data, enabling a breakthrough towards more precise and personalized medicine. Naturally, the increasing availability of data also enables physicians to compare patients’ data and treatments easily and to find similar patients in order to propose the optimal therapy. Such similar patient queries (SPQs) are of utmost importance to medical practice and will be relied upon in future health infor- mation exchange systems. While privacy-preserving so- lutions have been previously studied, those are limited to genomic data, ignoring the different newly available types of biomedical data.
<br>
In this paper, we propose new cryptographic techniques for finding similar patients in a privacy-preserving man- ner with various types of biomedical data, including genomic, epigenomic and transcriptomic data as well as their combination. We design protocols for two of the most common similarity metrics in biomedicine: the Euclidean distance and Pearson correlation coefficient. Moreover, unlike previous approaches, we account for the fact that certain locations contribute differently to a given disease or phenotype by allowing to limit the query to the relevant locations and to assign them dif- ferent weights. Our protocols are specifically designed to be highly efficient in terms of communication and bandwidth, requiring only one or two rounds of com- munication and thus enabling scalable parallel queries. We rigorously prove our protocols to be secure based on cryptographic games and instantiate our technique with three of the most important types of biomedical data – namely DNA, microRNA expression, and DNA methy- lation. Our experimental results show that our protocols can compute a similarity query over a typical number of positions against a database of 1,000 patients in a few seconds. Finally, we propose and formalize strategies to mitigate the threat of malicious users or hospitals.
