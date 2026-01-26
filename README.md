# Awesome Arabic AI 🚀

<div align="center">
  <img src="assets/logo.png" alt="Awesome Arabic AI Logo" width="200" height="200">
  <h1>Awesome Arabic AI</h1>
  <p><b>Democratizing Arabic AI by centralizing the world's best open-source LLMs, Speech models, and Datasets.</b></p>

  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
  [![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
</div>

---

## 📖 Introduction

**Awesome-Arabic-AI** is the definitive hub for open-source advancements in Arabic Large Language Models (LLMs), Text-to-Speech (TTS), and Speech-to-Text (STT) technologies. Arabic, spoken by over 400 million people, presents unique computational challenges—from its complex morphology and lack of diacritics to the profound state of **diglossia** (the gap between MSA and spoken dialects).

Our mission is to foster a community where state-of-the-art speech and language technologies are accessible and optimized for the linguistic richness of the Arab world, bridging the gap between academic research and practical application.

---

## 🔥 New & Trending

The latest and most significant breakthroughs in the Arabic AI space:

- 🗣️ **[Chatterbox-Egyptian](https://huggingface.co/oddadmix/chatterbox-egyptian-v0)**: A specialized model built on the Chatterbox architecture, fine-tuned specifically for **Egyptian Arabic (Masri)**.
- 📊 **[Silma Open-Source Benchmark](https://huggingface.co/spaces/silma-ai/opensource-arabic-tts-benchmark)**: A foundational benchmark prioritizing direct auditory assessment over standard metrics to capture the nuances of Arabic speech.

---

## 🗺️ Table of Contents

- [🔬 Research Spotlight: NAMAA Space](#-research-spotlight-namaa-space)
- [🗣️ Text-to-Speech (TTS)](#️-text-to-speech-tts)
- [🎙️ Speech-to-Text (STT)](#️-speech-to-text-stt)
- [🧠 Large Language Models (LLMs)](#-large-language-models-llms)
- [🌍 Dialectal AI & Community Hubs](#-dialectal-ai--community-hubs)
- [📊 Datasets & Benchmarks](#-datasets--benchmarks)
- [⚖️ Model Comparison Table](#-model-comparison-table)
- [👥 Key Researchers](#-key-researchers--organizations)
- [🤝Contributing](#-contributing)

---

## 🎙️ Arabic TTS Excellence

These models represent the cutting edge of open-source Arabic speech synthesis.

| Model Name | Developer/Author | Links | Notes |
| :--- | :--- | :--- | :--- |
| **Arabic-F5-TTS-v2** | Ibrahim Salah | [Model](https://huggingface.co/IbrahimSalah/Arabic-F5-TTS-v2) | Advanced F5-based Arabic TTS |
| **Arabic-TTS-Spark** | Ibrahim Salah | [Space](https://huggingface.co/spaces/IbrahimSalah/Arabic-TTS-Spark) | Spark-based Arabic synthesis |
| **Chatterbox-Egyptian** | oddadmix | [Model](https://huggingface.co/oddadmix/chatterbox-egyptian-v0) / [Demo](https://huggingface.co/spaces/oddadmix/Chatterbox-Egyptian) | Focus on Egyptian Dialect |
| **Habibi-TTS** | SWivid | [Model/Dataset](https://huggingface.co/datasets/SWivid/Habibi) | High-quality Arabic speech dataset & model |
| **Hamsa** | Silma AI | [Org](https://huggingface.co/silma-ai) | High-end Arabic TTS |
| **XTTS-v2 (Arabic)** | Coqui/Community | [Link](https://huggingface.co/lucasnewman/xtts-v2-arabic) | Multi-lingual support with Arabic fine-tuning |



## 🎙️ Speech-to-Text (STT)

### Foundational & Fine-tuned Models
- **[ArTST v2](https://huggingface.co/MBZUAI/ArTST)**: Unified Transformer for Arabic text and speech, supporting 17 dialects (MBZUAI).
- **[Whisper Large V3 Turbo (Arabic)](https://huggingface.co/mboushaba/whisper-large-v3-turbo-arabic)**: High-speed throughput fine-tuned for Arabic.
- **[Whisper-Large-V2-Arabic-5k](https://huggingface.co/clu-ling/whisper-large-v2-arabic-5k-steps)**: High accuracy on Common Voice.
- **[Whisper-Medium-Egyptian](https://huggingface.co/MAdel121/whisper-medium-egy)**: Specialized for Egyptian Arabic dialect.

---

## 🧠 Large Language Models (LLMs)

### Featured Foundational Models
- **[Falcon-H1-Arabic (3B, 7B, 34B)](https://huggingface.co/tiiuae)**: Latest models from TII with hybrid Mamba-Transformer architecture for superior Arabic performance (Jan 2026).
- **[Jais (G42)](https://huggingface.co/inceptionai/jais-30b-chat)**: The leading Arabic-centric foundational model.
- **[Falcon 3 (TII)](https://huggingface.co/tiiuae/falcon-3-7b)**: High-performance multilingual models.
- **[Allam (KSAA)](https://huggingface.co/KSAA)**: Saudi sovereign model.

### Llama-3-Arabic Variants
- **[Arabic-llama3.1-16bit-FT](https://huggingface.co/Omartificial-Intelligence-Space/Arabic-llama3.1-16bit-FT)**: Fine-tuned on BigScience xP3.
- **[HeshamHaroon/Arabic-llama3](https://huggingface.co/HeshamHaroon/Arabic-llama3)**: Fine-tuned from Meta Llama 3.

---

## 🌍 Dialectal AI & Community Hubs

Arabic is not just MSA. This section collects resources for specific regional dialects.

### 🇪🇬 Egyptian (Masri)
- **[Chatterbox-Egyptian](https://huggingface.co/oddadmix/chatterbox-egyptian-v0)**: State-of-the-art synthesis for Egyptian colloquialisms.
- **[EGTTS-v0.1](https://huggingface.co/models?search=EGTTS)**: Community effort for Egyptian dialect speech.

### 🇸🇦 Saudi & Gulf
- **[Saudi Dialect Hub (NAMAA)](https://huggingface.co/namaa-space)**: A unified hub for Saudi datasets and the SAFIR Leaderboard.
- **[NAMAA-MT-Saudi](https://huggingface.co/NAMAA-Space/NAMAA-MT-Saudi2English)**: Translation systems for Najdi and Hijazi.

### 🇱🇧 Levantine (Shami)
- **[Shami-MT](https://huggingface.co/Omartificial-Intelligence-Space)**: Syrian/Levantine dialect translation systems.

---

## 📊 Datasets & Benchmarks

- **[Silma TTS Benchmark](https://huggingface.co/spaces/silma-ai/opensource-arabic-tts-benchmark)**: The standard for open-source Arabic TTS evaluation.
- **[OALL (Open Arabic LLM Leaderboard)](https://huggingface.co/spaces/TIIUAE/open-arabic-llm-leaderboard)**: The standard for LLM evaluation.
- **[Habibi Dataset](https://huggingface.co/datasets/SWivid/Habibi)**: Critical high-quality audio dataset.
- **[Common Voice (Arabic)](https://commonvoice.mozilla.org/ar)**: Massive community-driven speech dataset.
- **[SAFIR Leaderboard](https://huggingface.co/namaa-space)**: Evaluation specifically for Saudi Arabic tasks.

---



## 👥 Key Researchers & Organizations

- **[Ibrahim Salah](https://huggingface.co/IbrahimSalah)**: Specialist in F5 and Spark TTS.
- **[NAMAA Space](https://www.namaa.space/research)**: Institutional-grade research in OCR, LLMs, and Dialects.
- **[oddadmix](https://huggingface.co/oddadmix)**: Focus on Dialectal/Egyptian AI.
- **[SWivid](https://huggingface.co/SWivid)**: Creators of the Habibi dataset.
- **[Silma AI](https://huggingface.co/silma-ai)**: Leading Arabic Benchmarks and high-end models.
- **[TII (Technology Innovation Institute)](https://huggingface.co/tiiuae)**: Developers of Falcon and primary Arabic leaderboards.

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
