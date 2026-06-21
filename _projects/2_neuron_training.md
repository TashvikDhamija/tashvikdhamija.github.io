---
layout: page
title: Diffusion Training on AWS Trainium
description: Enabling SOTA diffusion and flow-matching model training on Trainium hardware — Stable Diffusion, FLUX, DiT, and Wan on the Neuron backend.
img:
importance: 2
category: industry
---

At [Amazon AWS Annapurna Labs](https://aws.amazon.com/machine-learning/trainium/) (Summer 2026), I worked on the Neuron Scalable Training team to onboard state-of-the-art generative models onto [AWS Trainium](https://aws.amazon.com/machine-learning/trainium/) — Amazon's purpose-built ML training accelerator.

**What I built:**
- Onboarded Stable Diffusion, FLUX, DiT, and Wan onto Neuron, Annapurna's native PyTorch backend for Trainium, enabling end-to-end diffusion and flow-matching training on custom silicon.
- Implemented and optimized PyTorch ATen operators for the Neuron backend, extending native operator coverage and improving execution efficiency.
- Designed and ran long-horizon training validation harnesses comparing Neuron and CUDA across text-to-image, text-to-video, and diffusion language model workloads — verifying numerical stability, convergence, and output quality parity.

This work directly expands the set of generative AI workloads accessible to AWS customers using Trainium hardware.
