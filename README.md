<p align="center">
  <br>
  <img width="600" src="./imgs/IR with LLM.jpg" alt="logo of awesome repository">
  <br>
  <br>
</p>

# Awesome Information Retrieval in the Age of Large Language Model

> A curated list of awesome papers about information retrieval (IR) in the age of large language model (LLM). These include retrieval augmented large language model, large language model for information retrieval, and so on. If I missed any papers, feel free to open a PR to include them! And any feedback and contributions are welcome! 

This list is currently maintained by [Yinqiong Cai](https://caiyinqiong.github.io/resume/), [Yu-An Liu](https://davion-liu.github.io/), [Shiyu Nee](https://shiyunee.github.io/), and Hengran Zhang at CAS Key Lab of Network Data Science and Technology, ICT, CAS. 

We thank all the great contributors very much.

## Contents

- [Retrieval Augmented LLM](#retrieval-augmented-LLM)
  - [Survey](#survey) 
  - [For Pre-training LLM](#for-pre-training-llm)  
  - [For Fine-tuning LLM](#for-fine-tuning-llm)        
  - [For Inference of LLM](#for-inference-of-llm)
    * [Joint Optimization of IR and LLM](#joint-optimization-of-ir-and-llm) 

- [LLM for IR](#LLM-for-IR)
  * [Generating Synthetic Queries](#generating-synthetic-queries)  
  * [Generating Synthetic Documents](#generating-synthetic-documents) 
  * [Generating Ranking Lists](#generating-ranking-lists)
  	* [Query Understanding](#query-understanding)
  	* [Query Extension](#query-extension)      
  * [Generate rather than Retrieve](#generate-rather-than-retrieve) 
- [Benchmark and Evaluation](#benchmark-and-evaluation)
- [Toolkits](#toolkits)

## Retrieval Augmented LLM

### Survey

- [Augmented Language Models: a Survey](https://arxiv.org/pdf/2302.07842.pdf) *Grégoire Mialon et.al.* Arxiv 2023.

### For Pre-training LLM

- [REALM: Retrieval augmented language model pre-training.](http://proceedings.mlr.press/v119/guu20a/guu20a.pdf) *Kelvin Guu et.al.* ICML 2020.
- [Improving language models by retrieving from trillions of tokens.](https://arxiv.org/pdf/2112.04426.pdf) *Sebastian Borgeaud et.al.* ICML 2022. (**RETRO**)
- [Shall We Pretrain Autoregressive Language Models with Retrieval? A Comprehensive Study.](https://arxiv.org/pdf/2304.06762) *Boxin Wang et.al.* Arxiv 2023.

### For Fine-tuning LLM

- [Dense Passage Retrieval for open-domain question answering.](https://arxiv.org/abs/2004.04906) *Vladimir Karpukhin et.al.* EMNLP 2020. (**DPR**)
- [RAG: Retrieval-augmented generation for knowledge-intensive NLP tasks.](https://arxiv.org/pdf/2005.12989) *Patrick Lewis et.al.* NeurIPS 2020.
- [FiD: Leveraging passage retrieval with generative models for open domain question answering.](https://arxiv.org/pdf/2007.01282) *Gautier Izacard, Edouard Grave* EACL 2021.

### For Inference of LLM

- [Generalization through memorization: Nearest neighbor language models.](https://arxiv.org/pdf/1911.00172.pdf) *Urvashi Khandelwal et.al.* Arxiv 2019.
- [Interleaving retrieval with chain-of-thought reasoning for knowledge-intensive multi-step questions.](https://arxiv.org/pdf/2212.10509) *Harsh Trivedi et.al.* Arxiv 2022.
- [Rethinking with retrieval: Faithful large language model inference.](https://arxiv.org/pdf/2301.00303) *Hangfeng He et.al.* Arxiv 2023.


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

### Query Understanding

- [Query Understanding in the Age of Large Language Models.](https://arxiv.org/pdf/2306.16004) *Avishek Anand et.al.* Gen-IR 2023.

### Query Extension

- [Generative relevance feedback with large language models.](https://arxiv.org/pdf/2304.13157) *Iain Mackie et.al.* Arxiv 2023.
- [Query2doc: Query expansion with large language models.](https://arxiv.org/pdf/2303.07678) *Liang Wang et.al.* Arxiv 2023.

### Generate rather than Retrieve

- [Generate rather than retrieve: Large language models are strong context generators.](https://arxiv.org/pdf/2209.10063) *Wenhao Yu et.al.* ICLR 2023.


## Benchmark and Evaluation

- [KILT: a benchmark for knowledge intensive language tasks.](https://arxiv.org/pdf/2009.02252) *Fabio Petroni et.al.* NAACL 2021.

## Toolkits

- [RETA-LLM: A Retrieval-Augmented Large Language Model Toolkit.](https://arxiv.org/pdf/2306.05212) *Jiongnan Liu et.al.* Arxiv 2023. [RETA-LLM](https://github.com/RUC-GSAI/YuLan-IR/tree/main/RETA-LLM)
