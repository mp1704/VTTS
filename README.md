# VTTS - Vietnamese Text-to-Speech Model Collections

A curated collection of Vietnamese Text-to-Speech (TTS) models that I have fine-tuned for high-quality Vietnamese speech synthesis. This repository serves as a central hub for accessing various TTS architectures optimized for Vietnamese language.

## 🎯 Overview

This project focuses on developing and fine-tuning state-of-the-art TTS models specifically for Vietnamese language. The models are trained to handle Vietnamese phonetics, tones, and linguistic characteristics to produce natural-sounding speech.

## 🚀 Available Models

### CSM 1B (Conversational Speech Model)
- **Type**: Large Language Model with TTS capabilities
- **Training**: Fine-tuned with LoRA adapter
- **Training Data**: 65 hours across 10 speakers
- **Checkpoint**: [Hugging Face - LoRA Adapter](https://huggingface.co/mp1704/adapter_65h_10speakers)

### VITS (Variational Inference Text-to-Speech)
- **Type**: End-to-end neural TTS model
- **Training Data**: 6 hours 40 minutes of radio speech data
- **Checkpoint**: [Hugging Face - VITS Model](https://huggingface.co/mp1704/vits_tram_radio_6h40)



## 📊 Model Performance

| Model | Training Hours | Speakers | Language | Quality Score |
|-------|----------------|----------|----------|---------------|
| CSM 1B | 65h | 10 | Vietnamese | ?? |
| VITS | 6h 40m | 1 | Vietnamese | ?? |

## 🤝 Ready to Collaborate!

I'm passionate about TTS research and always excited to collaborate with fellow researchers, developers, and enthusiasts! Whether you're working on:
- Vietnamese language processing
- TTS model improvements
- Dataset collection and curation
- Real-world applications
- Cross-language TTS research

---

**Note**: This is an ongoing project. More models and features will be added regularly. Star ⭐ this repository to stay updated!