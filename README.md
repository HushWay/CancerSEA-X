# 🔬 CancerSEA-X & CancerSEA
> **A Comprehensive Single-cell Resource for Tumor Microenvironment (TME) Cell States**

[![Website](https://img.shields.io/badge/Website-Access_CancerSEA--X-007EC6?style=for-the-badge&logo=google-chrome&logoColor=white)](https://biocc.hrbmu.edu.cn/CancerSEA-X/)
[![Publication](https://img.shields.io/badge/Publication-GPB_(2026)-E51B24?style=for-the-badge&logo=elsevier&logoColor=white)](#-citation)
[![Publication](https://img.shields.io/badge/Publication-NAR_(2019)-005A9C?style=for-the-badge&logo=oxford-university-press&logoColor=white)](#-citation)

Welcome to the architectural repository for **CancerSEA-X** and its predecessor, **CancerSEA**. 

**CancerSEA (2019)** was the first landmark cancer single-cell functional state atlas. Building upon this foundation, **CancerSEA-X (2026)** is a massive, comprehensive upgrade dedicated to systematically characterizing distinct cell states across malignant, immune, and stromal cells within the pan-cancer tumor microenvironment (TME).

🌐 **Official Database Access:** [https://biocc.hrbmu.edu.cn/CancerSEA-X/](https://biocc.hrbmu.edu.cn/CancerSEA-X/)

---

## 📊 Database Statistics (CancerSEA-X)
To comprehensively decode the TME, CancerSEA-X integrates massive-scale single-cell RNA-seq datasets, achieving unprecedented resolution and scale:

| Metric | Count | Breakdown of the 156 Cell States |
| :--- | :--- | :--- |
| **Single Cells** | `9,608,163` | 🦠 **25** Cancer cell states |
| **Datasets** | `239` | 🛡️ **52** T cell states \| **19** B cell states |
| **Cancer Types** | `32` | 🩸 **3** Monocyte states \| **16** Macrophage states |
| **Cell States** | `156` | 🧬 **15** Dendritic cell states |
| | | 🧱 **12** CAF states \| **14** Endothelial cell states |

---

## ✨ Core Features & Analytical Modules

### 1. 🔍 TME Cell State Exploration
- Covers a comprehensive catalog of 25 cancer cell states, 105 immune cell states, and 26 stromal cell states.
- Enables one-stop query and direct downloading of state-specific signature genes and functional activity spectrums.

### 2. 🔄 Bidirectional State-Gene Search
- **State-to-Gene:** Select a specific cell state to obtain a robust list of genes significantly correlated with that state within a specific cancer type.
- **Gene-to-State:** Input any gene of interest to retrieve its significantly correlated cell states across cancer types, complete with detailed statistical correlations.

### 3. 🕸️ Cross-cell-type State-Gene Network
- Visually and interactively explores the complex functional associations between cell states and genes.
- Supports dynamic interactive exploration to pinpoint key hub genes and critical cell states driving the TME ecosystem.

---

## 📸 Platform Preview

<img src="https://biocc.hrbmu.edu.cn/CancerSEA-X/images/help/help1.png" width="800">

---

## 💻 About the Architecture
*Note: This repository serves as a structural demonstration of the web application. Due to laboratory data privacy policies and the massive size of the raw single-cell count matrices, the backend database and core source code are maintained internally.*

The CancerSEA-X platform is powered by a robust full-stack architecture designed to handle high-concurrency data retrieval for over 9.6 million cells:
- **Frontend / Visualization:** webpack, D3.js, ECharts, HTML5/CSS3, Bootstrap
- **Backend / Logic:** Java, MySQL

---

## 📖 Citation and Contact

If you find our resource helpful in your research, please cite our publications:

1. **CancerSEA-X:**
   > *CancerSEA-X: A Single-cell Resource for Tumor Microenvironment Cell States Across over 30 Cancer Types.*
   > **Genomics, Proteomics & Bioinformatics**, 2026.
2. **CancerSEA:**
   > Yuan H, Yan M, Zhang G, Liu W, et al. *CancerSEA: a cancer single-cell state atlas.*
   > **Nucleic Acids Research**, 2019.

---
© 2025 College of Bioinformatics Science and Technology, Harbin Medical University.
