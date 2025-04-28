# RAG_for_ML

This project compares the performance, response quality, and speed of three open-source Large Language Models (LLMs):

TinyLlama

Gemma (1B model)

DeepSeek R1

🛠️ Features
Loads and runs TinyLlama, Gemma, and DeepSeek models.

Compares response times and output quality for a common set of questions.

Clear separation of models for easy extension and analysis.

Minimal and clean pipeline for testing model answers to simple and technical queries.

📦 Requirements
Python 3.10+

Libraries:

transformers

torch

sentence-transformers (optional, for deeper evaluation)

faiss-cpu (optional, if retrieval is involved)

Hardware:

CPU for Gemma (optimized)

T4 GPU or TPU for faster inference (optional)
