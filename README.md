# 5mCBERT
DNA Methylation-Aware Language Model

## Overview

5mCBERT is a BERT-inspired model that integrates base identity and epigenetic state (methylation) to perform multiple predictive tasks:

- 🧠 Tissue classification  
- 📈 Gene expression prediction  
- 🧬 Per-base methylation state estimation

It takes as input a DNA sequence encoded with a 5-letter vocabulary: `{A, T, C, G, M}` where **M** represents methylated cytosine (5mC).

---

## Features

- **Custom embedding layer** for 5-token genomic vocabulary  
- **Sinusoidal positional encoding**  
- **Stacked Transformer encoder layers** with multi-head self-attention  
- **Multi-task heads** for classification, regression, and binary prediction  
- **Train/test split support** and interpretable loss breakdown

---

