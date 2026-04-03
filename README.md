# AI Workshops

Hands-on workshops and build-alongs for modern AI systems — from fine-tuning and alignment to multimodal models and edge deployment.

This repository serves as a central hub for interactive notebooks that guide you through real-world AI workflows using tools like PyTorch, Hugging Face, and on-device runtimes.

---

## Overview

Each workshop is designed to be:

- **Practical** — focused on real implementation, not just theory  
- **Reproducible** — runs end-to-end in Google Colab  
- **Modular** — each workshop is self-contained  
- **Extensible** — builds toward more advanced systems (e.g., VLMs, edge AI)

Workshops typically follow this structure:

1. Setup environment  
2. Load and prepare data  
3. Run baseline model  
4. Apply optimization or alignment technique  
5. Evaluate results  
6. Measure performance (latency, throughput, etc.)

---

## Workshops

### LoRA Alignment Lab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DerrickJ1612/edge-ai-workshops/blob/main/workshops/lora-alignment/colab_model_alignment_lab.ipynb)

Fine-tune a language model using Low-Rank Adaptation (LoRA) for structured outputs and improved behavior.

- Covers dataset preparation, LoRA configuration, training, and evaluation  
- Demonstrates alignment via supervised fine-tuning  
- Includes performance and timing analysis  


**Source repo:**  
https://github.com/DerrickJ1612/model-alignment-lab

---

## Getting Started

The easiest way to run a workshop is through Google Colab.

1. Click the **Open in Colab** link for a workshop  
2. Run the setup cell at the top of the notebook  
3. Execute cells sequentially  

Each notebook automatically:
- Downloads required code  
- Installs dependencies  
- Sets up the environment  

No local setup required.

---

## Requirements

- Google account (for Colab)  
- Optional: GPU runtime (recommended for training workflows)

---

## Repository Structure

ai-workshops/
├── README.md
├── workshops/
│ └── model-alignment-lora/
│ ├── README.md
│ └── colab-model-alignment-lab.ipynb

