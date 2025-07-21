# 🧪 Experimental RAG Techniques

Welcome to the **Experimental RAG Techniques** repository! This repo contains various experimental techniques for implementing and optimizing certain aspects of Retrieval Augmented Generation (RAG) systems. For each technique, you can find a dedicated notebook file that goes into detail about the intuition behind the technique, how to implement it, and its potential benefits.

This repostiory is adjacent to Nir Diamant's [Advanced Rag Techniques Repo](https://github.com/NirDiamant/RAG_Techniques), which i highly recommend checking out. 

### ⁉️ What kind of tech are we talking about?

The techniques included in this repository are **experimental** in nature, meaning they may not have been extensively tested or validated in serious production environments. However, they represent innovative approaches to improving RAG systems and could lead to advancements in the field, which is why I wanted to share them with the community. _This repository is a place for experimentation and exploration, so please approach its contents with an open mind and a willingness to test and iterate_.

The techniques implemented in this repository primarily rely on **Traditional NLP** methods, which offer a strong balance between quality and efficiency. While these methods may not match the raw power of LLMs, they can still produce highly satisfactory results, especially when considering the **quality/latency tradeoff**. This makes them particularly suitable for RAG environments, where low latency and high quality are often two critical requirements.

### ⁉️ Can I contribute?

Absolutely! If you have a novel experimental technique that you've developed or even just thought about, please feel free to contact me. I would be happy to collaborate with you and credit you for your contribution. You can send me an email at **strano.lucass@gmail.com** or reach out to me on [LinkedIn](https://www.linkedin.com/in/strano-lucass/).

## 📑 Table of Contents

> Techniques marked with a 🧪 emoji are original contributions derived from my research that, to the best of my knowledge, have not been published or widely discussed elsewhere.

| # | Title | Type | Notebook |
|---|-------|------|----------|
| 1 | 🧪 **Dynamic K Estimation with Query Complexity Score** | 🎣 Retrieval | [![Github View](https://img.shields.io/badge/GitHub-View-blue)](https://github.com/LucaStrano/Experimental_RAG_Tech/blob/main/experimental_tech/1_estimating_k.ipynb) [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LucaStrano/Experimental_RAG_Tech/blob/main/experimental_tech/1_estimating_k.ipynb) |
| 2 | 🧪 **Single Pass Rerank and Compression with Recursive Reranking** | 🎣 Retrieval | [![Github View](https://img.shields.io/badge/GitHub-View-blue)](https://github.com/LucaStrano/Experimental_RAG_Tech/blob/main/experimental_tech/2_compress_and_rerank.ipynb) [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LucaStrano/Experimental_RAG_Tech/blob/main/experimental_tech/2_compress_and_rerank.ipynb) |
| 3 | 🧪 **Coming Soon!** | ❓ _Soon_ | _Coming Soon_ |

## 🔬 Techniques Overview

### 1. Dynamic K Estimation with Query Complexity Score

**Type: 🎣 Retrieval (🧪)**

This technique introduces a novel approach to dynamically estimate the optimal number of documents to retrieve (K) based on the complexity of the query. By using traditional NLP methods and by analyzing the query's structure and semantics, the (hyper)parameter K can be adjusted to ensure retrieval of the right amount of information needed for effective RAG.

### 2. Single Pass Rerank and Compression with Recursive Reranking

**Type: 🎣 Retrieval (🧪)**

This technique combines Reranking and Contextual Compression into a single pass by using a Reranker Model. Retrieved documents are broken down into smaller sub-sections, which are then used to both rerank documents by calculating an average score and compress them by statistically selecting only the most relevant sub-sections with regard to the user query.

## 🤝🏻 Acknowledgements

Made with 100% love and 0% Vibe Coding by [Luca Strano](https://www.linkedin.com/in/strano-lucass/) ❤️. Acknowledgements for future contributions and collaborations will go here!

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 