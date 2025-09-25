---
title: "Learning to Simulate Natural Language Feedback for Interactive Semantic Parsing"
collection: publications
category: conferences
permalink: /publication/2023-05-14-nl-feedback-parser
excerpt: 'We propose simulating natural language feedback for interactive semantic parsing, enabling scalable training without costly human annotations and improving text-to-SQL error correction.'
date: 2023-05-14
paperurl: 'https://aclanthology.org/2023.acl-long.177.pdf'
citation: 'Hao Yan, Saurabh Srivastava, Yintao Tai, Sida I. Wang, Wen-tau Yih, and Ziyu Yao. 2023. Learning to Simulate Natural Language Feedback for Interactive Semantic Parsing. In Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers), pages 3149–3170, Toronto, Canada. Association for Computational Linguistics.'
bibtexurl: 'https://tyttyttyt.github.io/files/nl_feedback_parser.bib'
venue: 'ACL'

github_repo: "hyan5/Learning_to_Simulate_NL_Feedback"
# huggingface_repo: "april-tools/pixar"
# pypi_package: "HyperArgs"
# conda_package: "conda-forge/awesome-retrieval"
# docker_image: "yourname/awesome-retrieval"
# npm_package: "awesome-retrieval"

tags:
  - NLP
  - semantic-parsing
---

**Authors**: Hao Yan, Saurabh Srivastava, **Yintao Tai**, Sida I. Wang, Wen-tau Yih, Ziyu Yao \
**Project URL**: [https://aclanthology.org/2023.acl-long.177/](https://aclanthology.org/2023.acl-long.177/) \
**Code**: [https://github.com/hyan5/Learning_to_Simulate_NL_Feedback](https://github.com/hyan5/Learning_to_Simulate_NL_Feedback)

![overview](/images/nl_feedback_parser_overview.png)

## Abstract
Interactive semantic parsing based on natural language (NL) feedback, where users provide feedback to correct the parser mistakes, has emerged as a more practical scenario than the traditional one-shot semantic parsing. However, prior work has heavily relied on human-annotated feedback data to train the interactive semantic parser, which is prohibitively expensive and not scalable. In this work, we propose a new task of simulating NL feedback for interactive semantic parsing. We accompany the task with a novel feedback evaluator. The evaluator is specifically designed to assess the quality of the simulated feedback, based on which we decide the best feedback simulator from our proposed variants. On a text-to-SQL dataset, we show that our feedback simulator can generate high-quality NL feedback to boost the error correction ability of a specific parser. In low-data settings, our feedback simulator can help achieve comparable error correction performance as trained using the costly, full set of human annotations.
