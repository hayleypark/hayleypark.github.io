---
title: About
layout: page
---
![Profile Image]({{ site.url }}/{{ site.picture }})

I'm an Applied Scientist at the [Generative AI Innovation Center](https://aws.amazon.com/ai/generative-ai/innovation-center/) at Amazon Web Services. My work sits at the intersection of AI research and real-world deployment: I develop evaluation methodologies and multi-agent architectures that enable enterprises across critical industries to reliably deploy large language models for mission-critical processes.

### Research Interests

- **AI Evaluation**: Designing rigorous methods for assessing generative AI systems, from structured output evaluation for information extraction to confidence calibration in agentic environments
- **Multi-Agent Systems**: Designing and deploying systems that coordinate multiple specialized AI agents to solve complex enterprise problems across industries
- **Synthetic Data for Evaluation**: Establishing validity frameworks for synthetic evaluation data, addressing the fundamental bottleneck of data access in regulated industries
- **LLM Reliability & Calibration**: Two active research threads: (1) quantifying structural uncertainty in LLM reasoning ([EMNLP 2026](https://aclanthology.org/2026.emnlp-main.699/); [ICLR 2026 workshop Best Paper](https://arxiv.org/abs/2606.17312)), and (2) pass@k calibration, studying whether LLMs can predict their own marginal gains from additional sampling to enable efficient inference-time compute allocation

### Recent Highlights

- **[EMNLP 2026](https://aclanthology.org/2026.emnlp-main.699/)** paper on structural uncertainty from self-preference in black-box language models
- **Best Paper Award** at the [ICLR 2026 Workshop on Logical Reasoning of Large Language Models](https://arxiv.org/abs/2606.17312) for work on quantifying consistency in LLM logical reasoning
- Founder and maintainer of [SEED (Synthetically Engineered Evaluation Data)](https://github.com/awslabs/synthetically_engineered_evaluation_data), an open-source platform for generating high-quality synthetic evaluation data. I built the tabular data generation component and manage releases. SEED enables teams to begin AI development without waiting for real customer data, addressing the fundamental data access bottleneck in regulated industries (healthcare, finance, legal).
- Contributor to [stickler](https://github.com/awslabs/stickler), an open-source evaluation library for structured LLM outputs (14,000+ monthly PyPI downloads). I built the hierarchical aggregate metrics system for evaluating nested structures at arbitrary depth. stickler now powers the structured-output evaluator in Strands Evals; see our [Strands Agents blog post](https://strandsagents.com/blog/structured-output-similarity-strands-evals/).
- Main author of [Evaluating Intelligent Document Processing Solutions](https://awslabs.github.io/generative-ai-atlas/topics/2_0_technical_foundations_and_patterns/2_6_model_evaluation_and_selection_criteria/2_6_4_domain_specific_evaluations/2_6_4_2_evaluating_intelligent_document_processing/2_6_4_2_evaluating_intelligent_document_processing.html) in the [GenAI Atlas](https://awslabs.github.io/generative-ai-atlas/)
- Organized the AMLC 2025 Workshop on *Evaluation Paradigms for GenAI* and organizing the AMLC 2026 Workshop on *Test-Time Scaling: Algorithms, Systems, and Evaluation for Inference-Time Compute in the Era of Reasoning Models*
- Building agentic systems for enterprise customers, including leading the communications agent layer of a large-scale member-orchestration platform in healthcare, and leading the implementation of an agentic system that automates 5G network capacity-planning validation for a major telecommunications carrier
- AI solutions deployed across 9 industry sectors: energy, healthcare, telecommunications, pharmaceutical manufacturing, financial services, legal, media, HR, and consumer retail

### Background

I completed my PhD in Computational Linguistics at the University of Illinois at Urbana-Champaign (alongside an MS in Statistics), where I worked with [Prof. Lane Schwartz](http://dowobeha.github.io/) on computational methods for low-resource languages. My research spanned [multilingual language modeling (TACL 2021)](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00365/98237/Morphology-Matters-A-Multilingual-Language), neural approaches to polysynthetic language modeling at [JSALT 2019](https://arxiv.org/abs/2005.05477), and NLP tools for an endangered language, supported by [NSF Award #1761680](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1761680). My [dissertation](https://www.ideals.illinois.edu/items/125303) brought much of this work together.

I've been at Amazon since 2022, previously working on LLM-based content generation for Alexa Kids and NLU for Fire TV before joining the GenAI Innovation Center.

Feel free to reach out at [hayley.uiuc@gmail.com](mailto:hayley.uiuc@gmail.com) 

---

### Selected Publications

* **[Structural Uncertainty from Self-Preference in Black-Box Language Models](https://aclanthology.org/2026.emnlp-main.699/)** \
  Baishali Chaudhury, Mengdie Flora Wang, **Hyunji Hayley Park**, Rahul Ghosh, Sungmin Hong, Jae Oh Woo \
  <em>Conference on Empirical Methods in Natural Language Processing (EMNLP)</em>, 2026

* **[Best Paper Award] [Quantifying Consistency in LLM Logical Reasoning via Structural Uncertainty](https://arxiv.org/abs/2606.17312)** \
  Baishali Chaudhury, Mengdie Flora Wang, **Hyunji Hayley Park**, Rahul Ghosh, Sungmin Hong, Jae Oh Woo \
  <em>ICLR 2026 Workshop on Logical Reasoning of Large Language Models</em>, 2026

* **[Evaluating Structured Agent Output, Field by Field, with Strands Evals](https://strandsagents.com/blog/structured-output-similarity-strands-evals/)** \
  Spencer Romo, Vincil Bishop, Diego Galavíz, Harry Cavanagh, **Hayley Park** \
  <em>Strands Agents Blog</em>, 2026

* **[Halliburton Enhances Seismic Workflow Creation with Amazon Bedrock and Generative AI](https://aws.amazon.com/blogs/machine-learning/halliburton-enhances-seismic-workflow-creation-with-amazon-bedrock-and-generative-ai/)** \
  Yuan Tian, Arun Ramanathan, Baishali Chaudhury, Gan Luan, Haochen Xie, Jared Kramer, **Hayley Park**, Di Wu \
  <em>AWS Machine Learning Blog</em>, 2026. A version of this work was also [co-published with Halliburton](https://www.earthdoc.org/content/papers/10.3997/2214-4609.202639083) in the EAGE 2026 Proceedings.

* **Beyond Binary Metrics: A Structured Evaluation Framework for Information Extraction** \
  Spencer Romo, Ayushi Haria, **Hyunji Hayley Park**, Sujitha Martin, Piyush Vyas, Jared Kramer \
  <em>AMLC 2025 Workshop on Evaluation Paradigms for GenAI</em>, 2025

* **[Efficient Classification of Long Documents Using Transformers](https://aclanthology.org/2022.acl-short.79/)** \
  **Hyunji Hayley Park**, Yogarshi Vyas, Kashif Shah \
  <em>Association for Computational Linguistics (ACL)</em>, 2022

* **[Expanding Universal Dependencies for Polysynthetic Languages: A Case of St. Lawrence Island Yupik](https://www.aclweb.org/anthology/2021.americasnlp-1.14/)** \
  **Hyunji Hayley Park**, Lane Schwartz, Francis M. Tyers \
  <em>Workshop on NLP for Indigenous Languages of the Americas (AmericasNLP), NAACL</em>, 2021

* **[Morphology Matters: A Multilingual Language Modeling Analysis](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00365/98237/Morphology-Matters-A-Multilingual-Language)** \
  **Hyunji Hayley Park**, Katherine J. Zhang, Coleman Haley, Kenneth Steimel, Han Liu, Lane Schwartz \
  <em>Transactions of the Association for Computational Linguistics (TACL)</em>, 2021 

* **[Neural Polysynthetic Language Modelling](https://arxiv.org/abs/2005.05477)** \
  Lane Schwartz, Francis Tyers, ..., **Hyunji Hayley Park**, et al. \
  <em>Final Report of the Neural Polysynthetic Language Modelling Team at the 2019 Frederick Jelinek Memorial Summer Workshop</em>, 2020

For a full list, see my [Google Scholar](https://scholar.google.com/citations?user=61SbSqQAAAAJ&hl=en).
