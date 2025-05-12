# Sra2b – Single-Cell and Chimerism Analysis in Cardiac Tissue

**Team**: Sra²b  
**Project Title**: *Beyond the Pump: Identifying Neuron-Like Cells and Chimerism in Cardiac Tissue*

---

## 🧠 Overview

This project investigates two key biological questions:
1. Do **neuron-like cells** exist in the heart? (*analyzed in zebrafish and mouse*)
2. Do **donor and recipient cells coexist** after heart transplantation? (*analyzed in human*)

---

## 📁 Contents

| File | Description |
|------|-------------|
| `CB_Final_Sumaya_A.pdf` | Final written report |
| `zebrafish Analysis` | [📘 View Zebrafish Notebook in Google Colab](https://colab.research.google.com/drive/1bYgDab3UFBuOm7DzoKGG5qBpxg_frp-s?usp=sharing)
| `Mouse Analysis` | [📘 View Mouse Notebook in Google Colab](https://colab.research.google.com/drive/1EOi2KMNGHaix2zMHW0h09aNB4tr1S_4Q?usp=sharing)
|
| `Chimerism Analysis` | [📘 View Chimerism Notebook in Google Colab](https://colab.research.google.com/drive/1WF-IcuQmJxrfOtLZD6wnq-jfUmLarvfp?usp=sharing)
 |

---

## 🔬 Tools & Methods

- **scVI** for normalization, batch correction & latent space embedding
- **Cell Ranger** for 10x Genomics processing
- **Souporcell** for genotype-free clustering and chimerism analysis
- Visualization with **Scanpy**, **matplotlib**, and **seaborn**
- Executed via **Google Colab** and **VSCode** on Linux

---

## 🧪 Datasets

- 🐟 [Zebrafish Heart scRNA-seq (GSE261619)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE261619)  
- 🐭 [Mouse Heart snRNA-seq (10x Genomics)](https://www.10xgenomics.com/resources/datasets/5-k-mouse-heart-nuclei-1-standard-1-1-0)  
- 🧬 [Human Heart Transplant snRNA-seq (GSE203548)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE203548)

---
## 🔍 Key Findings

- Neuron-like gene expression was detected in zebrafish and mouse cardiac datasets, including genes linked to synaptic plasticity and neural function.
- Zebrafish showed broader expression of plasticity-associated markers, while the mouse dataset also revealed consistent neuron-like transcriptional patterns.
- Chimerism analysis of the human heart transplant sample confirmed the coexistence of donor- and recipient-derived cells, validated through genotype-free clustering and gene expression profiling.


---

## Citation

**Sumaya Abdulrahman (Sra²b)**  
Mohamed bin Zayed University of Artificial Intelligence (MBZUAI)

---

## License

MIT License *(or replace with the license you selected)*

---

