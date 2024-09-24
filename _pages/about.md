---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am now a forth year Ph.D. student supervised by Prof.[Jiafeng Guo](http://www.bigdatalab.ac.cn/gjf/), in Computer Science at Institute of Computing Technology, Chinese Academy of Sciences. My research is focused on information retrieval, and in particular on the recently emerging paradigm of generative retrieval. In generative retrieval, all information about the corpus is encoded within a consolidated model as its parameters. The model autoregressively generate relevant document identifiers for queries, while dense retrieval methods match pre-indexed documents with queries. Generative retrieval enables end-to-end optimization, faster inference, and reduced storage costs. My specific research explores generative retrieval modeling theory, relevance learning mechanisms for complex search scenarios, and practical applications.

# 🔥 News
- *May. 2024*: &nbsp;🎉🎉 A research paper is accepted at The 62nd Annual Meeting of the Association for Computational Linguistics (ACL 2024).
- *Apr. 2024*: &nbsp;🎉🎉 A research paper is accepted at Transactions on Information Systems (TOIS).
- *Dec. 2023*: &nbsp;🎉🎉 I received the "President of Institute of Computing Technology's Prize Scholarship"(中国科学院计算所所长优秀奖).
- *Aug. 2023*: &nbsp;🎉🎉 A research paper "Semantic-Enhanced Differentiable Search Index Inspired by Learning Strategies" is applied to the official site retrieval scenario at Baidu search.

# 📝 Publications 
[ACL 2024] **Bootstrapped Pre-training with Dynamic Identifier Prediction for Generative Retrieval**  [[PDF](resources/ACL24-Bootstrapped_Pre-training_with_Dynamic_Identifier_Prediction_for_Generative_Retrieval.pdf)] [[Poster](resources/poster-BootRet-ACL_Findings_1874.pdf)] [[Slides](resources/slides-BootRet-ACL_Findings_1874.pptx)]

   The 62nd Annual Meeting of the Association for Computational Linguistics (CCF-A)  
   **_Yubao Tang_**, Ruqing Zhang, Jiafeng Guo, Maarten de Rijke, Yixing Fan, Xueqi Cheng  


[TOIS] **Listwise Generative Retrieval Models via a Sequential Learning Process** [[PDF](resources/TOIS-Listwise_Generative_Retrieval_Models_via_a_Sequential_Learning_Process.pdf)]

   Transactions on Information Systems (CCF-A)  
   **_Yubao Tang_**, Ruqing Zhang, Jiafeng Guo, Maarten de Rijke, Wei Chen, Xueqi Cheng  

[KDD 2023] **Semantic-Enhanced Differentiable Search Index Inspired by Learning Strategies** [[PDF](resources/KDD23-Semantic-Enhanced_Differentiable_Search_Index_Inspired_by_Learning_Strategies.pdf)] [[Slides](resources/SE-DSI.pptx)]

   Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (CCF-A)  
   **_Yubao Tang_**, Ruqing Zhang, Jiafeng Guo, Jiangui Chen, Zuowei Zhu, Shuaiqiang Wang, Dawei Yin, Xueqi Cheng

[CCL 2024] **生成式信息检索前沿进展与挑战**  
   Proceedings of the 22nd Chinese National Conference on Computational Linguistics  
   Yixing Fan, **_Yubao Tang_**, Jiangui Chen, Ruqing Zhang, Jiafeng Guo

# 🎙️ Tutorials
[SIGIR-AP 2023, ECIR 2024, TheWebConf 2024, SIGIR 2024] **Recent Advances in Generative Information Retrieval** [[Website](https://thewebconf2024-generative-ir.github.io/)]   
**_Yubao Tang_**, Ruqing Zhang, Jiafeng Guo, Maarten de Rijke  
Zhaochun Ren is invited as a special speaker at ECIR 2024, TheWebConf 2024, SIGIR 2024  
Weiwei Sun is invited as a special speaker at TheWebConf 2024


# 📝 Industry applications
[2024-Present] **Book search**  
Books contain complex, multi-faceted information. To address the unique challenges in book search, we designed an effective GR framework for book search, including data augmentation and outline-oriented book encoding, which outperforms the state-of-the-art GR baseline by 9.8% in terms of MRR@20 on the Baidu dataset.

[2023] **Official site retrieval at Baidu search**  
Official site retrieval task aims to understand query intents on official sites operated by administrative units, and further guide the search engine to recall relevant official sites. We designed a generative retrieval method, called Semantic-enhanced DSI (Semantic-Enhanced Differentiable Search Index Inspired by Learning Strategies), and applied it into this task, which significantly outperformed the existing baseline of Baidu search engine by 8.83% in terms of Recall@20 on the online dataset.


# 📝 Projects
[2024] **Co-training framework for Retrieval-augmented Generation and Generation-augmented Retrieval**  
We design the framework as a cooperative two-player game, leveraging the complementarity between retrieval-augmented generation (RAG) and generation-augmented retrieval (GAR) to progressively improve RAG performance. Additionally, we address privacy concerns, particularly the leakage of Personally Identifiable Information (PII), by identifying and neutralizing the neurons in the generator responsible for PII while preserving model performance.

[2023] **GoMate: RAG Framework within Reliable input,Trusted output**  [[Link](https://github.com/gomate-community/GoMate)]  
GoMate is a comprehensive knowledge-based QA application based on large LLMs. It primarily includes a query understanding module, a retrieval module, an LLM module for retrieval enhancement, a reference tracing module, an answer generation module, and an user privacy protection module. Users might inadvertently disclose private information while interacting with GoMate. To address this problem, our approach is to identify and mitigate user-side privacy leaks and to abstract user input into semantically similar but less specific and safer text.


[2023] **Virtual Screening**  
Given a protein pocket as the query, it aims to retrieve from a large-scale molecule library the relevant molecules. We develope a GR framework to generate relevant molecule identifiers for a given protein pocket.


# 🎖 Honors and Awards
*2023*: 🎖 President of Institute of Computing Technology's Prize Scholarship (中国科学院计算所所长优秀奖)  
*2021, 2022, and 2023*: 🎖 Merit Student, University of Chinese Academy of Sciences (中国科学院大学三好学生)


# 📖 Educations
- *Sep. 2021 - Present*, Ph.D. Candidate, University of Chinese Academy of Sciences  
- *Sep. 2018 - Jun. 2021*, Master, University of Chinese Academy of Sciences  
- *Sep. 2014 - Jun. 2018*, Undergraduate, Sichuan University  

# 🎙️ Talks
- *Sep. 2024*, "Generative Information Retrieval: Learning and Application Research" at Baidu Inc. 
- *Jan. 2024*, "Recent Advances in Generative Information Retrieval" at Baidu Inc. [[Slides](resources/GR_Tutorial_Slides_for_baidu.pdf)] 
- *Nov. 2023*, "Semantic-Enhanced Differentiable Search Index" at Kuaishou Inc. [[Slides](resources/Introduction_to_GR.pdf)] 

# 📝 Intership 
- *May. 2023-Present*, Baidu search

# 💗 Academic Service
- *Reviewer*: Transactions on Information Systems, Gen-IR@SIGIR24, Gen-IR@SIGIR23, WI-IAT 2023
- *Program Committee*: Gen-IR@SIGIR24, Gen-IR@SIGIR23
- *Volunteer*: SIGIR-AP 2023

