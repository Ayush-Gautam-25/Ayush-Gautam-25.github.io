---
layout: page
title: LoRA vs QLoRA
---

# LoRA vs QLoRA vs Full Finetuning

> Comparing three approaches to finetuning LLMs in terms of memory, speed, and performance.

## Why This Matters

Full finetuning of LLMs is compute-heavy and inaccessible. This blog shows how parameter-efficient finetuning methods like LoRA and QLoRA can drastically reduce GPU/memory cost.

## Results

| Method | Memory (GB) | Time/Epoch | Accuracy | Checkpoint Size |
|--------|-------------|------------|----------|-----------------|
| Full   | 30GB        | Slow       | High     | 13GB            |
| LoRA   | 16GB        | Medium     | Mid      | ~150MB          |
| QLoRA  | 12GB        | Fast       | Mid-High | ~70MB           |

## Code

🔗 [← Back to Home](../index.html)
