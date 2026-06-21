---
layout: page
title: Industrial Anomaly Detection
description: Real-time one-shot anomaly detection on manufacturing lines — >99% accuracy with <1% false positives, deployed on edge hardware.
img:
importance: 3
category: industry
---

At [SwitchOn](https://www.switchon.earth/) (Summer 2023), I engineered a production computer vision system for automated quality control on manufacturing lines.

**System design:**
- Built real-time **one-shot anomaly detection** pipelines using embedding similarity in memory-bank architectures, enabling defect detection with only a handful of reference images at setup time.
- Integrated a **transformer-based OCR module** into the anomaly detection stack for reading product labels, lot numbers, and markings directly within the same inference pipeline.
- Achieved **>99% accuracy with <1% false positives** across diverse product categories on active manufacturing lines.
- Performed remote rollout and on-device validation of quantized models on Linux embedded hardware, ensuring robust edge inference under production constraints.

The system replaced manual visual inspection at scale, reducing defect escape rates while maintaining throughput on high-speed lines.
