# Enhancing molecular property prediction with quantized GNN models

## 📌 Summary
This paper integrates DoReFa-Net quantization with GNNs to improve computational and storage efficiency in molecular property prediction. Results show that GCN models maintain comparable performance up to INT8 quantization, while GIN models are less robust. However, 4-bit and 2-bit quantization significantly degrade performance. Overall, INT8 quantization offers a good balance between computational efficiency and predictive accuracy.

### 🎯 Goal:
To develop lightweight and computationally efficient GNN models through quantization while maintaining reliable molecular property prediction performance.

---

<div align="center">
  <img src="./Figures/a_2.png.jpg" width="600">
</div>

---


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
