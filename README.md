# Parallel Corpora Synthesis and Analysis with Large Language Models

## Abstract
This study explores the use of Large Language Models (LLMs) to generate and fine-tune parallel corpora, focusing on translation performance. Leveraging Mistral-7B for English text generation and T5-base for translation to German, the research compares three models — T5-base, T5-base fine-tuned on Opus-books collection, and T5-base fine-tuned on synthetic data — on the Flores dataset using SacreBLEU scores.

The findings reveal that while T5-base Opus-books initially performed better, it ultimately achieved a lower SacreBLEU score than the original T5-base. On the other hand, T5-base Synthetic consistently outperformed both models during training, showcasing the promising role of synthetic data in advancing LLM training practices.

## Dataset
[Synthetic Parallel Corpora](https://huggingface.co/datasets/jaymanvirk/synthetic_parallel_corpora)

## Paper
[Parallel Corpora Synthesis and Analysis with Large Language Models](parallel_corpora_synthesis_analysis_llm.pdf)
