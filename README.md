# LLM Benchmarking and Prompt Engineering

This project evaluates the performance of large language models (LLMs) on reasoning tasks using different prompting strategies and automatic evaluation metrics.

The goal of this project is to analyze how prompting techniques affect the quality of model-generated responses.

---

## Models

- DeepSeek-R1-Distill-Llama-8B
- DeepSeek-R1-Distill-Qwen-7B

Both models are loaded using the HuggingFace Transformers library and optimized with 4-bit quantization for efficient inference.

---

## Dataset

- GlaiveAI Reasoning v1 Dataset

This dataset contains reasoning-based question-answer pairs used to evaluate model responses.

---

## Prompting Strategies

The experiments include:

- Zero-shot prompting
- Few-shot prompting
- Chain-of-Thought (CoT) prompting
- Chat-style prompting

---

## Evaluation Metrics

Model responses are evaluated using:

- BLEU
- ROUGE
- BERTScore

These metrics measure the similarity between generated responses and reference answers.

---

## Notebook

The full experiment pipeline is implemented in a Jupyter Notebook:

`LLM_Benchmarking.ipynb`

---

## Run on Google Colab

You can run this project directly on Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1RG8uEE98gJGtnZ5ZkwRQoy-zRvVI8S3M?usp=sharing)

---

## Technologies

- Python
- PyTorch
- HuggingFace Transformers
- BitsAndBytes
- Pandas
- Datasets
