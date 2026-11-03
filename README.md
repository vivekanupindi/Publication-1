# Comparative Evaluation of Logistic Regression for ICD-10 Code Classification

### Using the CodiEsp Spanish Clinical Text Dataset

An interpretable baseline study of assigning ICD-10 codes to Spanish clinical narratives with TF–IDF features and one-vs-rest Logistic Regression.

[**Read the paper (PDF)**](./Publication%201.pdf) · [**View the published article**](https://doi.org/10.22214/ijraset.2025.76293)

---

## Study at a glance

| | |
|---|---|
| **Task** | Multi-label ICD-10 classification |
| **Text** | Spanish clinical narratives |
| **Dataset** | CodiEsp |
| **Baseline** | TF–IDF + one-vs-rest Logistic Regression |
| **Evaluation focus** | Macro-averaged precision, recall, and F1 |

## Why this baseline

Clinical coding from free text is a demanding classification problem: one narrative may map to several diagnostic codes, and the code distribution is highly imbalanced. This study uses a transparent, comparatively lightweight model to establish a reference point before moving to more complex approaches.

The paper also discusses data-quality issues that can shape results, including inconsistent identifiers, missing text files, and sparse labels.

## Pipeline

1. **Inspect and align** the dataset records, text files, and code labels.
2. **Prepare the text** with normalization and tokenization.
3. **Extract features** using term frequency–inverse document frequency (TF–IDF).
4. **Train the baseline** with one-vs-rest Logistic Regression.
5. **Evaluate** with macro-averaged metrics to account for label imbalance.

## Main takeaway

The linear baseline offers an interpretable starting point, but its performance is constrained by dataset structure, rare labels, and the limited context captured by a bag-of-words representation. The study positions this work as a foundation for future comparisons with transformer-based models and other language-model approaches.

> This is a research baseline, not a clinically validated or deployed coding system.

## Publication

**Author:** Vivek Anupindi  
**Journal:** *International Journal for Research in Applied Science & Engineering Technology (IJRASET)*  
**Issue:** Volume 13, Issue XII, December 2025  
**DOI:** [10.22214/ijraset.2025.76293](https://doi.org/10.22214/ijraset.2025.76293)

### Citation

```bibtex
@article{anupindi2025logistic,
  author  = {Anupindi, Vivek},
  title   = {Comparative Evaluation of Logistic Regression for ICD-10 Code Classification Using the CodiEsp Clinical Text Dataset},
  journal = {International Journal for Research in Applied Science \\& Engineering Technology},
  volume  = {13},
  number  = {XII},
  year    = {2025},
  doi     = {10.22214/ijraset.2025.76293}
}
```

## Repository contents

This repository contains the paper PDF. It does not include the CodiEsp dataset or implementation scripts.
