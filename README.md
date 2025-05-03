# EmojiDM: Generate Emoji via Diffusion Models


---

## 🚀 Project Overview

**EmojiDM ** is an open‑source project that trains a diffusion‑based generative model to create novel emoji designs with state‑of‑the‑art denoising diffusion probabilistic models (DDPM).

This model is trained on this dataset:
https://huggingface.co/datasets/valhalla/emoji-dataset

- Train custom diffusion pipelines on emoji and icon collections  
- Sample high‑quality, diverse emoji at various resolutions  

---

## 📦 Features


- **Modular Training Pipeline**  
  - Configurable UNet or Transformer backbones  
  - Noise schedules: linear, cosine, learnable  
  - Mixed‑precision and multi‑GPU support via PyTorch Lightning

- **Inference & Sampling**  
  - Deterministic and stochastic samplers  
  - Batch sampling with optional guidance (classifier or CLIP)

- **Evaluation & Metrics**  
  - FID, Inception Score, and human preference logging  
  - Built‑in visualization dashboards with TensorBoard

---

## ⚙️ Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/GunaDD/emoji-diffusion-model.git
   ```
