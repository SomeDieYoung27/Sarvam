# Cross-Lingual Word Embedding Alignment System

This repository contains the implementation of a **supervised cross-lingual word embedding alignment system** for English and Hindi using the **Procrustes method** as part of an assignment task. Additionally, an optional extra credit task involving **unsupervised alignment with Cross-Domain Similarity Local Scaling (CSLS)** and adversarial training is also provided.

## Table of Contents
1. [Assignment Description](#assignment-description)
2. [Repository Structure](#repository-structure)
3. [Instructions](#instructions)
4. [Task 1: Supervised Alignment (embedding.ipynb)](#task-1-supervised-alignment)
    - [Data Preparation](#data-preparation)
    - [Embedding Alignment](#embedding-alignment)
    - [Evaluation](#evaluation)
5. [Optional Extra Credit: Unsupervised Alignment (csls.ipynb)](#optional-extra-credit-unsupervised-alignment)
6. [Requirements](#requirements)
7. [Running the Code](#running-the-code)
8. [References](#references)

---

## Assignment Description
The main objective of this assignment is to implement and evaluate a **supervised cross-lingual word embedding alignment system** for English and Hindi. The task is divided into several parts:
1. **Data Preparation**: Training monolingual FastText embeddings or using pre-trained ones, and extracting a bilingual lexicon from the MUSE dataset.
2. **Embedding Alignment**: Implementing the Procrustes method to align the word embeddings.
3. **Evaluation**: Translating words from English to Hindi using the aligned embeddings and evaluating the translation accuracy using the MUSE test dictionary.

Optionally, an unsupervised alignment method with **CSLS** and **adversarial training** is implemented as described in the MUSE paper.

---

## Repository Structure
This repository contains two main Jupyter notebooks:
1. **`embedding.ipynb`** - Implements the supervised alignment task using the Procrustes method.
2. **`csls.ipynb`** - Implements the optional extra credit task using the unsupervised alignment method with CSLS and adversarial training.


