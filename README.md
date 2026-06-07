Overview:

This project builds a Question Answering (QA) system that accepts queries written in three different forms — standard Urdu script, English, and Roman Urdu — and returns relevant answers by searching through two bilingual datasets.
The system is built entirely on classical Information Retrieval using TF-IDF and cosine similarity. No GPU, no cloud API, and no large pretrained transformer model is required. Everything runs locally on a standard laptop.
The most original contribution of this project is the Roman Urdu normalization layer — the first end-to-end QA pipeline to handle Roman Urdu natively, filling a documented gap in NLP research for South Asian languages.

Datasets:

SQuAD v2(https://huggingface.co/datasets/rajpurkar/squad_v2) — Stanford Question Answering Dataset published in 2018. Contains Wikipedia article paragraphs in English with extractive question-answer pairs. Previous work achieved F1 ~93% using BERT, RoBERTa, and GPT-3.
UQA(https://huggingface.co/datasets/uqa/UQA ) — Urdu Question Answering dataset published at LREC-COLING 2024. Created by translating SQuAD2.0 into Urdu using the EATS technique. All prior work uses transformer models (XLM-RoBERTa F1: 85.99, mT5). This project establishes the first classical IR baseline on UQA.

Steps to run the code:
1. Download the python file
2. If using visual studio etc download all the libraries (used in the project_mentioned in first block)
3. IF using Colab run the code directly no need to download the libraries
4. Datasets will load automatically in Colab (path is there in the code)
5. For maually applying the datasets download the training and validation files of the datasets.

