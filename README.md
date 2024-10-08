<p align="center">
  <br>
  <img width="600" src="./imgs/IR with LLM.jpg" alt="logo of awesome repository">
  <br>
  <br>
</p>

# Awesome Information Retrieval in the Age of Large Language Model

> A curated list of awesome papers about information retrieval (IR) in the age of large language model (LLM). These include retrieval augmented large language model, large language model for information retrieval, and so on. If I missed any papers, feel free to open a PR to include them! And any feedback and contributions are welcome! 

This list is currently maintained by [Yinqiong Cai](https://caiyinqiong.github.io/resume/), [Yu-An Liu](https://davion-liu.github.io/), [Shiyu Nee](https://shiyunee.github.io/), and [Hengran Zhang](https://hengran.github.io/) at CAS Key Lab of Network Data Science and Technology, ICT, CAS. 

We thank all the great contributors very much.

## Contents
- [Survey](#survey)
  * [Retrieval Augmented LLM](#retrieval-augmented-LLM)
  * [LLM for IR](#LL-augmented-LLM)

- [Perspective Papers](#LLM-for-IR)

- [Retrieval Augmented LLM](#retrieval-augmented-LLM)
  * [For Pre-training LLM](#for-pre-training-llm)  
  * [For Fine-tuning LLM](#for-fine-tuning-llm)        
  * [For Inference of LLM](#for-inference-of-llm)
  * [Joint Optimization of IR and LLM](#joint-optimization-of-ir-and-llm) 

- [LLM for IR](#LLM-for-IR)
  * [Generating Synthetic Queries](#generating-synthetic-queries)  
  * [Generating Synthetic Documents](#generating-synthetic-documents) 
  * [Generating Ranking Lists](#generating-ranking-lists)
  * [Query Understanding](#query-understanding)
  * [Query Extension](#query-extension)      
  * [Generate rather than Retrieve](#generate-rather-than-retrieve) 
- [LLM for IR](#Bias-for-IR)
- [Benchmark and Evaluation](#benchmark-and-evaluation)
- [Toolkits](#toolkits)


## Survey
### Retrieval Augmented LLM
- [Retrieval-based Language Models and Applications](https://acl2023-retrieval-lm.github.io/) *Akari Asai et.al.* ACL 2023. (**Tutorial**)
- [Augmented Language Models: a Survey](https://arxiv.org/pdf/2302.07842.pdf) *Grégoire Mialon et.al.* Arxiv 2023.
- [Information Retrieval Meets Large Language Models: A Strategic Report from Chinese IR Community](https://arxiv.org/pdf/2307.09751.pdf) *Qingyao Ai et.al.* Arxiv 2023.
- [Retrieval-Augmented Generation for Large Language Models: A Survey](https://arxiv.org/pdf/2312.10997.pdf). *Yunfan Gao et.al.* Arxiv 2023.
- [A Survey on RAG Meets LLMs: Towards Retrieval-Augmented Large Language Models](https://arxiv.org/abs/2405.06211). *Yujuan Ding et.al.* Arxiv 2024.

### LLM for IR
- [Large Language Models for Information Retrieval: A Survey](https://arxiv.org/pdf/2308.07107.pdf) *Yutao Zhu et.al.* Arxiv 2023.

## Perspective Papers
- [Perspectives on Large Language Models for Relevance Judgment](https://arxiv.org/pdf/2304.09161.pdf) *Guglielmo Faggioli et.al.* ICTIR 2023. (**Best paper**)
- [Information Retrieval Meets Large Language Models](https://dl.acm.org/doi/pdf/10.1145/3589335.3641299). *Zheng Liu et.al.* WWW 2024.

## Retrieval Augmented LLM

### For Pre-training LLM

- [REALM: Retrieval augmented language model pre-training.](http://proceedings.mlr.press/v119/guu20a/guu20a.pdf) *Kelvin Guu et.al.* ICML 2020.
- [Improving language models by retrieving from trillions of tokens.](https://arxiv.org/pdf/2112.04426.pdf) *Sebastian Borgeaud et.al.* ICML 2022. (**RETRO**)
- [Shall We Pretrain Autoregressive Language Models with Retrieval? A Comprehensive Study.](https://arxiv.org/pdf/2304.06762) *Boxin Wang et.al.* Arxiv 2023.

### For Fine-tuning LLM

- [Dense Passage Retrieval for open-domain question answering.](https://arxiv.org/abs/2004.04906) *Vladimir Karpukhin et.al.* EMNLP 2020. (**DPR**)
- [RAG: Retrieval-augmented generation for knowledge-intensive NLP tasks.](https://arxiv.org/pdf/2005.12989) *Patrick Lewis et.al.* NeurIPS 2020.
- [FiD: Leveraging passage retrieval with generative models for open domain question answering.](https://arxiv.org/pdf/2007.01282) *Gautier Izacard, Edouard Grave* EACL 2021.
- [Copy Is All You Need.](https://arxiv.org/abs/2307.06962) *Tian Lan et.al.* ICLR 2023. (**COG**)
- [Chain-of-Note: Enhancing Robustness in Retrieval-Augmented Language Models.](https://arxiv.org/abs/2311.09210) *Wenhao Yu et.al.* Arxiv 2023. (**Chain-of-Note**)

### For Inference of LLM

- [Generalization through memorization: Nearest neighbor language models.](https://arxiv.org/pdf/1911.00172.pdf) *Urvashi Khandelwal et.al.* Arxiv 2019.
- [Interleaving retrieval with chain-of-thought reasoning for knowledge-intensive multi-step questions.](https://arxiv.org/pdf/2212.10509) *Harsh Trivedi et.al.* Arxiv 2022.
- [Rethinking with retrieval: Faithful large language model inference.](https://arxiv.org/pdf/2301.00303) *Hangfeng He et.al.* Arxiv 2023.
- [Investigating the Factual Knowledge Boundary of Large Language Models with Retrieval Augmentation](https://arxiv.org/abs/2307.11019) *Ruiyang Ren et.al.* Arxiv 2023.
- [When Not to Trust Language Models: Investigating Effectiveness of Parametric and Non-Parametric Memories](https://arxiv.org/abs/2212.10511). *Alex Mallen et.al.* ACL 2023.
- [When Do LLMs Need Retrieval Augmentation? Mitigating LLMs’ Overconfidence Helps Retrieval Augmentation](https://arxiv.org/pdf/2402.11457.pdf) *Shiyu Ni et.al.* Arxiv 2024.


### Joint Optimization of IR and LLM

- [Atlas: Few-shot Learning with Retrieval Augmented Language Models.](https://arxiv.org/pdf/2208.03299.pdf?trk=public_post_comment-text) *Gautier Izacard et.al.*  Arxiv 2022.
- [REPLUG: Retrieval-Augmented Black-Box Language Models.](https://arxiv.org/pdf/2301.12652) *Weijia Shi et.al.* Arxiv 2023.
- [Learning to Retrieve In-Context Examples for Large Language Models.](https://arxiv.org/pdf/2307.07164.pdf) *Liang Wang et.al.* Arxiv 2023.


## LLM for IR

### Generating Synthetic Queries

- [InPars: Data augmentation for information retrieval using large language models.](https://arxiv.org/pdf/2202.05144) *Luiz Bonifacio et.al.* SIGIR 2022.
- [UPR: Improving passage retrieval with zero-shot question generation.](https://arxiv.org/pdf/2204.07496) *Devendra Singh Sachan et.al.* EMNLP 2022.
- [Promptagator: Fewshot dense retrieval from 8 examples.](https://arxiv.org/pdf/2209.11755) *Zhuyun Dai et.al.* ICLR 2023.

### Generating Synthetic Documents

- [Precise Zero-Shot Dense Retrieval without Relevance Labels.](https://arxiv.org/pdf/2212.10496) *Luyu Gao et.al.* Arxiv 2022.
- [Generating Synthetic Documents for Cross-Encoder Re-Rankers: A Comparative Study of ChatGPT and Human Experts.](https://arxiv.org/pdf/2305.02320) *Arian Askari et.al.* Arxiv 2023.

### Generating Ranking Lists

- [Is ChatGPT Good at Search? Investigating Large Language Models as Re-Ranking Agent.](https://arxiv.org/pdf/2304.09542) *Weiwei Sun et.al.* Arxiv 2023.
- [Zero-Shot Listwise Document Reranking with a Large Language Model.](https://arxiv.org/pdf/2305.02156) *Xueguang Ma et.al.* Arxiv 2023.
- [Are Large Language Models Good at Utility Judgments?](https://arxiv.org/pdf/2403.19216) *Hengran Zhang et.al.* SIGIR 2024.
- [RankRAG: Unifying Context Ranking with Retrieval-Augmented Generation in LLMs](https://arxiv.org/html/2407.02485v1) *Yue Yu et.al.* Arxiv 2024.
- [Iterative Utility Judgment Framework via LLMs Inspired by Relevance in Philosophy](https://arxiv.org/abs/2406.11290) *Hengran Zhang et.al.* Arxiv 2024.


### Query Understanding

- [Query Understanding in the Age of Large Language Models.](https://arxiv.org/pdf/2306.16004) *Avishek Anand et.al.* Gen-IR 2023.

### Query Extension

- [Generative relevance feedback with large language models.](https://arxiv.org/pdf/2304.13157) *Iain Mackie et.al.* Arxiv 2023.
- [Query2doc: Query expansion with large language models.](https://arxiv.org/pdf/2303.07678) *Liang Wang et.al.* Arxiv 2023.
- [Enhancing Retrieval-Augmented Large Language Models with Iterative Retrieval-Generation Synergy](https://aclanthology.org/2023.findings-emnlp.620/) *Zhihong Shao et al.* findings of EMNLP 2023

### Generate rather than Retrieve

- [Generate rather than retrieve: Large language models are strong context generators.](https://arxiv.org/pdf/2209.10063) *Wenhao Yu et.al.* ICLR 2023.

## Bias for IR

- [LLMs may Dominate Information Access: Neural Retrievers are Biased Towards LLM-Generated Texts](https://arxiv.org/abs/2310.20501). *Sunhao Dai et.al.* Arxiv 2023.


## Benchmark and Evaluation

- [KILT: a benchmark for knowledge intensive language tasks.](https://arxiv.org/pdf/2009.02252) *Fabio Petroni et.al.* NAACL 2021.

## Toolkits

- [RETA-LLM: A Retrieval-Augmented Large Language Model Toolkit.](https://arxiv.org/pdf/2306.05212) *Jiongnan Liu et.al.* Arxiv 2023. [RETA-LLM](https://github.com/RUC-GSAI/YuLan-IR/tree/main/RETA-LLM)

## Note

- Shiyu is currently focusing on the timing for triggering RAG (when to retrieve) based on the responses from the LLMs. Regarding the papers, you can visit https://github.com/ShiyuNee/Awesome-Calibration-Papers
