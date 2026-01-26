# Awesome Arabic AI 🚀

<div align="center">
  <img src="assets/logo.png" alt="Awesome Arabic AI Logo" width="200" height="200">
  <h1>Awesome Arabic AI</h1>
  <p><b>Democratizing Arabic AI by collecting the world's best open-source LLMs, Speech models, and Datasets.</b></p>

  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
  [![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
</div>

---

## 📖 Introduction

**Awesome-Arabic-AI** is the definitive hub for open-source advancements in Arabic Large Language Models (LLMs), Text-to-Speech (TTS), and Speech-to-Text (STT) technologies. Arabic, spoken by over 400 million people, presents unique computational challenges—from its complex morphology and lack of diacritics to the profound state of **diglossia** (the gap between MSA and spoken dialects). 

Our mission is to foster a community where state-of-the-art speech and language technologies are accessible and optimized for the linguistic richness of the Arab world.

---

## 🔥 New & Trending
The latest and most significant breakthroughs in the Arabic AI space:

- 🧠 **[AraModernBert (NAMAA)](https://huggingface.co/NAMAA-Space/AraModernBert-Base-V1.0)**: State-of-the-art Arabic ModernBERT, optimized for high performance and efficiency.
- 🗣️ **[Arabic-F5-TTS-v2 (Ibrahim Salah)](https://huggingface.co/IbrahimSalah/Arabic-F5-TTS-v2)**: Cutting-edge diffusion-based TTS for natural Arabic prosody.
- 👁️ **[Qari-OCR v0.3 (NAMAA)](https://huggingface.co/NAMAA-Space/Qari-OCR-v0.3-VL-2B-Instruct)**: High-fidelity vision model for complex Arabic documents.

---

## 🗺️ Table of Contents

- [Research Labs (NAMAA Space)](#-research-labs-namaa-space)
- [Text-to-Speech (TTS)](#️-text-to-speech-tts)
- [Large Language Models (LLMs)](#-large-language-models-llms)
- [Community & Dialectal Hubs](#-community--dialectal-hubs)
- [Datasets & Benchmarks](#-datasets--benchmarks)
- [⚖️ Model Comparison Table](#-model-comparison-table)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🧪 Research Labs: NAMAA Space Ecosystem
*Network for Advancing Modern ArabicNLP & AI*

| Model / Project | Type | Description | Link |
| :--- | :--- | :--- | :--- |
| **AraModernBERT** | LLM (Encoder) | SOTA Arabic ModernBERT (Base V1.0), optimized for 8K context length. | [HuggingFace](https://huggingface.co/NAMAA-Space/AraModernBert-Base-V1.0) |
| **Qari-OCR v0.3** | Vision/OCR | High-fidelity Arabic OCR based on Qwen2-VL, supports diacritics & complex layouts. | [HuggingFace](https://huggingface.co/NAMAA-Space/Qari-OCR-v0.3-VL-2B-Instruct) |
| **Jasmine** | LLM | Arabic GPT models optimized for few-shot learning (300M - 6.7B parameters). | [HuggingFace](https://huggingface.co/UBC-NLP/Jasmine-350M) |
| **NAMAA-MT-Saudi** | Translation | Saudi Dialect (Najdi, Hijazi) to English translation system. | [HuggingFace](https://huggingface.co/NAMAA-Space/NAMAA-MT-Saudi2English) |
| **Bojji / Zarra** | Embeddings | Ultra-lightweight static embedding models (Model2Vec) for fast CPU inference. | [Bojji](https://huggingface.co/NAMAA-Space/bojji) / [Zarra](https://huggingface.co/NAMAA-Space/zarra) |
| **Namaa-Reranker** | RAG Tool | High-performance reranker fine-tuned on mMARCO for Arabic IR. | [HuggingFace](https://huggingface.co/NAMAA-Space/Namaa-Reranker-v1) |

---

## 🗣️ Text-to-Speech (TTS) & Audio
*Top-tier open-source synthesis models.*

| Model Name | Developer | Links | Key Features |
| :--- | :--- | :--- | :--- |
| **Arabic-F5-TTS-v2** | Ibrahim Salah | [Model](https://huggingface.co/IbrahimSalah/Arabic-F5-TTS-v2) | Advanced F5-based TTS, supports full diacritics. |
| **Arabic-TTS-Spark** | Ibrahim Salah | [Space](https://huggingface.co/spaces/IbrahimSalah/Arabic-TTS-Spark) | Lightweight Spark-based synthesis. |
| **Chatterbox-Egyptian** | oddadmix | [Demo](https://huggingface.co/spaces/oddadmix/Chatterbox-Egyptian) | **Dialect Focus:** Specialized in Egyptian colloquial speech. |
| **Habibi-TTS** | SWivid | [Dataset](https://huggingface.co/datasets/SWivid/Habibi) | High-quality single-speaker dataset & model. |
| **Hamsa** | Silma AI | [Org](https://huggingface.co/silma-ai) | Full-stack Arabic speech suite. |

*   **Benchmarks:** [Silma Open Source Arabic TTS Benchmark](https://huggingface.co/spaces/silma-ai/opensource-arabic-tts-benchmark)
*   **Proprietary Baselines:** ElevenLabs, Google Gemini TTS, Google Chirp 3, OpenAI TTS Mini.

---

## 🧠 Large Language Models (LLMs)

### Featured Foundational Models
- **[Falcon-H1-Arabic (3B, 7B, 34B)](https://huggingface.co/tiiuae)**: Hybrid Mamba-Transformer architecture for superior efficiency (Jan 2026).
- **[Jais (G42)](https://huggingface.co/inceptionai/jais-30b-chat)**: Leading Arabic-centric foundational model.
- **[Falcon 3 (TII)](https://huggingface.co/tiiuae/falcon-3-7b)**: High-performance multilingual models with strong Arabic scores.
- **[Allam (KSAA)](https://huggingface.co/KSAA)**: Saudi sovereign model.

### Llama-3-Arabic Variants
- **[Arabic-llama3.1-16bit-FT](https://huggingface.co/Omartificial-Intelligence-Space/Arabic-llama3.1-16bit-FT)**: Fine-tuned on BigScience xP3.
- **[HeshamHaroon/Arabic-llama3](https://huggingface.co/HeshamHaroon/Arabic-llama3)**: Fine-tuned from Meta Llama 3.

---

## Community & Dialectal Hubs

- **Saudi Dialect Hub**: A unified hub by NAMAA for Saudi datasets and the **SAFIR Leaderboard**.
- **Shami-MT**: Syrian dialect translation systems by Omartificial Intelligence Space.
- **[NAMAA Research](https://www.namaa.space/research)**: Institutional-grade research and papers.
- **[ArabicNLP Conference](https://arabicnlp.org/)**: The premier scholarly venue for Arabic NLP.

---

## Datasets & Benchmarks

- **[Habibi Dataset](https://huggingface.co/datasets/SWivid/Habibi)**: Critical resource for Arabic TTS.
- **[OALL (Open Arabic LLM Leaderboard)](https://huggingface.co/spaces/TIIUAE/open-arabic-llm-leaderboard)**: The standard for LLM evaluation.
- **[SAFIR Leaderboard](https://huggingface.co/namaa-space)**: Multi-dialectal evaluation for Saudi Arabic.

---

## ⚖️ Model Comparison Table

| Feature | Hamsa (Silma AI) | Arabic-F5 v2 | Chatterbox-EG | ElevenLabs |
| :--- | :--- | :--- | :--- | :--- |
| **Access** | Open-Source | Open-Source | Open-Source | Proprietary |
| **Primary Focus** | High-end MSA | Performance | Egyptian Dialect | Global Standard |
| **Latency** | Low | Moderate | Moderate | API-Dependent |

---

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines. Researchers are encouraged to submit their models via Pull Request.

---

## 📜 License

Distributed under the Apache 2.0 License. See `LICENSE` for more information.


---

<div align="center">
  <sub>Built with ❤️ for the Arabic AI Community.</sub>
</div>
