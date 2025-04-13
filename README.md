
# Latent Influence Network (LIN) and LIDET Framework

This repository contains the implementation of the **Latent Influence Network (LIN)** and the **Latent Influence Detection Framework (LIDET)**, introduced in our AAAI 2025 paper.

## 📘 Paper Title
**Latent Influence Network: Uncovering Hidden Influence Pathways in Social Media**  
Chenhao Gu, Zainab Zaidi, Shanika Karunasekera, Ling Luo

## 🔍 Overview

This project proposes a novel method for uncovering latent influence in social networks:

- **LIN (Latent Influence Network)**: A network structure inferred from social activity patterns to represent hidden influence links.
- **LIDET (Latent Influence Detection Framework)**: A systematic evaluation and optimization framework for influence modeling, using user behavior prediction tasks.

## 🗂 Directory Structure

```
├── data/                  # Dataset files or download scripts
├── src/                   # Core LIN and LIDET implementations
├── experiments/           # Experiment configurations and runners
├── results/               # Outputs, metrics, and model evaluations
├── figures/               # Plots and visualizations
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

## 🚀 Quick Start

1. **Install dependencies:**

```bash
pip install -r requirements.txt
```

2. **Run an experiment:**

```bash
python src/run_lidet.py --dataset covid19 --output results/covid19/
```

> Modify configurations in `src/config.py` as needed.

## 📊 Datasets

The framework supports multiple datasets. Instructions for obtaining and preprocessing them are provided in `data/README.md`.

## 📈 Key Features

- Automatically identifies hidden influence structures.
- Achieves **99% classification accuracy** on COVID-19 Twitter data.
- Generalizes across multiple real-world datasets.

## 📄 Citation

```bibtex
@inproceedings{gu2025latent,
  title={Latent Influence Network: Uncovering Hidden Influence Pathways in Social Media},
  author={Gu, Chenhao and Zaidi, Zainab and Karunasekera, Shanika and Luo, Ling},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  year={2025}
}
```

## 🔗 Links

- [Paper (coming soon)](https://arxiv.org/abs/...)
- [Project Website](https://gudan.me/lin-lidet)

## 📬 Contact

For questions or collaborations, please contact:  
**Chenhao Gu** – [chenhao.gu@student.unimelb.edu.au](mailto:chenhao.gu@student.unimelb.edu.au)
