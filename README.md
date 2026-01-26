# Awesome Arabic AI 🚀

<div align="center">
  <img src="assets/logo.png" alt="Awesome Arabic AI Logo" width="200" height="200">
  <p><b>A Comprehensive Hub for Open-Source Arabic Speech and Language Technologies</b></p>

  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
  [![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
  [![Maintainer](https://img.shields.io/badge/Maintainer-Open--Source%20AI%20Researcher-orange.svg)](https://github.com/omarsalah)
</div>

---

## 📖 Introduction

**Awesome-Arabic-AI** is the definitive hub for open-source advancements in Arabic Large Language Models (LLMs), Text-to-Speech (TTS), and Speech-to-Text (STT) technologies. Arabic, spoken by over 400 million people, presents unique computational challenges—from its complex morphology and lack of diacritics to the profound state of diglossia (MSA vs. Dialects). 

This repository synthesizes current research, institutional leadership, and state-of-the-art model benchmarks to provide a strategic foundation for researchers and developers navigating the burgeoning Arabic AI ecosystem.

---

## 🗺️ Table of Contents

- [Large Language Models (LLMs)](#-large-language-models-llms)
- [Speech Technologies](#-speech-technologies)
  - [Speech-to-Text (STT/ASR)](#speech-to-text-sttasr)
  - [Text-to-Speech (TTS)](#text-to-speech-tts)
  - [Diacritization (Tashkeel)](#diacritization-tashkeel)
- [Data and Evaluation](#-data-and-evaluation)
  - [Corpora](#corpora)
  - [Leaderboards & Benchmarks](#leaderboards--benchmarks)
- [Tools and Libraries](#-tools-and-libraries)
- [Institutional Leadership](#-institutional-leadership)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🧠 Large Language Models (LLMs)

Arabic LLMs have evolved from encoder-based architectures (AraBERT) to massive generative models (Jais, Falcon) and efficient Mixture-of-Experts (MoE) frameworks.

### 🏆 Featured Models

| Model Family | Developer | Architecture | Parameter Sizes | License | Primary Focus |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **AraBERT** | AUB-MIND | Encoder (BERT) | 110M - 340M | Apache 2.0 | NLU, Sentiment Analysis |
| **Jais** | Inception (G42) | Decoder-only | 13B, 30B, 70B | Apache 2.0 | Arabic-centric foundational knowledge |
| **AceGPT-v2** | KAUST / CUHKSZ | Llama 3 Based | 8B, 32B, 70B | Llama 3 | Instruction-following, Dialogue |
| **Qwen3** | Alibaba | MoE | 8B - 235B | Apache 2.0 | Multilingual reasoning, MoE efficiency |
| **Falcon 3** | TII | Decoder-only | 1B, 3B, 7B, 10B | Apache 2.0 | High-performance small models |
| **SILMA** | Silma AI | Gemma Based | 9B | Gemma | Optimized for RAG and Arabic speed |
| **Allam** | KSAA | Decoder-only | 7B | Apache 2.0 | Saudi sovereign model |
| **Fanar-1** | QCRI | Decoder-only | 9B | Apache 2.0 | Qatar sovereign model |

> **Key Insight:** Specialized tokenizers are critical for Arabic. Models like Jais and AceGPT utilize custom tokenizers to minimize the "fertility score" (tokens per word), improving efficiency and syntactic grasp.

---

## 🎙️ Speech Technologies

### Speech-to-Text (STT/ASR)

Arabic ASR must bridge the gap between Phonetic MSA and diversas spoken dialects.

| Model / System | Architecture | Params | VRAM Req. | Primary Use Case |
| :--- | :--- | :--- | :--- | :--- |
| **Munsit (NADI 2025)** | Conformer-Large | 121M | High | Multidialectal ASR leader |
| **Whisper Large V3** | Transformer Enc-Dec | 1.55B | ~10GB | Global multilingual standard |
| **Whisper V3 Turbo** | Transformer Enc-Dec | 809M | ~6GB | High-speed throughput |
| **ArTST v2** | Unified Transformer | Base | Moderate | Dialect-specific recognition |
| **MMS** | Wav2Vec2 | 1B | Moderate | Support for 1,100+ languages |
| **Granite Speech 3.3** | Encoder-only | 8B | High | Enterprise-grade translation |

### Text-to-Speech (TTS)

High-quality Arabic TTS requires a robust pipeline: `Text -> Diacritizer -> Mel-Spectrogram -> Vocoder`.

- **[tts_arabic](https://github.com/pndurette/tts-arabic)**: Offline solution using FastPitch ($46.3M$ params) and Mixer-TTS ($1.5M-2.9M$ params).
- **F5-TTS**: Diffusion-based synthesis for natural prosody.

### Diacritization (Tashkeel)

The prerequisite for natural-sounding speech and accurate NLU.

| Model Name | Architecture | Key Metrics | Notes |
| :--- | :--- | :--- | :--- |
| **Sadeed** | SLM Decoder-only | Competitive with LLMs | Fine-tuned on noise-free text |
| **CATT** | Char-Transformer | ED/EO model options | Official diacritization toolkit |
| **Shakkala** | Bi-LSTM | DER: 1.69% | State-of-the-art accuracy |
| **Hareef / Sarf** | Deep GRU + Transf. | Standardized metrics | Supports ONNX export |

---

## 📊 Data and Evaluation

### Corpora

- **ArabicWeb16**: 150M web pages covering major regional dialects.
- **OSCAR**: Massive multilingual corpus from Common Crawl.
- **1.5 Billion Words Corpus**: Formal text from news sources across 10 countries.
- **Shami Corpus**: 117k+ sentences for Levantine dialect adaptation.
- **Common Voice (Arabic)**: Community-driven speech dataset.

### Leaderboards & Benchmarks

| Benchmark | Focus Area | Main Metrics |
| :--- | :--- | :--- |
| **[OALL](https://huggingface.co/spaces/TIIUAE/open-arabic-llm-leaderboard)** | General NLP & RAG | MMLU, Grammar, Trust |
| **[ArabicMMLU](https://github.com/mbzuai-nlp/arabic-mmlu)** | Native School Exams | 14,575 Native MCQs |
| **[ArabLegalEval](https://huggingface.co/datasets/KSAA/ArabLegalEval)** | Legal Knowledge | Multitask Saudi-based Law |
| **[AraTrust / AraSafe](https://huggingface.co/datasets/KSAA/AraTrust)** | Safety | Red-teaming & Hallucination |
| **NADI Shared Tasks** | Dialects | Accuracy, WER, CER |

---

## 🛠️ Tools and Libraries

- **[Camel-tools](https://github.com/CAMeL-Lab/camel_tools)**: Suite of Arabic NLP tools (morphology, NER, sentiment).
- **[PyArabic](https://github.com/linuxscout/pyarabic)**: Library for Arabic text manipulation.
- **[Farasa](https://farasa.qcri.org/)**: High-speed segmenter and POS tagger.
- **[LM Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness)**: Now supporting many Arabic-specific tasks.

---

## 🚀 Demos and Interactive Notebooks

Experience Arabic AI in action:

- **[Jais-30B Chat Demo](https://huggingface.co/spaces/inceptionai/jais-30b-chat)**: Interactive chat with the leading Arabic-centric model.
- **[OALL Leaderboard](https://huggingface.co/spaces/TIIUAE/open-arabic-llm-leaderboard)**: Real-time rankings of the latest open-weight models.
- **[Whisper Arabic ASR Notebook](https://github.com/openai/whisper)**: Guide on fine-tuning Whisper for regional dialects.

---

## 🏛️ Institutional Leadership

Leading the charge in Arabic AI:

- **Technology Innovation Institute (TII), UAE**: Sponsors of Falcon and OALL.
- **MBZUAI, UAE**: Leaders in Aram Lab, ArTST, and ArabicMMLU.
- **KSAA, Saudi Arabia**: Operates the ARAI Center for linguistic tools.
- **G42 / Core42, UAE**: Developers of the Jais foundation models.
- **QCRI, Qatar**: Pioneers in speech processing and Fanar models.

---

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

1. Fork the Repo.
2. Create your Feature Branch.
3. Commit your Changes.
4. Push to the Branch.
5. Open a Pull Request.

---

## 📜 License

Distributed under the Apache 2.0 License. See `LICENSE` for more information.

---

## ✍️ Citation

If you use this repository in your research, please cite:

```bibtex
@misc{awesome-arabic-ai,
  author = {Awesome Arabic AI Community},
  title = {Awesome-Arabic-AI: A Hub for Open-Source Arabic Speech and Language Technologies},
  year = {2025},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/omarsalah/Awesome-Arabic-AI}}
}
```

<div align="center">
  <sub>Built with ❤️ for the Arabic AI Community.</sub>
</div>
