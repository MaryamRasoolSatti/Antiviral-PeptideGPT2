# Antiviral-PeptideGPT2

This repository provides the implementation of **Antiviral-PeptideGPT2**, a prompt-based fine-tuning framework using **ProtGPT2** for antiviral peptide identification.

The model is designed to classify peptide sequences as either:

- Antiviral
- Non-antiviral

This repository includes dataset preparation files and four different prompt-based model training scripts for antiviral peptide prediction.

---

## Overview

Antiviral peptides are short amino acid sequences that may inhibit viral infection or viral replication. This project uses a pretrained protein language model, **ProtGPT2**, to learn sequence patterns associated with antiviral activity.

The workflow includes:

1. Preparing antiviral and non-antiviral peptide datasets
2. Converting peptide sequences into prompt-based input formats
3. Fine-tuning ProtGPT2 using different prompt designs
4. Predicting antiviral activity using likelihood-based scoring
5. Evaluating model performance using classification metrics


## Repository Structure

```text
Antiviral-PeptideGPT2/
│
├── Dataset/
│   ├── antiviral.csv
│
├── Model training/
│   ├── Prompt_1.py
│   ├── Prompt_2.py
│   ├── Prompt_3.py
│   └── Prompt_4.py
│
└── README.md

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/MaryamRasoolSatti/Antiviral-PeptideGPT2.git
cd Antiviral-PeptideGPT2

