
# Background Radiation and Inverse Source Tracking Algorithm (BaRISTA)

## Motivation

Achieving the required sensitivity in next-generation neutrinoless double-beta decay (0νββ) experiments (e.g., LEGEND, CUPID,..) depends on an accurate understanding of background distributions. Radioactiv decays can produce signals in the region of interest (ROI) of the energy spectrum, potentially mimicking 0νββ events.

## Introduction

This project introduces a novel approach to spectral decomposition and anomaly detection in rare-event physics experiments. The goal is to improve background modeling and signal extraction by leveraging machine learning-enhanced Bayesian inference.

### Key Concepts

Traditional background modeling approaches—used in 0νββ experiments share a common approach, a binned Likelihood Fit to Energy Spectrum:
- The observed energy spectrum is modeled as a Poisson-distributed sum of individual contributions.
- Contributions are derived from Monte Carlo simulated spectra, integrated over specific detector response functions.

### Bottlenecks/Challenges:
- High Computational Cost: Traditional Monte Carlo simulations require excessive resources.
- Source Degeneracy: Background contributions are difficult to disentangle.
- Blind to Anomalies: Standard fitting methods struggle with unexpected spectral features.

## 💡 Proposed Solution

![image](https://github.com/user-attachments/assets/c970322d-16cc-4b5a-8ece-f503e51f308b)

- Forward modeling
- Inverse mapping for background inference
Detection probability maps
- Anomaly detection for unexpected background sources

### 🛠 Implementation & Access

The core implementation is currently in a private repository.
- If you’re interested in collaborating or learning more, please reach out!
