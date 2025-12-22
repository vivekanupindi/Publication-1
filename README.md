# Publication-1
Publication - Comparative Evaluation of Logistic Regression for ICD-10 Code Classification Using the CodiEsp Clinical Text Dataset

Comparative Evaluation of Logistic Regression for 
ICD-10 Code Classification Using the CodiEsp 
Clinical Text Dataset 
 
Vivek Anupindi 
Independent Researcher 
 
Abstract: Automatic assignment of ICD-10 diagnostic codes from free-text clinical narratives is a central task in modern 
healthcare analytics. While recent literature has focused heavily on deep learning and large language models (LLMs), classical 
machine learning methods remain essential for building transparent and reproducible baselines, especially when data quality 
issues exist. This paper presents a research-grade baseline study using Logistic Regression for ICD-10 classification of Spanish 
clinical text from the CodiEsp dataset. We describe a complete end-to-end pipeline including dataset inspection, text 
preprocessing, TF–IDF feature extraction, one-vs-rest Logistic Regression modeling, and result analysis. Particular attention is 
given to practical challenges such as misaligned identifiers, missing text files, and multi-label imbalance. Experimental results 
on a cleaned subset of the data show that Logistic Regression can provide interpretable decision boundaries and reasonable 
macro-F1, but performance is constrained by dataset structure and label sparsity. We conclude by outlining a path toward 
transformer-based and LLM-enhanced architectures that build directly on this baseline pipeline.
