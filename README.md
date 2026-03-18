
# Latent Influence Network (LIN) and LIDET Framework

This repository contains the implementation of the **Latent Influence Network (LIN)** and the **Latent Influence Detection Framework (LIDET)**, introduced in our ICWSM 2025 paper.

## 📘 Paper Title
**LIN: Latent Influence Network for Discovering Hidden Directed Influence Links on Social Media**  

## 🔍 Overview

This project proposes a novel method for uncovering latent influence in social networks:

- **LIN (Latent Influence Network)**: A network structure inferred from social activity patterns to represent hidden influence links.
- **LIDET (Latent Influence Detection Framework)**: A systematic evaluation and optimization framework for influence modeling, using user behavior prediction tasks.

## 🗂 Directory Structure

```
├── Covid_result_example/     # Output examples on COVID-19 dataset
├── Data_example/             # Sample datasets and ID-based examples
├── ipynb/                    # Jupyter notebooks demonstrating LIN/LIDET
├── LIN_example/              # Core LIN model implementation and demos
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```


## 📊 Datasets

Due to Twitter's data sharing policies, only sample data are included in `Data_example/`. You may need to rehydrate them using tools like `twarc`.

## 📓 Notebooks

All core implementation examples, evaluations, and visualizations are provided in the `ipynb/` directory. These include:
- Influence network construction
- Parameter selection for LIDET
- Classification evaluation

Currently, the notebooks cover preprocessing and modeling for the Twitter15 and Twitter16 datasets. Additional notebooks (e.g., for COVID-19 ) are still being organized and will be added soon.

## 📈 Key Features

- Automatically identifies hidden influence structures.
- Achieves **99% classification accuracy** on COVID-19 Twitter data.
- Generalizes across multiple real-world datasets.

## ⚙️ Dependencies

Install required packages using:

```bash
pip install -r requirements.txt
```

## 📬 Contact

For questions or collaborations, please contact:  
**Chenhao Gu** – [chenhao.gu1@unimelb.edu.au](mailto:chenhao.gu@unimelb.edu.au)
