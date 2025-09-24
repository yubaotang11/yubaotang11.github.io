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

<p align="right" style="color: #999999; font-size: 0.9em;">
  Last updated: September 24, 2025
</p>

<span class='anchor' id='about-me'></span>

I am a postdoctoral researcher at University of Amsterdam, working with Prof. dr. [Maarten de Rijke](https://staff.fnwi.uva.nl/m.derijke/). I received my PhD degree from Institute of Computing Technology, Chinese Academy of Sciences, supervised by Prof. dr. [Jiafeng Guo](http://www.bigdatalab.ac.cn/gjf/). My research mainly focuses on Information Retrieval and Natural Language Processing. Currently, I’m working on applying language models on IR problems including generative document retrieval, generative recommendation and retrieval-augmented generation.


# 🔥 Call for PhD Students and Research Engineer in Generative Information Retrieval
The IRLab at the UvA invites applications for three fully-funded PhD positions and one Research Engineer position in the area of generative information retrieval (GenIR), under the supervision of Prof. dr. Maarten de Rijke. IRLab has an extensive publication record (SIGIR, ACL, NeurIPS, etc.) and active industry collaborations applying GenIR in real-world settings. 

You’ll contribute to **key research areas**:
- Accuracy: Understanding generalization and establishing performance guarantees across retrieval tasks.  
- Reliability: Examining how different indexing/generation strategies affect consistency across user groups, query types, and output forms.  
- Resilience: Incorporating mechanisms for adapting to changing corpora and adversarial scenarios without retraining.  
- Probing: Developing techniques to inspect and interpret the internal behavior of GenIR systems.  


**What we’re looking for**
- Background in CS, AI, or related fields  
- Interest in NLP, IR, and generative models (PhD) / experience building IR/NLP systems (Engineer)  
- Strong coding skills in Python and familiarity with PyTorch, HuggingFace, or similar ML frameworks  
- Bonus: prior experience with LLM fine-tuning, retrieval pipelines, or model interpretability  

If you’re interested, please feel free to contact Prof. dr. Maarten de Rijke or me at [m.derijke@uva.nl / y.tang3@uva.nl] for further information or an discussion. It would be better to include your CV when reaching out.
*Note*: The official job postings are still in preparation.


# 🔥 News
- *Jun. 2025*: &nbsp;🎉🎉 I was recognized as an Outstanding Graduate of Beijing, as well as an Outstanding Graduate of the University of Chinese Academy of Sciences.
- *Apr. 2025*: &nbsp;🎉🎉 Two research papers are accepted at the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2025).
- *Nov. 2024*: &nbsp;🎉🎉 A research paper is accepted at the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2025).
- *Nov. 2024*: &nbsp;🎉🎉 I received the "National Scholarship"(国家奖学金).
- *Sep. 2024*: &nbsp;🎉🎉 A research paper is accepted at the 38th Annual Conference on Neural Information Processing Systems (NeurIPS 2024) as Spotlight.
- *May. 2024*: &nbsp;🎉🎉 A research paper is accepted at the 62nd Annual Meeting of the Association for Computational Linguistics (ACL 2024).

# 📝 Publications 
[SIGIR 2025] **Boosting Retrieval-Augmented Generation with Generation-Augmented Retrieval: A Co-Training Approach** [[PDF](resources/MINT_SIGIR2025.pdf)]      
   The 48th International ACM SIGIR Conference on Research and Development in Information Retrieval (CCF-A)  
   **_Yubao Tang_**, Ruqing Zhang, Jiafeng Guo, Maarten de Rijke, Yixing Fan and Xueqi Cheng  

[SIGIR 2025] **Lightweight and Direct Document Relevance Optimization for Generative Information Retrieval** [[PDF](resources/DDRO-SIGIR2025.pdf)]   
   The 48th International ACM SIGIR Conference on Research and Development in Information Retrieval (CCF-A)  
   Kidist Amde Mekonnen, **_Yubao Tang_** and Maarten de Rijke  

[KDD 2025] **Generative Retrieval for Book Search** [[PDF](resources/Generative_Retrieval_for_Book_Search.pdf)] [[Video](https://www.youtube.com/watch?v=l4D__UBTAV4)]    
   The 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining  (CCF-A)  
   **_Yubao Tang_**, Ruqing Zhang, Jiafeng Guo, Maarten de Rijke, Shihao Liu, Shuaiqiang Wang, Dawei Yin, Xueqi Cheng  
   
[NeurIPS 2024, Spotlight] **Generative Retrieval Meets Multi-Graded Relevance** [[PDF](resources/Generative_Retrieval_Meets_Multi-Graded_Relevance.pdf)]    
   The 38th Annual Conference on Neural Information Processing Systems (CCF-A)  
   **_Yubao Tang_**, Ruqing Zhang, Jiafeng Guo, Maarten de Rijke, Wei Chen, Xueqi Cheng  
   
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
[SIGIR 2024] **Recent Advances in Generative Information Retrieval** [[Website](https://generative-ir.github.io)]   
**_Yubao Tang_**, Ruqing Zhang, Zhaochun Ren, Jiafeng Guo, Maarten de Rijke  

[TheWebConf 2024] **Recent Advances in Generative Information Retrieval** [[Website](https://thewebconf2024-generative-ir.github.io/)]   
**_Yubao Tang_**, Ruqing Zhang, Weiwei Sun, Zhaochun Ren, Jiafeng Guo, Maarten de Rijke  

[ECIR 2024] **Recent Advances in Generative Information Retrieval** [[Website](https://ecir2024-generativeir.github.io)]   
**_Yubao Tang_**, Ruqing Zhang, Zhaochun Ren, Jiafeng Guo, Maarten de Rijke  

[SIGIR-AP 2023] **Recent Advances in Generative Information Retrieval** [[Website](https://sigir-ap2023-generative-ir.github.io)]   
**_Yubao Tang_**, Ruqing Zhang, Jiafeng Guo, Maarten de Rijke  


# 📝 Industry applications
[2024] **Book search**  
Books contain complex, multi-faceted information. To address the unique challenges in book search, we designed an effective GR framework for book search, including data augmentation and outline-oriented book encoding, which outperforms the state-of-the-art GR baseline by 9.8% in terms of MRR@20 on the Baidu dataset.

[2023] **Official site retrieval at Baidu search**  
Official site retrieval task aims to understand query intents on official sites operated by administrative units, and further guide the search engine to recall relevant official sites. We designed a generative retrieval method, called Semantic-enhanced DSI (Semantic-Enhanced Differentiable Search Index Inspired by Learning Strategies), and applied it into this task, which significantly outperformed the existing baseline of Baidu search engine by 8.83% in terms of Recall@20 on the online dataset.


# 📝 Projects
[2024] **Co-training framework for Retrieval-augmented Generation and Generation-augmented Retrieval**  
We design the framework as a cooperative two-player game, leveraging the complementarity between retrieval-augmented generation (RAG) and generation-augmented retrieval (GAR) to progressively improve RAG performance. Additionally, we address privacy concerns, particularly the leakage of Personally Identifiable Information (PII), by identifying and neutralizing the neurons in the generator responsible for PII while preserving model performance.

[2023] **GoMate: RAG Framework within Reliable input,Trusted output**  [[Link](https://github.com/gomate-community/GoMate)]  
GoMate is a comprehensive knowledge-based QA application based on large LLMs. It primarily includes a query understanding module, a retrieval module, an LLM module for retrieval enhancement, a reference tracing module, an answer generation module, and an user privacy protection module. Users might inadvertently disclose private information while interacting with GoMate. To address this problem, our approach is to identify and mitigate user-side privacy leaks and to abstract user input into semantically similar but less specific and safer text.


# 🎖 Honors and Awards
- *2025*: 🎖 Outstanding Graduate of Beijing
- *2024*: 🎖 National Scholarship (国家奖学金)  
- *2023*: 🎖 President of Institute of Computing Technology's Prize Scholarship (中国科学院计算所所长优秀奖)  
- *2021, 2022, and 2023*: 🎖 Merit Student, University of Chinese Academy of Sciences (中国科学院大学三好学生)  


# 📖 Educations
- *Sep. 2021 - Jan. 2025*, Ph.D., University of Chinese Academy of Sciences  
- *Sep. 2018 - Jun. 2021*, Master, University of Chinese Academy of Sciences  
- *Sep. 2014 - Jun. 2018*, Undergraduate, Sichuan University  

# 🎙️ Talks
- *Jun. 2025*, "Recent Advances in Generative Information Retrieval" for University of Glasgow. (online) [[Slides](resources/Talk_GenIR_20250609.pdf)] 
- *Sep. 2024*, "Generative Information Retrieval: Learning and Application Research" at Baidu Inc. 
- *Jan. 2024*, "Recent Advances in Generative Information Retrieval" at Baidu Inc. [[Slides](resources/GR_Tutorial_Slides_for_baidu.pdf)] 
- *Nov. 2023*, "Semantic-Enhanced Differentiable Search Index" at Kuaishou Inc. [[Slides](resources/Introduction_to_GR.pdf)] 

# 📝 Intership 
- *May. 2023-Dec. 2024*, Baidu search

# 📝 Teaching 
- Recommender Systems (June 2025) – MSc Artificial Intelligence
  - University of Amsterdam, Amsterdam, The Netherlands
  - Developed and delivered lectures on generative recommendation [[Slides](resources/Recsys_2025_Lecture_4_Generative_approaches_to_recommender_systems.pdf)], guided students in reproducing recommendation methods, and conducted assessments.

- Information Retrieval (Sep–Oct 2025) – BSc AI
  - University of Amsterdam, Amsterdam, The Netherlands
  - Lecturer for Learning to Rank and Semantic Matching [[Slides](resources/Recsys_2025_Lecture_4_Generative_approaches_to_recommender_systems.pdf)], conducting assessments, supporting students, and maintaining course materials.


# 📝 Supervision 
- Steven Dong (BSc., March 2025 – June 2025), University of Amsterdam
  - Thesis: The integration of Chain of Thought in Generative Information Retrieval

# 💗 Academic Service
- *Program Committee / Conference Reviewer*: WSDM 2025, EMNLP ARR 2025, NeurIPS 2025, SIGIR 2025, ACL ARR 2025, KDD 2025, Gen-IR@SIGIR24, Gen-IR@SIGIR23, WI-IAT 2023
- *Journal reviewer*: Transactions on Information Systems, Information Processing and Management
- *Volunteer*: SIGIR-AP 2023

# 🗺 Visitors
<p align="left"><script type='text/javascript' id='clustrmaps' src="//clustrmaps.com/map_v2.js?d=x8LNUtBmFleCVRz5MLrkTsnhzd_J_MZUJx-P28qFPmI&cl=ffffff&w=a"></script></p>

