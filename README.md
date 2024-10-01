🧬 Mechanisms of Action (MoA) Prediction
This project aims to predict the Mechanism of Action (MoA) of drugs based on gene expression and cell viability data, improving drug discovery automation.

🔗 Project Links
Google Colab Notebook
GitHub Repository
📁 Dataset
train_features.csv: Gene expression & cell viability data.
train_targets_scored.csv: Scored MoA annotations.
test_features.csv: Test features for MoA prediction.
🛠️ Key Techniques
PCA: Dimensionality reduction.
Gaussian Normalization: Feature scaling.
TabNet Model: Multi-label classification.
📊 Results
AUC: 0.75
Log Loss: 0.018
🚀 How to Run
bash
Copy code
git clone https://github.com/Sengathir24/Triathlon_GrandTheftAxiosTeam
cd Triathlon_GrandTheftAxiosTeam
python train_model.py
