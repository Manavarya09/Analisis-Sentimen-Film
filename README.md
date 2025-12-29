# 🎬 Analisis Sentimen Film

<div align="center">

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](./LICENSE) 
[![Python: 3.10+](https://img.shields.io/badge/python-3.10%2B-blue.svg)]
[![Maintainer: Manavarya09](https://img.shields.io/badge/maintainer-Manavarya09-9cf.svg)](https://github.com/Manavarya09)
[![Docs](https://img.shields.io/badge/docs-README-brightgreen.svg)]
[![Issues](https://img.shields.io/github/issues/Manavarya09/analisis-sentimen-film)](https://github.com/Manavarya09/analisis-sentimen-film/issues)

</div>

---

## 📖 About

**Analisis Sentimen Film** is a reproducible repository for training and evaluating sentiment-analysis models on film reviews. It compares classical ML, deep learning, and transformer-based approaches (including LoRA/adapter methods) using standard datasets.

This repo is written in Indonesian and English for accessibility and includes notebooks, model results, and utilities to reproduce experiments.

---

## ✨ Highlights

- ✅ Support for multiple model families (Logistic Regression, CNN, LSTM, Transformer)
- ✅ Reproducible notebooks and saved model artifacts in `/Result`
- ✅ Clear training/evaluation scripts and hyperparameter examples
- ✅ Designed for quick experimentation on IMDB / local review datasets

---

## 📂 Repository layout

- `Notebooks/` — exploratory and reproducible Jupyter notebooks
- `Dataset Raw/` — raw data files and preprocessing notebooks
- `Models/` — model descriptions and checkpoints listing
- `Result/` — trained models, confusion matrices, word clouds, and evaluation outputs

---

## 🚀 Quick start

1. Clone the repo

```bash
git clone https://github.com/Manavarya09/analisis-sentimen-film.git
cd analisis-sentimen-film
```

2. Create a virtual environment and install dependencies (example):

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

> If `requirements.txt` is missing, install common packages:

```bash
pip install numpy pandas scikit-learn tensorflow torch transformers jupyterlab matplotlib seaborn
```

---

## 🧪 Usage

- Open `Notebooks/Scraping_Film_ML_C.ipynb` or `Dataset Raw/Raw_Data_Machine_Learning.ipynb` to explore data and preprocessing steps.
- Run training scripts or notebooks to reproduce results. Example training command (pseudo):

```bash
python train.py --model transformer --dataset imdb --epochs 3 --batch-size 16 --lr 2e-5
```

- Evaluation outputs (confusion matrices, accuracy, loss curves) are saved to `Result/`.

---

## 📊 Results & Models

Model performance and artifacts are inside `/Result`. See `Result/Comparison Results/` and `Result/Confusion Matrix/` for evaluation artifacts and visualizations.

---

## 🤝 Contributing

Contributions are welcome — open an issue or send a PR. Please include an explanation and a reproducible example for changes that affect models or data.

---

## 🧾 License

This project is licensed under the MIT License — see the `LICENSE` file for details.

**Copyright (c) 2025 Manavarya09**

---

## 📬 Contact

Maintainer: [Manavarya09](https://github.com/Manavarya09)

If you'd like custom badges, more examples, or integration with CI/CD (GitHub Actions), tell me which ones and I'll add them.

---

*Thank you for using Analisis Sentimen Film — contributions and feedback are appreciated!*# Analisis-Sentimen-Film
