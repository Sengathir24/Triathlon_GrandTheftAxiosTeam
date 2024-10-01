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

## 🚀 How to Run the Project
Clone the repository and run the model:
```bash
git clone https://github.com/Sengathir24/Triathlon_GrandTheftAxiosTeam
cd Triathlon_GrandTheftAxiosTeam
python train_model.py
