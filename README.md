# Memorizing Transformers: Implementation

## Introduction
This repository implements the Memorizing Transformers architecture from [Memorizing Transformers (Wu et al., 2022)](https://arxiv.org/pdf/2203.08913). The model extends traditional transformers with a kNN-based memory retrieval mechanism, enabling the use of external memory for processing long-context data. This implementation leverages FAISS (Facebook AI Similarity Search) for efficient approximate nearest-neighbor searches, ensuring scalability even with large memory sizes.


## Key Specifications

Frameworks: PyTorch, FAISS

GPU: NVIDIA T4 GPU

Sequence Length: Supports sequences up to 5120 tokens

Memory Size: Configurable memory sizes up to 81,920 tokens

Datasets: Optimized for datasets like arXiv Math


## Features 

kNN-Augmented Attention: Implements kNN-based memory retrieval to handle long-range dependencies efficiently.

Transformer-XL Recurrence: Integrates recurrence mechanisms to extend context length without increasing computational complexity.

T5 Positional Encodings: Adapts T5's relative positional encodings for better performance on long-context tasks.

Efficient Memory Management: Supports external memory sizes up to 81,920 tokens for large datasets.



<p align="center"><img width="477" alt="Screenshot 2025-01-08 at 8 40 37 PM" src="https://github.com/user-attachments/assets/c42016d9-3d58-41e2-9b27-5021d335cfff" />

