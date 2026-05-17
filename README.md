# Zero-Day Malware Detection — CNN–BiLSTM–Attention

This repository contains a Jupyter notebook (`Code/`) implementing a CNN–BiLSTM–Bahdanau Attention model for malware detection, along with a `Dataset.txt` file with the download link for the CIC-MalMem-2022 dataset. Run the notebook end-to-end in Google Colab (T4 GPU recommended) — the dataset downloads automatically via `kagglehub` and each stage saves a `.pkl` checkpoint so you can resume at any point. Dependencies: `Python 3.12`, `TensorFlow 2.19`, `scikit-learn`, `SHAP 0.45+`, `kagglehub`.
