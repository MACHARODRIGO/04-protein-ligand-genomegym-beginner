# 🥩 Protein-Ligand Analysis 🧬

## 📌 Brief Description
This repository contains introductory examples of **protein and ligand analysis in Python**.  
- **Gemmi** is used to load and explore protein structures in PDB (Protein Data Bank) format.  
- **RDKit** is used to represent ligands from **SMILES notation** and compute basic chemical properties.  

These examples demonstrate how to access fundamental structural information without requiring 3D graphical visualization tools.

---

## 🎯 Learning Objectives
- Load a protein structure in PDB format using Gemmi.  
- Iterate over chains and residues to explore protein content.  
- Represent small molecules with RDKit from SMILES strings.  
- Calculate basic properties such as molecular formula and molecular weight.  

---

## 📌 Why it matters
Understanding how to **read and manipulate proteins and ligands in silico** is essential for:  
- Analyzing protein–ligand interactions.  
- Designing experiments in structural biology and computational chemistry.  
- Integrating structural data into bioinformatics or drug discovery pipelines.  

---

## ⚙️ Prerequisites
- Python 3.9+  
- [Gemmi](https://gemmi.readthedocs.io/)  
- [RDKit](https://www.rdkit.org/)  

Recommended installation with `conda`:
```bash
conda create -n protein-beginner python=3.9
conda activate protein-beginner
conda install -c conda-forge gemmi rdkit
```

---

## 🚀 Usage

You can explore this challenge directly in Jupyter Notebook.

- **Option 1: Google Colab (recommended for beginners)**  
 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MACHARODRIGO/04-protein-ligand-genomegym-beginner/blob/main/protein_ligand_beginner.ipynb)

- **Option 2: Local Jupyter**  
  Clone this repo and open the notebook manually:
  ```bash
  git clone https://github.com/MACHARODRIGO/04-protein-ligand-genomegym-beginner.git
  cd 04-protein-ligand-genomegym-beginner
  jupyter notebook protein_ligand_beginner.ipynb

