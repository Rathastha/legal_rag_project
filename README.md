# 🚀 Multilingual Legal RAG System

## 📌 Overview

This project implements a Retrieval-Augmented Generation (RAG) pipeline for Indian legal judgments, enabling multilingual query understanding and context-aware response generation.

## 📂 Dataset

Dataset sourced from **Vihaan's Legal Dataset on Hugging Face**, containing Indian legal case documents.

## 🚀 Key Highlights

* Multilingual legal query support
* Legal-aware intelligent chunking
* Semantic retrieval using embeddings
* Reduced hallucination using RAG pipeline

## 🧠 Architecture

Input Query → Embedding → Vector Search → Context Retrieval → LLM Response

## 🛠 Tech Stack

* Python
* Sentence Transformers
* FAISS
* LLM (GPT / Qwen)

## 📁 Project Structure

* notebooks/ → Jupyter notebooks
* src/ → core logic
* data/ → datasets
* models/ → embeddings/models
* results/ → outputs

## ▶️ How to Run

pip install -r requirements.txt
jupyter notebook

## 📊 Results

* Improved retrieval accuracy
* Context-aware legal responses

## 🔮 Future Scope

* Voice-based legal assistant
* Web deployment
* Real-time legal search

## ⚠️ Note

Due to computational constraints, outputs are retained as-is. The pipeline is reproducible using the provided code.
