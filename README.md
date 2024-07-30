# Awesome Compound AI Paper List ⭐️
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)

Developers are increasingly creating Compound AI systems that combine multiple model calls and external components to tackle complex AI tasks. These systems often outperform single models through effective component combination and orchestration with better cost-efficiency and/or reduced latency. This repository collects and categorizes papers on Compound AI, including LLM routing, cascading, ensembling, speculative decoding methods, and LLM programming frameworks.

If you find this repository useful, please consider giving it a star. If there are any relevant papers that should be included, you're welcome to create a pull request or open an issue!

## Related Resources
- [The Shift from Models to Compound AI Systems](https://bair.berkeley.edu/blog/2024/02/18/compound-ai-systems/)
- [Compound AI Systems Workshop](https://sites.google.com/view/compound-ai-systems-workshop/)


## Routing
- Large Language Model Routing with Benchmark Datasets (arXiv, 2023) [[PDF]](https://arxiv.org/pdf/2309.15789) 
  - Tal Shnitzer, Anthony Ou, Mírian Silva, Kate Soule, Yuekai Sun, Justin Solomon, Neil Thompson, Mikhail Yurochkin
- Tryage: Real-time, intelligent Routing of User Prompts to Large Language Models (arXiv, 2023) [[PDF]](https://arxiv.org/pdf/2308.11601)
  - Surya Narayanan Hari, Matt Thomson
- Harnessing the Power of Multiple Minds: Lessons Learned from LLM Routing (Workshop on Insights from Negative Results in NLP, 2024) [[PDF]](https://aclanthology.org/2024.insights-1.15.pdf)
  - Kv Aditya Srivatsa, Kaushal Maurya, Ekaterina Kochmar
- ROUTERBENCH: A Benchmark for Multi-LLM Routing System (arXiv, 2024) [[PDF]](https://arxiv.org/pdf/2403.12031) ![Benchmark](https://img.shields.io/badge/benchmark-blue)
  - Qitian Jason Hu, Jacob Bieker, Xiuyu Li, Nan Jiang, Benjamin Keigwin, Gaurav Ranganath, Kurt Keutzer, Shriyash Kaustubh Upadhyay
  - Code: https://github.com/withmartian/routerbench
- Fly-Swat or Cannon? Cost-Effective Language Model Choice via Meta-Modeling (WSDM 2024) [[PDF]](https://arxiv.org/pdf/2308.06077) 
  - Marija Šakota, Maxime Peyrard, Robert West 
- Routing to the Expert: Efficient Reward-guided Ensemble of Large Language Models (NAACL 2024) [[PDF]](https://aclanthology.org/2024.naacl-long.109.pdf)
  - Keming Lu, Hongyi Yuan, Runji Lin, Junyang Lin, Zheng Yuan, Chang Zhou, Jingren Zhou

## Ensemble
- Efficient Online ML API Selection for Multi-Label Classification Tasks (ICML 2022) [[PDF]](https://arxiv.org/pdf/2102.09127)
  - Lingjiao Chen, Matei Zaharia, James Zou
- LLM-Blender: Ensembling Large Language Models with Pairwise Ranking and Generative Fusion (ACL 2023) [[PDF]](https://arxiv.org/pdf/2306.02561)
  - Dongfu Jiang, Xiang Ren, Bill Yuchen Lin
- More Agents Is All You Need (arXiv, 2024) [[PDF]](https://arxiv.org/pdf/2402.05120)
  - Junyou Li, Qin Zhang, Yangbin Yu, Qiang Fu, Deheng Ye

## Cascade
- FrugalML: How to Use ML Prediction APIs More Accurately and Cheaply (NIPS 2020) [[PDF]](https://arxiv.org/pdf/2006.07512)
  - Lingjiao Chen, Matei Zaharia, James Zou
- Model Cascading: Towards Jointly Improving Efficiency and Accuracy of NLP Systems (EMNLP 2022) [[PDF]](https://arxiv.org/pdf/2210.05528)
  - Neeraj Varshney, Chitta Baral
- FrugalGPT: How to Use Large Language Models While Reducing Cost and Improving Performance (arXiv, 2023) [[PDF]](https://arxiv.org/pdf/2305.05176)
  - Lingjiao Chen, Matei Zaharia, James Zou
- Online Cascade Learning for Efficient Inference over Streams (ICML 2024) [[PDF]](https://arxiv.org/pdf/2402.04513) 
  - Lunyiu Nie, Zhimin Ding, Erdong Hu, Christopher Jermaine, Swarat Chaudhuri
  - Code: https://github.com/Flitternie/online_cascade_learning
- Language Model Cascades: Token-level uncertainty and beyond (ICLR 2024) [[PDF]](https://arxiv.org/pdf/2404.10136)
  - Neha Gupta, Harikrishna Narasimhan, Wittawat Jitkrittum, Ankit Singh Rawat, Aditya Krishna Menon, Sanjiv Kumar
- Large Language Model Cascades with Mixture of Thoughts Representations for Cost-efficient Reasoning (ICLR 2024) [[PDF]](https://arxiv.org/pdf/2310.03094)
  - Murong Yue, Jie Zhao, Min Zhang, Liang Du, Ziyu Yao
- Cascade-Aware Training of Language Models (arXiv, 2024) [[PDF]](https://arxiv.org/pdf/2406.00060)
  - Congchao Wang, Sean Augenstein, Keith Rush, Wittawat Jitkrittum, Harikrishna Narasimhan, Ankit Singh Rawat, Aditya Krishna Menon, Alec Go

## Speculative Decoding
- Fast Inference from Transformers via Speculative Decoding (ICML 2023) [[PDF]](https://arxiv.org/pdf/2211.17192)
  - Yaniv Leviathan, Matan Kalman, Yossi Matias
- SpecInfer: Accelerating Generative Large Language Model Serving with Tree-based Speculative Inference and Verification (ASPLOS 2024) [[PDF]](https://arxiv.org/pdf/2305.09781)
  - Xupeng Miao, Gabriele Oliaro, Zhihao Zhang, Xinhao Cheng, Zeyu Wang, Zhengxin Zhang, Rae Ying Yee Wong, Alan Zhu, Lijie Yang, Xiaoxiang Shi, Chunan Shi, Zhuoming Chen, Daiyaan Arfeen, Reyna Abhyankar, Zhihao Jia
- Faster Cascades via Speculative Decoding (arXiv, 2024) [[PDF]](https://arxiv.org/pdf/2405.19261)
  - Harikrishna Narasimhan, Wittawat Jitkrittum, Ankit Singh Rawat, Seungyeon Kim, Neha Gupta, Aditya Krishna Menon, Sanjiv Kumar

## LLM Programming Framework
- Prompting Is Programming: A Query Language for Large Language Models (PLDI 2023) [[PDF]](https://arxiv.org/pdf/2212.06094)
  - Luca Beurer-Kellner, Marc Fischer, Martin Vechev
  - Code: https://github.com/eth-sri/lmql ![Stars](https://img.shields.io/github/stars/eth-sri/lmql)
- DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines (R0-FoMo Workshop, 2023) [[PDF]](https://arxiv.org/pdf/2310.03714)
  - Omar Khattab, Arnav Singhvi, Paridhi Maheshwari, Zhiyuan Zhang, Keshav Santhanam, Sri Vardhamanan, Saiful Haq, Ashutosh Sharma, Thomas T. Joshi, Hanna Moazam, Heather Miller, Matei Zaharia, Christopher Potts
  - Code: https://github.com/stanfordnlp/dspy ![Stars](https://img.shields.io/github/stars/stanfordnlp/dspy)
- Language Agents as Optimizable Graphs (ICML 2024) [[PDF]](https://arxiv.org/pdf/2402.16823)
  - Mingchen Zhuge, Wenyi Wang, Louis Kirsch, Francesco Faccio, Dmitrii Khizbullin, Jürgen Schmidhuber
  - Code: https://github.com/metauto-ai/gptswarm ![Stars](https://img.shields.io/github/stars/metauto-ai/gptswarm)
- SGLang: Efficient Execution of Structured Language Model Programs (arXiv, 2024) [[PDF]](https://arxiv.org/pdf/2312.07104)
  - Lianmin Zheng, Liangsheng Yin, Zhiqiang Xie, Chuyue Sun, Jeff Huang, Cody Hao Yu, Shiyi Cao, Christos Kozyrakis, Ion Stoica, Joseph E. Gonzalez, Clark Barrett, Ying Sheng
  - Code: https://github.com/sgl-project/sglang ![Stars](https://img.shields.io/github/stars/sgl-project/sglang)
- A Declarative System for Optimizing AI Workloads (arXiv, 2024) [[PDF]](https://arxiv.org/pdf/2405.14696)
  - Chunwei Liu, Matthew Russo, Michael Cafarella, Lei Cao, Peter Baille Chen, Zui Chen, Michael Franklin, Tim Kraska, Samuel Madden, Gerardo Vitagliano
  - Code: https://github.com/mitdbg/palimpzest ![Stars](https://img.shields.io/github/stars/mitdbg/palimpzest)