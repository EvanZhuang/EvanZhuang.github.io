---
title: "Exploring Software Naturalness through Neural Language Models"
collection: publications
permalink: /publication/2020-08-01-codenatural
excerpt: 'The Software Naturalness hypothesis argues that programming languages can be understood through the same techniques used in natural language processing. We explore this hypothesis through the use of a pre-trained transformer-based language model to perform code analysis tasks.'
date: 2020-08-01
venue: 'arxiv (preprint)'
paperurl: 'https://arxiv.org/abs/2006.12641'

citation: 'Luca Buratti, Saurabh Pujar, Mihaela Bornea, Scott McCarley, Yunhui Zheng, Gaetano Rossiello, Alessandro Morari, Jim Laredo, Veronika Thost,<b>Yufan Zhuang</b>, Giacomo Domeniconi. &quot;Exploring Software Naturalness through Neural Language Models.&quot; <i>arXiv:2006.12641</i>.'
---
The Software Naturalness hypothesis argues that programming languages can be understood through the same techniques used in natural language processing. We explore this hypothesis through the use of a pre-trained transformer-based language model to perform code analysis tasks. Present approaches to code analysis depend heavily on features derived from the Abstract Syntax Tree (AST) while our transformer-based language models work on raw source code. This work is the first to investigate whether such language models can discover AST features automatically. To achieve this, we introduce a sequence labeling task that directly probes the language models understanding of AST. Our results show that transformer based language models achieve high accuracy in the AST tagging task. Furthermore, we evaluate our model on a software vulnerability identification task. Importantly, we show that our approach obtains vulnerability identification results comparable to graph based approaches that rely heavily on compilers for feature extraction.
