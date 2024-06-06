# Tiara: Deep Learning-based Classification System for Eukaryotic Sequences

**Tiara** is a deep-learning-based approach for the identification of eukaryotic sequences in metagenomic data, powered by PyTorch.

## Introduction

Tiara is designed to address the challenges of eukaryotic metagenomics, which has become increasingly important with the growing availability of metagenomic datasets. Proper classification of eukaryotic nuclear and organellar genomes is essential for understanding eukaryotic diversity. Tiara leverages deep learning to accurately classify sequences in a two-stage process:

1. **First Stage**: Sequences are initially classified into broad categories: archaea, bacteria, prokarya, eukarya, organelle, and unknown.
2. **Second Stage**: Sequences labeled as organelle in the first stage are further classified into mitochondria, plastid, or unknown.

Tiara has been shown to perform similarly to EukRep for prokaryote classification and outperforms it for eukaryote classification, offering faster computation times. It is the only tool available that correctly classifies organellar sequences, enabling the recovery of nearly complete plastid and mitochondrial genomes from both test and real metagenomic data.

For detailed information, please refer to the manuscript: Karlicki, M., Antonowicz, S., & Karnkowska, A. (2022). Tiara: deep learning-based classification system for eukaryotic sequences. *Bioinformatics*, 38(2), 344–350. [https://doi.org/10.1093/bioinformatics/btab672](https://doi.org/10.1093/bioinformatics/btab672).

