# 🛡️ System Threat Forecaster

This repository contains my Kaggle competition notebook for predicting how likely a system is to get infected by malware.  
The data comes from antivirus software and includes system details along with infection status.  
The goal is to build a machine learning model to estimate the infection risk.

---

## 📂 Project Structure
├── System_Threat_Forecaster.ipynb # Kaggle notebook
├── data/ # Dataset files
│ ├── train.csv
│ ├── test.csv
│ └── sample_submission.csv
└── README.md # Project documentation

---

## 📊 Competition Details
**Competition:** [System Threat Forecaster (Kaggle)](https://www.kaggle.com/)  
**Objective:** Predict the probability of malware infection based on system and security features.

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/System-Threat-Forecaster.git
cd System-Threat-Forecaster
2. Install dependencies
pip install -r requirements.txt

3. Add dataset

Place the dataset files in the data/ directory.
If you are participating in the competition, download the dataset from Kaggle:

kaggle competitions download -c COMPETITION_NAME
unzip COMPETITION_NAME.zip -d data

🚀 Running the Notebook

You can open and run the notebook locally or in Google Colab:

jupyter notebook System_Threat_Forecaster.ipynb


Or run in Kaggle Notebooks for direct access to the competition dataset.

📈 Model Overview

Data preprocessing with pandas and numpy

Feature scaling and encoding with sklearn

Visualization with matplotlib and seaborn

Model training with RandomForestClassifier and hyperparameter tuning

📝 Results

Achieved 62.47% accuracy on the validation set

Best performing model: RandomForestClassifier

📌 Notes

The dataset is not included here due to Kaggle's competition rules.
You can download it from the competition page after accepting the terms.

Modify the notebook to experiment with different models and features.
