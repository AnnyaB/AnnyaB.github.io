# Riya Basak

**World Models · Self-Supervised Predictive Representation Learning · Safe Sequential Decision-Making · Embodied AI**

[Academic Homepage](https://annyab.github.io/) · [CV](./assets/files/riya-basak-cv.pdf) · [GitHub](https://github.com/AnnyaB) · [LinkedIn](https://www.linkedin.com/in/riya-b-506346315/)

## Research

My research focuses on **world models for general, reliable intelligence**: learning structured latent state, transferable dynamics, causal structure, uncertainty, and action consequences so that agents can reason about how the world changes before acting.

I am particularly interested in four connected questions:

- **World Models & Transferable Dynamics** — how to separate persistent state, nuisance variation, and reusable mechanisms so learned dynamics transfer across changes in context, appearance, embodiment, and interaction horizon.
- **Self-Supervised Predictive Representation Learning** — how to learn representations that preserve structure and dynamics without depending on dense supervision or shortcut correlations.
- **Safe Sequential Decision-Making** — how model-based reasoning, uncertainty estimation, admissibility constraints, and counterfactual analysis can support safer action selection.
- **Embodied AI** — how learned world dynamics can support agents that anticipate physical and social consequences before acting.

## Selected Research

### Mitigating Shortcut Learning in Brain Tumour MRI Classification

Proposed **Pathology-Focused Disentanglement (PFD)** and **Guided Semantic Token Evolution (GSTE)** for shortcut-learning mitigation without segmentation masks in a ResNet50V2–RViT hybrid.

Across the fixed benchmark, models reached **98.52–99.22% test accuracy** and **98.49–99.20% macro-F1**. Attribution analysis revealed a stronger distinction than accuracy alone: reviewed **PFD–GSTE-B** predictions were tumour-focused in about **90%** of cases, compared with about **70%** for **PFD–GSTE-A**.

[Preprint](https://doi.org/10.5281/zenodo.21903347) · [Code](https://github.com/AnnyaB/HybridResNet50V2-RViT)

### LAADAN-AC: Admissibility-Aware Offline Reinforcement Learning

Developed **Lagrangian Admissibility-Aware Deep Action-Nudging Actor-Critic (LAADAN-AC)** for safer offline treatment-policy learning, combining hard admissibility masking, twin critics, conservative critic regularisation, expert-policy regularisation, smoothness shaping, and Lagrangian cost control.

Under the matched ICU-Sepsis benchmark protocol, LAADAN-AC achieved **0.7931 ± 0.0007 survival/return**, **0.0000 inadmissibility**, and **0.9525 expert-action match**, producing the strongest return–safety trade-off among the evaluated baselines.

[Code](https://github.com/AnnyaB/laadan-ac)

## Current Directions

### Same Rules, New Worlds

Developing a **mechanism-transport world model** for compositional and interventional generalisation. The central problem is transfer: predictive models can perform well in-distribution while failing when the same underlying dynamics appear under new contexts, appearances, embodiments, or longer interaction horizons.

The current direction separates **persistent latent state** from **transferable dynamics**, enforces consistency across nuisance shifts, and remains sensitive to genuine changes in the underlying causal mechanism.

### From World Models to Embodied Social Robots

Building a LeWM- and DreamerV3-based world-model research stack for agents that reason over predicted physical and social futures.

This work includes **KCON (Kinetic Counterfactual Oversight Nexus)**, a compact executive layer for comparing imagined action consequences, handling uncertainty and novelty, and supporting failure-aware action selection with minimal intervention.

## Academic Background

**BSc (Hons) Computer Science with Artificial Intelligence — First Class Honours**  
University of Hertfordshire, 2026  
Cumulative GPA: **4.38/4.50** · Level 6 GPA: **4.44/4.50**

