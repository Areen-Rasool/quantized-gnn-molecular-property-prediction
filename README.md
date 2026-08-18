# Enhancing Molecular Property Prediction with Quantized GNN Models

[![Paper](https://img.shields.io/badge/Paper-Journal%20of%20Cheminformatics-blue?style=for-the-badge)](https://doi.org/10.1186/s13321-025-00989-3)
[![DOI](https://img.shields.io/badge/DOI-10.1186%2Fs13321--025--00989--3-green?style=for-the-badge)](https://doi.org/10.1186/s13321-025-00989-3)

## 📌 Overview

This repository contains the implementation associated with our work on **quantized Graph Neural Networks (GNNs) for molecular property prediction**. The study integrates the **DoReFa-Net quantization algorithm** with GNN models to reduce computational and storage requirements while maintaining predictive performance.

The proposed approach is evaluated on molecular property prediction tasks using **MoleculeNet benchmark datasets** and different quantization levels, including FP16, INT8, INT4, and INT2.

### 🎯 Goal

To develop lightweight and computationally efficient GNN models through quantization while maintaining reliable molecular property prediction performance.

---

<div align="center">
  <img src="./Figures/a_2.png.jpg" width="600">
</div>

---

## 🧠 Methodology

The proposed framework combines **Graph Neural Networks (GNNs)** with **DoReFa-Net quantization** to investigate the trade-off between predictive performance and computational efficiency.

The study evaluates:

- **GCN (Graph Convolutional Network)**
- **GIN (Graph Isomorphism Network)**
- **DoReFa-Net quantization**
- Multiple numerical precision levels
- Molecular property prediction benchmarks

### Overall Workflow

```text
Molecular Graph
      ↓
Graph Neural Network
      ↓
DoReFa-Net Quantization
      ↓
Quantized GNN Model
      ↓
Molecular Property Prediction
      ↓
Performance Evaluation

## ⚙️ Installation & Setup

###  💻 Google Colab (Recommended)

```bash
!pip install torch_geometric
!pip install rdkit
```

### Train/test quant_molecular_networks:
  
 Run train.py using
```bash
  `python train.py`  
```
## 📊 Datasets

🌐 Public dataset used in this work: https://moleculenet.org/datasets-1 

## 📄 Published Paper

<p align="center"> <a href="https://doi.org/10.1186/s13321-025-00989-3"> <img src="https://img.shields.io/badge/Read%20Published%20Paper-Journal%20of%20Cheminformatics-blue?style=for-the-badge"> </a> </p>

DOI:
https://doi.org/10.1186/s13321-025-00989-3

## 📚 Citation

If you use this work in your research, please cite:

```bibtex
@article{rasool2025enhancing,
  title={Enhancing molecular property prediction with quantized GNN models},
  author={Rasool, Areen and Ul Rahman, Jamshaid and Uwitije, Rongin},
  journal={Journal of Cheminformatics},
  volume={17},
  number={1},
  pages={81},
  year={2025},
  doi={10.1186/s13321-025-00989-3}
}

```
