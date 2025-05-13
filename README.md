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
| `BeyondThePump_Report.pdf` | Final written report |
| `zebrafish Analysis` | [📘 View Zebrafish Notebook in Google Colab](https://colab.research.google.com/drive/1bYgDab3UFBuOm7DzoKGG5qBpxg_frp-s?usp=sharing)
| `Mouse Analysis` | [📘 View Mouse Heart snRNA-seq Notebook in Google Colab](https://colab.research.google.com/drive/1EOi2KMNGHaix2zMHW0h09aNB4tr1S_4Q?usp=sharing)
| `Chimerism Analysis` | [📘 View Chimerism Notebook in Google Colab](https://colab.research.google.com/drive/1WF-IcuQmJxrfOtLZD6wnq-jfUmLarvfp?usp=sharing)
 

---

## 🔬 Tools & Methods

- **Cell Ranger** for 10x Genomics processing
- **Souporcell** for genotype-free clustering and chimerism analysis
- **scVI** for normalization, batch correction & latent space embedding
- Visualization with **Scanpy**, **matplotlib**, and **seaborn**
- Executed via **Google Colab** and **VSCode** on Linux

---

## 🧪 Datasets

- 🐟 [Zebrafish Heart scRNA-seq (GSE261619)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE261619)  
- 🐭 [5k Adult Mouse Heart Nuclei – 10x Genomics](https://www.10xgenomics.com/datasets/5k-adult-mouse-heart-nuclei-isolated-with-chromium-nuclei-isolation-kit-3-1-standard)
- 🧬 [Human Heart Transplant snRNA-seq (GSE203548)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE203548)

---
## 🔍 Key Findings

- Neuron-like gene expression was detected in zebrafish and mouse cardiac datasets, including genes linked to synaptic plasticity.
- Zebrafish showed broader expression of plasticity-associated markers, while the mouse dataset also revealed consistent neuron-like transcriptional patterns.
- Chimerism analysis of the human heart transplant sample confirmed the coexistence of donor- and recipient-derived cells, validated through genotype-free clustering.


---

## Citation

**Sumaya Abdulrahman (Sra²b)**  
Mohamed bin Zayed University of Artificial Intelligence (MBZUAI)  
sumaya.alameri@mbzuai.ac.ae 


---

## License

MIT License *(or replace with the license you selected)*

---

