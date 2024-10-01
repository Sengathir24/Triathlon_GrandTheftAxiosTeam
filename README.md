# 🧬 Mechanisms of Action (MoA) Prediction

This project focuses on predicting the **Mechanism of Action (MoA)** of drugs using gene expression and cell viability data, aiding in drug discovery automation.

## 🔗 Links
- [Google Colab Notebook](https://colab.research.google.com/drive/1roP0vQopDMkxfs1LsiFogaJ-342yiE_Y?usp=sharing)
- [GitHub Repo](https://github.com/Sengathir24/Triathlon_GrandTheftAxiosTeam)

## 📁 Dataset Overview
- `train_features.csv`: Contains gene expression (`g-`) and cell viability (`c-`) data.
- `train_targets_scored.csv`: Binary targets for MoA classification.
- `test_features.csv`: Test set features for MoA predictions.

## 🛠️ Techniques Used
- **PCA** for dimensionality reduction.
- **Gaussian Normalization** for feature scaling.
- **TabNet**: Neural network-based model for multi-label classification.

## 📊 Model Performance
- **AUC**: 0.75
- **Logarithmic Loss**: 0.018

## 📐 TabNet Architecture
TabNet uses a combination of attention mechanisms and sequential feature selection. It allows learning from tabular data without extensive preprocessing. The architecture is composed of the following:
- **Feature Transformer**: A shared network for processing input data.
- **Attentive Transformer**: It selects relevant features dynamically.
- **Sparsemax Activation**: Provides sparse attention for feature selection.

TabNet balances interpretability and performance by focusing on the most relevant features, which is beneficial for multi-label classification tasks like MoA prediction.

## 🚀 How to Run the Project
Clone the repository and run the model:
```bash
git clone https://github.com/Sengathir24/Triathlon_GrandTheftAxiosTeam
cd Triathlon_GrandTheftAxiosTeam
python train_model.py
