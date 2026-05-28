---
title: "“QuantumIrrigation” – a new quantum computing python package for irrigation demand assessment"
type: Publication
authors: Adarsha Neupane and Vidya Samadi
venue: Smart Agricultural Technology, 2025
year: 2025
image: /assets/images/publications/QuantumIrrigation.png
summary: Quantum computing package for irrigation demand assessment.
paper_url: https://www.sciencedirect.com/science/article/pii/S2772375525007543
code_url: https://github.com/Clemson-Hydroinformatics-Lab/QuantumIrrigation
layout: publication
---

## Abstract

Accurate estimation of irrigation demand is a cornerstone of precision agriculture, typically achieved through modeling crop reference evapotranspiration (ETo) and soil moisture dynamics. In this study, we developed QuantumIrrigation—a novel Python package that integrates quantum computing with deep learning to predict ETo and soil moisture (expressed as soil water tension). The framework was tested using data from an experimental research farm in Camilla, Georgia. QuantumIrrigation’s performance was benchmarked against two state-of-the-art deep learning architectures widely used for time-series prediction: Long Short-Term Memory (LSTM) and the Patch Time-Series Transformer (PatchTST). The package incorporates two quantum models—Variational Quantum Circuit (VQC) and Quantum LSTM (QLSTM)—which were evaluated both as standalone models and within four hybrid configurations: hybrid LSTM–VQC, hybrid LSTM–QLSTM, hybrid PatchTST–VQC, and hybrid PatchTST–QLSTM. For ETo prediction, LSTM and QLSTM achieved the strongest performance across all evaluation metrics, while the hybrid variants offered no additional gains in predictive accuracy. In contrast, LSTM-based hybrid quantum models outperformed all other configurations for soil water tension prediction, effectively combining LSTM’s temporal memory with quantum properties of superposition and entanglement. These hybrids delivered superior predictive accuracy and greater computational efficiency compared to both standalone quantum and other hybrid models. Sensitivity analysis identified solar radiation as the most influential variable for ETo prediction and lagged soil water tension values as the dominant predictors for soil moisture dynamics. Overall, the results highlight the domain-specific advantages of quantum–classical hybrid modeling and demonstrate the potential of the QuantumIrrigation package to advance irrigation demand forecasting and support more efficient, data-driven irrigation decision making.

<!-- ## Key contributions

- Contribution 1
- Contribution 2
- Contribution 3 -->

## BibTeX

```bibtex
@article{neupane2025quantumirrigation,
  title = {QuantumIrrigation: A New Quantum Computing Python Package for Irrigation Demand Assessment},
  author = {Neupane, Adarsha and Samadi, Vidya},
  journal = {Smart Agricultural Technology},
  pages = {101523},
  year = {2025},
  publisher = {Elsevier},
}
```