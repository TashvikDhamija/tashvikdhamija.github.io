---
layout: page
title: Causal Interpretability in Robot Learning
description: Framework for identifying which physical priors govern distinct stages of manipulation task execution in imitation learning policies.
img:
importance: 5
category: research
related_publications: true
---

This project introduces a **causal interpretability framework** for understanding imitation learning (IL) policies — specifically, which physics properties (mass, friction, geometry, etc.) are causally responsible for distinct stages of a robot manipulation task.

**The problem:** Modern IL policies are often opaque: they learn from demonstrations and generalize well, but it's unclear *why* they succeed or fail, and which physical properties of the environment they rely on at each decision point.

**Our approach:**
- Designed a removal-based causal analysis method (inspired by feature attribution but applied to physical simulation parameters) to isolate which priors are load-bearing at each stage of task execution.
- Formalized a stage decomposition of manipulation trajectories and assigned causal responsibility scores to physical properties per stage.
- Results reveal interpretable structure in IL policies that can inform sim-to-real transfer, failure diagnosis, and policy debugging.

Submitted to [CoRL 2025](https://www.corl.org/) (Conference on Robot Learning).
