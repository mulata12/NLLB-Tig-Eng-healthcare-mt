
# Domain-Adaptive NLLB for English–Tigrigna Healthcare Translation

## Overview
This project investigates domain-adaptive fine-tuning of Meta's NLLB model
for high-stakes healthcare translation between English and Tigrigna.

## Methods
- Baseline NLLB evaluation
- LoRA parameter-efficient fine-tuning
- Back-translation for data augmentation
- Automatic metrics: BLEU, chrF++, TER, COMET
- Human evaluation: MQM framework

## Model
facebook/nllb-200-distilled-600M

## Dataset
- 1000 curated EN–TI healthcare sentence pairs
- English monolingual medical corpus

## Project Structure
See repository folders for data, training scripts, and evaluation results.
