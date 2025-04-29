# Reproducing GPT-2 (124M) from Scratch

This repo contains the implementation of the GPT-2 (124M parameters) model, reproduced from scratch using the insights from *Attention is All You Need*, GPT-2, and GPT-3 papers. The model is trained with optimizations for better performance, including Flash Attention, Torch Compile, and multi-GPU support via Distributed Data Parallel (DDP).

## Key Features:
- **Reproduction of GPT-2 architecture (124M parameters)** based on the original research papers.
- **Optimized training** with Flash Attention, Torch Compile, and gradient accumulation for faster convergence.
- **Multi-GPU training** using DDP to scale training across multiple devices.
- **Model evaluation** on the HellaSwag dataset for reasoning and language understanding benchmarking.



