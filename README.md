# Awesome-AI-Learning

This repository is used to collect papers and code in the field of AI. The contents contain the following parts:

## Table of Content  
- [NLP](https://github.com/songqiang321/Awesome-AI-Papers/tree/main#nlp)
  - [Word2Vec](https://github.com/songqiang321/Awesome-AI-Papers/tree/main#1word2vec)
  - [Seq2Seq](https://github.com/songqiang321/Awesome-AI-Papers/tree/main#2seq2seq)
  - [Pretraining](https://github.com/songqiang321/Awesome-AI-Papers/tree/main#3pretraining)
- [CV](https://github.com/songqiang321/Awesome-AI-Papers/tree/main#cv)
- [Multimodal](#multimodal)
- [Reinforcement Learning](#reinforcement-learning)
- [GNN](#gnn)

---

## NLP

### 1. Word2Vec

- **Efficient Estimation of Word Representations in Vector Space**, _Mikolov et al._, arxiv 2013. \[[paper](https://arxiv.org/abs/1301.3781)\]
- **Distributed Representations of Words and Phrases and their Compositionality**, _Mikolov et al._, arxiv 2013. \[[paper](https://arxiv.org/abs/1310.4546)\]
- **Distributed representations of sentences and documents**, _Le and Mikolov_, ICML 2014. \[[paper](https://arxiv.org/abs/1405.4053)\]
- **Word2vec Explained: deriving Mikolov et al.'s negative-sampling word-embedding method**, _Goldberg and Levy_, arxiv 2014. \[[paper](https://arxiv.org/abs/1402.3722)\]
- **word2vec Parameter Learning Explained**, _Rong_, arxiv 2014. \[[paper](https://arxiv.org/abs/1411.2738)\]

### 2. Seq2Seq

- **Generating Sequences With Recurrent Neural Networks**, _Graves_, arxiv 2013. \[[paper](https://arxiv.org/abs/1308.0850)\]
- **Sequence to Sequence Learning with Neural Networks**, _Sutskever et al._, NeruIPS 2014. \[[paper](https://arxiv.org/abs/1409.3215)\]
- **Neural Machine Translation by Jointly Learning to Align and Translate**, _Bahdanau et al._, ICLR 2015. \[[paper](https://arxiv.org/abs/1409.0473)\]\[[code](https://github.com/lisa-groundhog/GroundHog)\]
- **On the Properties of Neural Machine Translation: Encoder-Decoder Approaches**, _Cho et al._, arxiv 2014. \[[paper](https://arxiv.org/abs/1409.1259)\]
- **Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation**, _Cho et al._, arxiv 2014. \[[paper](https://arxiv.org/abs/1406.1078)\]

### 3. Pretraining

- **Attention Is All You Need**, _Vaswani et al._, NIPS 2017. \[[paper](https://arxiv.org/abs/1706.03762)\]\[[code](https://github.com/tensorflow/tensor2tensor)\]
- GPT: **Improving language understanding by generative pre-training**, _Radford et al._, preprint 2018.  \[[paper](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf)\]\[[code](https://github.com/openai/finetune-transformer-lm)\]
- GPT-2: **Language Models are Unsupervised Multitask Learners**, _Radford et al._, OpenAI blog 2019. \[[paper](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)\]\[[code](https://github.com/openai/gpt-2)\]
- GPT-3: **Language Models are Few-Shot Learners**, _Brown et al._, NeurIPS 2020. \[[paper](https://arxiv.org/abs/2005.14165)\]\[[code]\]
- InstructGPT: **Training language models to follow instructions with human feedback**, _Ouyang et al._, NeurIPS 2022. \[[paper](https://arxiv.org/abs/2203.02155)\]\[[code]\]
- **BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding**, _Devlin et al._, arxiv 2018. \[[paper](https://arxiv.org/abs/1810.04805)\]\[[code](https://github.com/google-research/bert)\]
- **RoBERTa: A Robustly Optimized BERT Pretraining Approach**, _Liu et al._, arxiv 2019. \[[paper](https://arxiv.org/abs/1907.11692)\]\[[code](https://github.com/facebookresearch/fairseq)\]
- **What Does BERT Look At_An Analysis of BERT's Attention**, _Clark et al._, arxiv 2019. \[[paper](https://arxiv.org/abs/1906.04341)\]\[[code](https://github.com/clarkkev/attention-analysis)\]
- **DeBERTa: Decoding-enhanced BERT with Disentangled Attention**, _He et al._, ICLR 2021. \[[paper](https://arxiv.org/abs/2006.03654)\]\[[code](https://github.com/microsoft/DeBERTa)\]
- **DistilBERT: a distilled version of BERT_smaller, faster, cheaper and lighter** _Sanh et al._, arxiv 2019. \[[paper](https://arxiv.org/abs/1910.01108)\]\[[code](https://github.com/huggingface/transformers)\]
- **BERT Rediscovers the Classical NLP Pipeline**, _Tenney et al._, arxiv 2019. \[[paper](https://arxiv.org/abs/1905.05950)\]\[[code](https://github.com/nyu-mll/jiant)\]
- **TinyStories: How Small Can Language Models Be and Still Speak Coherent English**, _Eldan and Li_, arxiv 2023. \[[paper](https://arxiv.org/abs/2305.07759)\]\[[code]\]

#### 3.1 Large Language Model

- Anthropic: **Training a Helpful and Harmless Assistant with Reinforcement Learning from Human Feedback**, _Bai et al._, arxiv 2022. \[[paper](https://arxiv.org/abs/2204.05862)\]\[[code](https://github.com/anthropics/hh-rlhf)\]
- Anthropic: **Constitutional AI: Harmlessness from AI Feedback**, _Bai et al._, arxiv 2022. \[[paper](https://arxiv.org/abs/2212.08073)\]\[[code](https://github.com/anthropics/ConstitutionalHarmlessnessPaper)\]
- Anthropic: **Model Card and Evaluations for Claude Models**, Anthropic, 2023. \[[paper](https://www-files.anthropic.com/production/images/Model-Card-Claude-2.pdf)\]
- **BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension**, _Lewis et al._, arxiv 2019. \[[paper](https://arxiv.org/abs/1910.13461)\]\[[code]\]
- **Code Llama: Open Foundation Models for Code**, _Rozière et al._, arxiv 2023. \[[paper](https://arxiv.org/abs/2308.12950)\]\[[code](https://github.com/facebookresearch/codellama)\]
- Codex: **Evaluating Large Language Models Trained on Code**, _Chen et al._, arxiv 2021. \[[paper](https://arxiv.org/abs/2107.03374)\]\[[code](https://github.com/openai/human-eval)\]
- **Colossal-AI: A Unified Deep Learning System For Large-Scale Parallel Training**, _Li et al._, ICPP 2023. \[[paper](https://arxiv.org/abs/2110.14883)\]\[[code](https://github.com/hpcaitech/ColossalAI)\]
- **Gemini: A Family of Highly Capable Multimodal Models**, _Gemini Team, Google_, Google DeepMind 2023. \[[paper](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf)\]
- **GPT-4 Technical Report**, _OpenAI_, arxiv 2023. \[[paper](https://arxiv.org/abs/2303.08774)\]
- **GPT-4V(ision) System Card**, _OpenAI_, OpenAI blog 2023. \[[paper](https://openai.com/research/gpt-4v-system-card)\]
- **Sparks of Artificial General Intelligence_Early experiments with GPT-4**, _Bubeck et al._, arxiv 2023. \[[paper](https://arxiv.org/abs/2303.12712)\]
- **The Dawn of LMMs_Preliminary Explorations with GPT-4V(ision)**, _Yang et al._, arxiv 2023. \[[paper](https://arxiv.org/abs/2309.17421)\]\[[code](https://github.com/guidance-ai/guidance)\]
- **LaMDA: Language Models for Dialog Applications**, _Thoppilan et al._, arxiv 2022. \[[paper](https://arxiv.org/abs/2201.08239)\]
- **LLaMA: Open and Efficient Foundation Language Models**, _Touvron et al._, arxiv 2023. \[[paper](https://arxiv.org/abs/2302.13971)\]\[[code](https://github.com/facebookresearch/llama)\]
- **Llama 2: Open Foundation and Fine-Tuned Chat Models**, _Touvron et al._, arxiv 2023. \[[paper](https://arxiv.org/abs/2307.09288)\]\[[code](https://github.com/facebookresearch/llama)\]
- **Mistral 7B**, _Jiang et al._, arxiv 2023. \[[paper](https://arxiv.org/abs/2310.06825)\]\[[code](https://github.com/mistralai/mistral-src)\]
- Minerva: **Solving Quantitative Reasoning Problems with Language Models**, _Lewkowycz et al._, arxiv 2022. \[[paper](https://arxiv.org/abs/2206.14858)\]
- **PaLM: Scaling Language Modeling with Pathways**, _Chowdhery et al._, arxiv 2022. \[[paper](https://arxiv.org/abs/2204.02311)\]\[[code](https://github.com/lucidrains/PaLM-pytorch)\]
- **PaLM 2 Technical Report**, _Anil et al._, arxiv 2023. \[[paper](https://arxiv.org/abs/2305.10403)\]
- **PaLM-E: An Embodied Multimodal Language Model**, _Driess et al._, arxiv 2023. \[[paper](https://arxiv.org/abs/2303.03378)\]
- T5: **Exploring the limits of transfer learning with a unified text-to-text transformer**, _Raffel et al._, Journal of Machine Learning Research 2023. \[[paper](https://arxiv.org/abs/1910.10683)\]\[[code](https://github.com/google-research/text-to-text-transfer-transformer)\]
- **Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models**, _Wu et al._, arxiv 2023. \[[paper](https://arxiv.org/abs/2303.04671)\]\[[code](https://github.com/moymix/TaskMatrix)\]
- **WebGPT: Browser-assisted question-answering with human feedback**, _Nakano et al._, arxiv 2021. \[[paper](https://arxiv.org/abs/2112.09332)\]

#### 3.2 LLM Application

##### 3.2.1 AI Agent

##### 3.2.2 Academic

##### 3.2.3 Code

##### 3.2.4 Financial Application

##### 3.2.5 Information Retrieval

##### 3.2.6 Math

##### 3.2.7 Medicine and Law

##### 3.2.8 Recommend System

##### 3.2.9 Tool Learning

#### 3.3 LLM Technique

#### 3.4 LLM Theory

#### 3.5 Chinese Model

---

## CV

### 1. Basic for CV

### 2. Contrastive Learning

### 3. CV Application

### 4. Image Editing

### 5. Object Detection

### 6. Semantic Segmentation

### 7. Video

### 8. Survey for CV

---

## Multimodal

### 1. Audio

### 2. Blip

### 3. Clip

### 4. Diffusion Model

### 5. Multimodal LLM

### 6. Text2Image

### 7. Text2Video

### 8. Survey for Multimodal

### 9. Other

---

## Reinforcement Learning

### 1.Basic for RL

### 2. LLM for decision making 

---

## GNN

### Survey for GNN

