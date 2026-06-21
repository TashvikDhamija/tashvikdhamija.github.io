---
layout: page
title: Amazon ML Challenge — 2nd Place
description: Nationwide ML competition (~5000 teams) — ensemble of fine-tuned BERT & RoBERTa with clustering-based quantization for product dimension prediction.
img:
importance: 4
category: competition
---

**Amazon ML Challenge** is a nationwide machine learning competition hosted by Amazon India, drawing approximately 5,000 teams. Our team, **Team Fishes**, secured **2nd place** on the leaderboard.

**Problem:** Predict physical product dimensions (height, width, depth, weight) from product listings — text descriptions, titles, and metadata — at scale.

**Approach:**
- Fine-tuned **BERT** and **RoBERTa** models on the product listing domain to extract structured dimension information from unstructured text.
- Designed an **ensemble** combining multiple fine-tuned model variants with learned aggregation weights, improving robustness across product categories.
- Applied **clustering-based quantization** to group products by category and domain-shift characteristics, allowing per-cluster model specialization and improving tail-category accuracy.

The solution demonstrated that strong NLP ensembles with domain-aware quantization can outperform single-model approaches on large-scale e-commerce extraction tasks.
