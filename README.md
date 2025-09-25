
# 🎨 AI Image Generation using Diffusion Models

This project demonstrates how to generate high-quality AI images from text prompts using **Stable Diffusion v1.5** with the Hugging Face **Diffusers** library.  

## 🚀 Features
- Text-to-image generation using diffusion models
- Works on **GPU (CUDA)**, **Apple Silicon (MPS)**, and **CPU**
- Supports **negative prompts** to remove unwanted artifacts
- Uses **Euler Ancestral Scheduler** for faster, sharper images
- Reproducible results with fixed seeds

---

## 🛠️ Installation
Install dependencies (if not on Google Colab):

```bash
pip install diffusers transformers accelerate torch torchvision safetensors
