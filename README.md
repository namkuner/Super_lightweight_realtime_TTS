# 🚀 Real-Time Text-to-Speech (TTS) - Ultra Fast & Lightweight

This project features a highly optimized real-time Text-to-Speech model designed for low-latency applications. Based on a modified architecture inspired by a research paper, this implementation significantly improves both inference speed and efficiency.
## 🌟 Highlights

- ⚙️ **2× faster** than the original implementation from the referenced paper.
- ⚡ **10× faster** than [XTTS](https://github.com/coqui-ai/TTS) and **60× faster** than [F5 TTS](https://github.com/bshall/flowtron).
- 🚀 Achieves **RTF ~0.055** on **NVIDIA T4 GPU**.
- 🧠 Custom model architecture and inference pipeline redesign for performance.
- 🧩 Designed for real-time voice synthesis tasks.

## 📊 Benchmark

| Model      | RTF (↓)     | Relative Speed |
|------------|-------------|----------------|
| This Model | **0.055**   | 1.0× (Baseline) |
| XTTS       | ~0.55       | 10× slower     |
| F5 TTS     | ~3.3        | 60× slower     |

## Demo

https://github.com/user-attachments/assets/422d0df7-8eb5-4333-88cd-b6a0564e19b6

