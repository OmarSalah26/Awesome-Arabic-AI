# Arabic Speech Technologies 🎙️

Speech technologies in Arabic are divided into two main frontiers: capturing the spoken word (ASR) and synthesizing the written word (TTS). Both face the challenge of **Diglossia**—the gap between Modern Standard Arabic (MSA) and dialects.

## 🔍 Speech-to-Text (STT/ASR)

Modern Arabic ASR focuses on:
- **Dialect Identification**: Crucial for mapping regional variations.
- **Robustness**: Handling "in-the-wild" audio from YouTube and podcasts.
- **Low Resource Learning**: Using SSL (Self-Supervised Learning) to transfer knowledge from MSA to dialects.

## 🗣️ Text-to-Speech (TTS)

High-quality synthesis relies on the **Diacritization Pipeline**:
1. **Diacritizer**: Adding short vowels (Tashkeel).
2. **Spectrogram Gen**: FastPitch, Mixer-TTS.
3. **Vocoder**: HiFi-GAN, BigVGAN.

## 📝 Diacritization Models

Diacritization is not just for TTS; it is essential for:
- Machine Translation
- Language Learning
- Accessibility

---
[Back to Main README](../README.md)
