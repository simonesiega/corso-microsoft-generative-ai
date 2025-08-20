# Lesson 2 - Exploring and Comparing Different LLMs

Large Language Models (LLMs) come in many forms, each designed for different purposes such as text, code, images, or audio, with different strengths, weaknesses, and applications.  

---

## Types of LLMs

LLMs can be specialized depending on the task:

- **Audio & Speech Recognition** → *Whisper* models for multilingual transcription and speech recognition.  
- **Image Generation** → *DALL·E*, *Stable Diffusion*, *Midjourney* for generating or editing images.  
- **Text & Code Generation** → GPT-3.5, GPT-4, and code-specific models like *CodeParrot*.  
- **Multimodal Models** → *GPT-4 Turbo with Vision*, *GPT-4o* for combining text and image understanding.  

---

## Foundation Models vs LLMs

- **Foundation Models** are very large, pretrained models built with unsupervised/self-supervised learning.  
- They act as a **base** for specialized models through fine-tuning.  
- Example: GPT-3.5 (foundation model) → ChatGPT (fine-tuned for conversation).  

![Foundation Models illustration](images/FoundationModel.png)

---

## Open Source vs Proprietary Models

- **Open-source models** → customizable and transparent (e.g., Alpaca, Bloom, LLaMA), but may lack optimization, maintenance, or enterprise support.  
- **Proprietary models** → optimized for production, higher performance (e.g., OpenAI GPT models, Google Bard, Claude), but closed-source and pay-to-use.  

---

## Model Categories by Output

- **Embeddings** – convert text into vectors for semantic search, clustering, and similarity tasks.  
- **Image Generation** – create or edit images (e.g., DALL·E, Stable Diffusion).  
- **Text & Code Generation** – generate natural language or code (e.g., GPT-4, CodeParrot).  

---

## Architectures: Encoder vs Decoder

- **Decoder-only** → text generation (e.g., GPT family).  
- **Encoder-only** → text understanding (e.g., BERT).  
- **Encoder-Decoder** → both understanding and generation (e.g., BART, T5).  

---

## Services vs Models

- **Model** → the raw neural network with weights/parameters (e.g., LLaMA). Requires infrastructure to run.  
- **Service** → packaged offering on the cloud (e.g., *Azure OpenAI Service*), with enterprise security, scaling, and pay-as-you-go pricing.  

---

## Improving LLM Results

There are multiple approaches to improve model performance:

- **Prompt Engineering with Context** → add examples and details in prompts for more accurate results.  
- **Retrieval Augmented Generation (RAG)** → enrich prompts with external data (using vector search).  
- **Fine-tuning** → further train a model on custom data for specialized accuracy.  
- **Training from scratch** → rarely used, requires massive resources, only for very domain-specific use cases.  

![Improving LLM Results](images/Deploy.png)

---

## Summary

- LLMs can be categorized by **task, architecture, modality, or licensing**.  
- **Foundation models** serve as the base for specialized LLMs.  
- Choosing between **open-source and proprietary** models depends on cost, customization, and performance needs.  
- **Azure AI Studio** provides tools to test, compare, fine-tune, and deploy models efficiently.  
- Businesses can improve results with **prompt engineering, RAG, or fine-tuning** depending on resources and requirements.  

---
