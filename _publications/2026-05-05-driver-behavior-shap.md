---
title: "Physiologically Grounded Driver Behavior Classification: SHAP-Driven Elite Feature Selection and Hybrid Gradient Boosting for Multimodal Physiological Signals"
collection: publications
category: manuscripts
permalink: /publication/2026-05-05-driver-behavior-shap
excerpt: 'This study introduces an interpretable ensemble framework using SHAP-based "Elite" feature selection and hybrid gradient boosting (XGBoost + LightGBM) to classify driving behaviors from multimodal physiological signals (EEG, EMG, GSR).'
date: 2026-05-05
venue: 'arXiv Preprint'
paperurl: 'https://arxiv.org/abs/2605.XXXXX'
---

## Abstract

This study proposes an interpretable and scalable framework for decoding driving behaviors from multimodal physiological signals. We utilize a large-scale dataset comprising synchronized EEG, EMG, and GSR signals, subjected to rigorous preprocessing including ICA-based artifact removal and multimodal synchronization. To address high dimensionality, we employ a SHAP-based "Elite" feature selection strategy, retaining the top 250 most influential features to reduce computational overhead by 50% while preserving predictive power. Final classification is performed using a weighted soft-voting ensemble of XGBoost and LightGBM models, optimized via Bayesian optimization (Optuna). Experimental results demonstrate that the proposed ensemble achieves a state-of-the-art accuracy of 80.91% and a macro-F1 score of 0.79 on the MPDB dataset, significantly outperforming single-modality baselines and traditional machine learning models. Comprehensive interpretability analysis using SHAP values validates the physiological plausibility of the model, highlighting the distinct contributions of EEG (cognitive load), EMG (motor execution), and GSR (arousal) to behavior classification.

## Key Contributions

*   **Robust Multimodal Pipeline:** Integration of 59-channel EEG, 4-channel EMG, and GSR with ICA-based artifact removal.
*   **Elite Feature Selection:** SHAP-based reduction of the feature space from 503 to 250 dimensions without loss of critical predictive information.
*   **Hybrid Ensemble Framework:** Optimized XGBoost and LightGBM ensemble achieving superior performance over existing deep learning benchmarks (MMPNet, MMPHGCN).
*   **XAI Validation:** Granular insights into physiological drivers, confirming the role of EEG Alpha/Theta ratios and EMG asymmetry in driving maneuvers.



## Cite This Research:


```bibtex
@article{golnari2026driverbehavior,
  title={Physiologically Grounded Driver Behavior Classification: SHAP-Driven Elite Feature Selection and Hybrid Gradient Boosting for Multimodal Physiological Signals},
  author={Akbari, Sahar and Mirza Ali Mohammadi, Mohammad Mahdi and Ensafdoust, Fatemeh and Golnari, Amin and Sanei, Saeid},
  journal={arXiv preprint arXiv:2605.XXXXX},
  year={2026}
}
