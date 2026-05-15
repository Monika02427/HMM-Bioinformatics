# HMM-Bioinformatics

Hidden Markov Models (HMMs) for biological sequence analysis and gene prediction.

---

## Project Overview

This repository implements a Hidden Markov Model (HMM) for computational biology applications using Python. The project focuses on predicting hidden biological states such as exon and intron regions from DNA sequences using the Viterbi Algorithm.

The implementation demonstrates how probabilistic models and dynamic programming can be applied to genomic sequence analysis.

---

## Biological Background

Genes in DNA contain different functional regions:

- **Exons (E)** → coding regions
- **Introns (I)** → non-coding regions
- **5' Splice Sites (5)** → exon-intron boundary regions

The Hidden Markov Model predicts these hidden biological states from observed nucleotide sequences.

---

## Algorithms Implemented

### Hidden Markov Model (HMM)
A probabilistic model used to describe systems with hidden states.

### Viterbi Algorithm
A dynamic programming algorithm used to determine the most probable sequence of hidden states for a given DNA sequence.

### Dynamic Programming
Used to efficiently compute optimal hidden-state paths.

---

## Features

- HMM state representation
- Transition probability matrix
- Emission probability matrix
- Viterbi decoding algorithm
- Traceback implementation
- DNA sequence analysis
- Hidden-state prediction
- Visualization of predicted states

---

## Repository Structure

```text
HMM-Bioinformatics/
│
├── notebooks/
│   └── hmm_gene_prediction.ipynb
│
├── src/
│   └── viterbi.py
│
├── data/
│
├── results/
│
├── figures/
│
├── requirements.txt
│
└── README.md
